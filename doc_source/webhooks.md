# Automating Chat Messages with Webhooks<a name="webhooks"></a>

You can use incoming webhooks to programmatically send messages to chat rooms\. For example, you can notify a customer service team about the creation of a new, high\-priority ticket and add a link to the ticket in the chat room\. Webhooks require custom development or third\-party tools that can help integrate external systems with Amazon Chime\. You can create up to 10 webhooks for each chat room\.

Webhooks messages can be formatted with markdown and can include emojis\. HTTP links and email addresses render as clickable links\. Messages can also include @All and @Present annotations to alert all members and present members of a chat room, respectively\. To directly @mention a chat room participant, use their alias or full email address\. For example, @`alias` or @`alias@domain.com`\.

Attachments are currently not supported\.

**To create a webhook for a chat room**
**Note**  
Webhooks can only be a part of a chat room and can't be shared\.

1. A chat room administrator creates a webhook for a chat room and copies the webhook URL into an application or script that the administrator has tasked with updating the chat room:

   1. Open the Amazon Chime desktop client \(Windows or macOS\)\.

   1. Choose the gear icon in the upper\-right corner and choose **Manage webhooks**\.

   1. In the **Manage webhooks** dialog box, choose **New**, enter a name for the webhook, and choose **Create**\.

   1. Verify that the webhook that you created is listed, and choose **Copy webhook URL** to send the webhook URL to the webhook developer\.

1. The script or application uses the webhook URL to send messages from an external system to a chat room:

   1. The URL accepts an HTTP POST request\. 

   1. Amazon Chime webhooks accept a JSON payload with a single key **Content**\. The following is a sample curl command with a sample payload:

      ```
      curl -X POST "<Insert your webhook URL here>" -H "Content-Type:application/json" --data '{"Content":"Message Body emoji test: :) :+1: link test: http://sample.com email test: marymajor@example.com All member callout: @All All Present member callout: @Present"}'
      ```

      The following is a sample PowerShell command for Windows users:

      ```
      Invoke-WebRequest -Uri '<Insert your webhook URL here>' -Method 'Post' -ContentType 'application/JSON' -Body '{"Content":"Message Body emoji test: :) :+1: link test: http://sample.com email test: marymajor@example.com All member callout: @All All Present member callout: @Present"}'
      ```

1. After the external program sends the HTTP POST to the webhook URL, the server validates that the webhook is valid and has an assigned chat room\.

1. The server relays the message to the chat room members in the Amazon Chime client \(mobile and desktop\)\. 
**Note**  
You can confirm that a webhook is in a chat room by seeing its name in the chat room roster with a webhook icon\. Every webhook post in the chat room shows the webhook name followed by “\(Webhook\)"\.

1. Amazon Chime users read the messages in the corresponding chat room\. 
**Note**  
Users can't interact with webhooks or send messages back\.

1. Repeat the process for each chat room in which you would like to use incoming webhooks\.

**Note**  
CORS is not currently enabled for webhooks\.

## Webhooks Errors<a name="webhooks-errors"></a>

The following is a list of webhook\-related errors:
+ The incoming webhook rate limit for each webhook is 1 TPS per chat room\. Throttling results in an HTTP 429 error\. 
+ Messages posted by a webhook must be 4 KB or less\. A bigger message payload results in an HTTP 413 error\.
+ Messages posted by a webhook with @All and @Present annotations work only for chat rooms with 50 or fewer members\. More than 50 members results in an HTTP 400 error\.
+ If the webhook URL is regenerated, using the old URL results in an HTTP 404 error\.
+ If the webhook in a room is deleted, using the old URL results in an HTTP 404 error\.
+ Invalid webhook URLs result in HTTP 403 errors\.
+ If the service is unavailable, the user receives an HTTP 503 error in the response\.