# Adding Webhooks to Chat Rooms<a name="webhooks"></a>

Incoming webhooks can programmatically send messages to chat rooms\. For example, a webhook can notify a customer service team about the creation of a new, high\-priority ticket and add a link to the ticket in the chat room\. Webhooks require custom development or third\-party tools that can help integrate external systems with Amazon Chime\. For more information, see [Webhooks for Amazon Chime](https://docs.aws.amazon.com/chime/latest/dg/webhooks.html) in the *Amazon Chime Developer Guide*\.

Webhooks can only be part of a chat room and can't be shared\. Amazon Chime chat room administrators can add up to 10 webhooks for each chat room\.

Webhooks messages can be formatted with markdown and can include emojis\. HTTP links and email addresses render as clickable links\. Attachments are not currently supported\. Messages can include @All and @Present annotations to alert all members and present members of a chat room, respectively\. To directly @mention a chat room participant, use their alias or full email address\. For example, @`alias` or @`alias@domain.com`\.

**Note**  
Amazon Chime chat room members can't interact with webhooks or send messages back\.

Amazon Chime chat room administrators can use the following procedure to add a webhook to a chat room\.

**To add a webhook to a chat room**

1. Open the Amazon Chime desktop client \(Windows or macOS\)\.

1. Choose the gear icon in the upper\-right corner and choose **Manage webhooks**\.

1. In the **Manage webhooks** dialog box, choose **New**, enter a name for the webhook, and choose **Create**\.

1. Verify that the webhook that you created is listed, and choose **Copy webhook URL**\.

1. Send the webhook URL to the webhook developer\.

The webhook developer uses the webhook URL in their application to allow it to send messages to the Amazon Chime chat room\. The webhook appears in the chat room roster with a webhook icon next to its name\. Chat room messages sent by the webhook appear in the chat room under the webhook name followed by **\(Webhook\)**\.