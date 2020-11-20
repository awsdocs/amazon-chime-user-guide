# Using chatbots<a name="chat-bots"></a>

Chatbots enable you to use Amazon Lex, AWS Lambda, and other AWS services to streamline common tasks such as creating support tickets or querying internal systems for data\. 

The process for creating and using chat bots follows these broad steps
+ System administrators on Amazon Chime Enterprise accounts create chatbots\. For more information about how administrators can integrate a chatbot with Amazon Chime, see [Chatbots](https://docs.aws.amazon.com/chime/latest/dg/chat-bots.html) in the *Amazon Chime Developer Guide*\.
+ As desired, chat room administrators add the chatbots to their chat rooms\. Users can interact with the chatbots, but only in chat rooms created by members of the same Amazon Chime account\.

## Adding a chatbot to a chat room<a name="add-bot-chat"></a>

Only chat room administrators can add chatbots to chat rooms\. The chat room must be created by a member of an Amazon Chime Enterprise account\.

Before you begin, get the chatbot's email address from your Amazon Chime account administrator\.

**To add a chatbot to a chat room**

1. Open your Amazon Chime desktop client or web application\.

1. Choose the gear icon in the upper\-right corner and choose **Manage webhooks and bots**\.

1. Choose **Add bot**\.

1. For **Email address**, enter the chatbot email address provided by your administrator\.

1. Choose **Add**\.

The chatbot name appears in the chat room roster\. Details about how to use the chatbot should be provided by your Amazon Chime account administrator\.

If you are a member of a chat room with a chatbot added to it, you can interact with the chatbot\. Type @*botDisplayName* and include any of the commands enabled for the chatbot\. Because each chatbot is unique to your Amazon Chime account, contact your administrator for assistance with chatbot commands\. 