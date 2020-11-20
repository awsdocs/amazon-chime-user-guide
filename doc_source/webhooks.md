# Adding webhooks to chat rooms<a name="webhooks"></a>

Webhooks send messages to chat rooms programmatically\. For example, a webhook can notify a customer service team about the creation of a new, high\-priority ticket and add a link to the ticket in the chat message\. Webhooks require custom development or third\-party tools that can help integrate external systems with Amazon Chime\. For more information, see [Webhooks for Amazon Chime](https://docs.aws.amazon.com/chime/latest/dg/webhooks.html) in the *Amazon Chime Developer Guide*\.

Webhooks only work with chat rooms\. You can't share them\. Amazon Chime chat room administrators can add up to 10 webhooks to a chat room\.

You can format webhook messages with markdown, and you can include emojis\. HTTP links and email addresses render as clickable links\. Webhooks currently don't support attachments\. Messages can include @All and @Present annotations to alert all members and present members of a chat room, respectively\. To directly @mention a chat room participant, use their alias or full email address\. For example, @`alias` or @`alias@domain.com`\.

**Note**  
Amazon Chime chat room members can't interact with webhooks or send messages back\.

**To add a webhook to a chat room**
**Note**  
You must be an Amazon Chime administrator to complete these steps\.

1. Open the Amazon Chime desktop client \(Windows or macOS\), then open the desired chat room\.

1. Choose the gear icon in the upper\-right corner and choose **Manage webhooks**\.

1. In the **Manage incoming webhooks and bots** dialog box, choose **Add webhook**, enter a name for the webhook, and choose **Create**\.

1. Verify that the webhook that you created is listed, and choose **Copy URL** to copy the webhook URL to your clipboard\.

1. Send the webhook URL to the webhook developer\.

The webhook developer uses the webhook URL in their application to allow it to send messages to the Amazon Chime chat room\. The webhook appears in the chat room roster with a webhook icon next to its name\. Chat room messages sent by the webhook appear in the chat room under the webhook name followed by **\(Webhook\)**\.