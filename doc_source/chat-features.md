# Using Chat Features<a name="chat-features"></a>

You can use the following features with Amazon Chime chat\.

**Search as you type**  
Searches your contacts, conversations, and chat rooms and starts displaying results as you type in the search bar\. Press **Enter** to search all content\.

**External content URL previews**  
Shows a preview of content, such as titles, descriptions, and thumbnails, when pasting URLs to external sites\.

**Message actions**  
Message actions display in the menu next to a message\. Use **Copy this message** to copy the message to your clipboard\. Use **Quote this message** to insert the selected message into your compose message field as a quotation, using markdown\. Quoting a message lets you respond to previous messages in context\.

**Rich text support for markdown and code blocks**  
Use [markdown syntax](http://commonmark.org/help) to format text using bold font, lists, and heading levels, and other options\. Amazon Chime also supports sending code blocks\. For more information, see [Sending Markdown Messages](#send-chat-markdown) and [Sending Code Blocks in Messages](#send-chat-code)\.

**Emoji and \.gif support**  
To insert an emoji, choose **Pick an emoji** next to the chat input field\. Amazon Chime also auto-completes most face emoticons in standard chat messages, and in markdown messages for the desktop clients and web application\. Choose **Attach a file** to upload a saved \.gif file into the chat input field and play it inline, or use markdown to display \.gif files from the web\.

**Drag and drop files**  
Drag and drop files into the chat pane, or copy and paste images directly from your clipboard\.

## Sending Markdown Messages<a name="send-chat-markdown"></a>

To send an Amazon Chime chat message using [markdown syntax](http://commonmark.org/help), type `/md` followed by a space at the beginning of your message\. Compose your message using markdown syntax\. Press **Enter** to send\.

The following example demonstrates how to format a Amazon Chime chat message using markdown syntax\.

```
/md **Hello world!**
```

The following example demonstrates how the sent message appears in Amazon Chime\.

```
Hello world!
```

## Sending Code Blocks in Messages<a name="send-chat-code"></a>

To send a code block in an Amazon Chime chat message, type `/code` followed by a space at the beginning of your message\. Copy and paste your code block into the message\. Press **Enter** to send\.

The following example demonstrates how to send a code block in a Amazon Chime chat message\.

```
/code CreateBotRequest createBotRequest = new CreateBotRequest()
    .withAccountId("chimeAccountId")
    .withDisplayName("exampleBot")
    .withDomain("example.com");

chime.createBot(createBotRequest);
```

The following example demonstrates how the sent message appears in Amazon Chime\.

```
CreateBotRequest createBotRequest = new CreateBotRequest()
    .withAccountId("chimeAccountId")
    .withDisplayName("exampleBot")
    .withDomain("example.com");

chime.createBot(createBotRequest);
```
