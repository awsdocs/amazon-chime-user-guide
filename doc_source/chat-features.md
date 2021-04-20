# Using chat features<a name="chat-features"></a>

You can use the following features with Amazon Chime chat\.

**Search as you type**  
Searches your contacts, conversations, and chat rooms and starts displaying results as you type in the search bar\. Press **Enter** to search all content\.

**External content URL previews**  
Shows a preview of content, such as titles, descriptions, and thumbnails, when pasting URLs to external sites\.

**Message actions**  
Message actions display in the menu next to a message\. Choose **Copy** to copy the message to your clipboard\. Choose **Quote message** to insert the selected message into your compose message field as a quotation\. To report a message to your administrator for removal, choose **Copy message ID** to copy the message ID information to your clipboard, then send the information to your administrator\.

**Rich text support for markdown and code blocks**  
Use [markdown syntax](http://commonmark.org/help) to format text using bold font, lists, and heading levels, and other options\. Amazon Chime also supports sending code blocks\. For more information, see [Sending markdown messages](#send-chat-markdown) and [Sending code blocks in messages](#send-chat-code)\.

**Emoji and \.gif support**  
To insert an emoji in Amazon Chime chat—not the chat in a meeting—choose **Pick an emoji** next to the chat input field\. You can also choose **Attach a file** to upload a saved \.gif file into the chat input field and play it inline, or use markdown to display \.gif files from the web\.   
You can also send emojis in chat messages during meetings, but the method you use depends on your machine and how you run Chime\. If you run the Amazon Chime desktop client on a PC or a Mac, you use *emoji codes*, words or numbers surrounded by colons\. If you run Amazon Chime in a browser, or on iOS and Android machines, you use an emoji picker\. For more information about using markdown, see [Sending markdown messages](#send-chat-markdown)\. For more information about using emoji codes in meeting chats, see [Adding emojis to in\-meeting chat messages](add-meeting-emojis.md)\.

**Drag and drop files**  
Drag and drop files into the chat pane, or copy and paste images directly from your clipboard\.

## Sending markdown messages<a name="send-chat-markdown"></a>

To send an Amazon Chime chat message using [markdown syntax](http://commonmark.org/help), enter `/md` followed by a space at the beginning of your message\. Compose your message using markdown syntax\. Press **Enter** to send\.

The following example demonstrates how to format an Amazon Chime chat message using markdown syntax\.

```
/md **Hello world!**
```

The message looks like this when sent\.

```
Hello world!
```

The following example demonstrates how to format a web link to a \.gif file using markdown syntax\. This displays the \.gif file in your Amazon Chime chat message\.

```
/md ![](https://example.com/filename.gif)
```

## Adding emojis to chat messages<a name="add-emojis"></a>

You can add emojis to your chat messages at any time\. In Amazon Chime chat&emdash;not the chat in meetings&emdash;choose the **Pick an emoji** icon next to the chat input field, then pick the emoji that you want to add\.

## Sending code blocks in messages<a name="send-chat-code"></a>

To send a code block in an Amazon Chime chat message, type `/code` followed by a space at the beginning of your message\. Copy and paste your code block into the message\. Press **Enter** to send\.

The following table lists the markdown for inserting several common emojis\. You enter or copy and paste the codes, then press **Enter**\. Remember to start and end each code with a colon \(**:**\)\.


| Name | Code | Image | 
| --- | --- | --- | 
| Thumbs up | `:+1:` |  ![\[Thumbs up emoji.\]](http://docs.aws.amazon.com/chime/latest/ug/images/thumbsup.png)  | 
| Thumbs down | `:-1:` |  ![\[Thumbs down emoji.\]](http://docs.aws.amazon.com/chime/latest/ug/images/thumbsdown.g)  | 
| Smile | `:smiley:` |  ![\[Smile emoji.\]](http://docs.aws.amazon.com/chime/latest/ug/images/smile.png)  | 
| Frown | `:frowning:` |  ![\[Frown emoji.\]](http://docs.aws.amazon.com/chime/latest/ug/images/frown.png)  | 
| Blush | `:blush:` |  ![\[Blush emoji.\]](http://docs.aws.amazon.com/chime/latest/ug/images/blush.png)  | 

For a complete list of emoji codes, see the Web FX [emoji cheat sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)\.

## Sending code blocks in messages<a name="send-chat-blocks"></a>

To send a code block in an Amazon Chime chat message, type `/code` followed by a space at the beginning of your message\. Copy and paste your code block into the message\. Press **Enter** to send\.

The following example demonstrates how to send a code block in an Amazon Chime chat message\.

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