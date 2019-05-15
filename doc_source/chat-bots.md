# Using Chat Bots<a name="chat-bots"></a>

Amazon Chime supports integration with chat bots that your Amazon Chime Enterprise account administrator creates\. With chat bots, you can use the power of Amazon Lex, AWS Lambda, and other AWS services to streamline common tasks with intelligent conversational interfaces that are accessible to users in Amazon Chime chat rooms\.

Amazon Chime administrators can use chat bots to allow users to perform various tasks, such as the following:
+ Querying for information from internal systems
+ Automating tasks
+ Receiving notifications for critical issues
+ Creating support tickets

When Amazon Chime administrators integrate chat bots with Amazon Chime, users can interact with the chat bot in chat rooms created by members of the same Amazon Chime account\. For more information about how administrators can integrate a chat bot with Amazon Chime, see [Managing Chat Bots](https://docs.aws.amazon.com/chime/latest/ag/manage-chat-bots.html) in the *Amazon Chime Administrator Guide*\.

## Adding a Chat Bot to a Chat Room<a name="add-bot-chat"></a>

Only chat room administrators can add chat bots to chat rooms\. Before you begin, get the chat bot's email address from your Amazon Chime account administrator\.

**To add a chat bot to a chat room**

1. Open your Amazon Chime desktop client or web application\.

1. Choose the gear icon in the upper\-right corner and choose **Manage webhooks and bots**\.

1. Choose **Add bot**\.

1. For **Email address**, enter the bot email address provided by your administrator\.

1. Choose **Add**\.

The bot name appears in the chat room roster\. Details about how to use the bot should be provided by your Amazon Chime account administrator\.

If you are a member of a chat room with a chat bot added to it, you can interact with the chat bot\. Type @*botDisplayName* and include any of the commands enabled for the bot\. Because each bot is unique to your Amazon Chime account, contact your administrator for assistance with bot commands\. 