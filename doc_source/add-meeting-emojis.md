# Adding emojis to in\-meeting chat messages<a name="add-meeting-emojis"></a>

If you join an Amazon Chime meeting in a browser, or on an iOS or Android machine, you use an emoji picker to add emojis to chat messages\. However, if you run the Amazon Chime desktop client on a PC or Macintosh, you use *emoji codes*, words and characters that specify a given emoji\. The codes look like this: `:`*characters*`:`\. For example, `:+1:` inserts the thumbs\-up emoji into a message\. You can add the codes to chat messages manually, or you can copy and paste them\. The emojis appear when you send a chat message during a meeting\.

**Topics**
+ [Using common emojis](#emoji-codes)
+ [Preventing emojis from appearing](#prevent-emojis)

## Using common emojis<a name="emoji-codes"></a>

The following table lists the codes for several common emojis\.


|  Name  |  Code  |  Image  | 
| --- | --- | --- | 
|  Thumbs up  |  `:+1:`  |  ![\[Thumbs up emoji.\]](http://docs.aws.amazon.com/chime/latest/ug/images/thumbsup.png)  | 
|  Thumbs down  |  `:-1:`  |  ![\[Thumbs down emoji.\]](http://docs.aws.amazon.com/chime/latest/ug/images/thumbsdown.png)  | 
|  Smile  |  `:smiley:`  |  ![\[Smile emoji.\]](http://docs.aws.amazon.com/chime/latest/ug/images/smile.png)  | 
|  Frown  |  `:frowning:`  |  ![\[Frown emoji.\]](http://docs.aws.amazon.com/chime/latest/ug/images/frown.png)  | 
|  Blush  |  `:blush:`  |  ![\[Blush emoji.\]](http://docs.aws.amazon.com/chime/latest/ug/images/blush.png)  | 

For a complete list of emoji codes, see the [Web FX emoji cheat sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)\.

## Preventing emojis from appearing<a name="prevent-emojis"></a>

Emojis can appear when you don't want them\. For example, if you enter **C:\\Users** in a message, Amazon Chime reads the **C:** as an emoji code and replaces it with a smiling emoji: ![\[A smiling emoji, a backslash, and the word Users.\]](http://docs.aws.amazon.com/chime/latest/ug/images/code-emoji.png)\.

To prevent that from happening, start each message with **/code**\. For example, entering **/code C:\\users** results in `C:\Users`\. 

Remember these facts about **/code**\.
+ It must be the first word in a message\.
+ It converts your text to a monospaced font\.
+ It prevents autocompletion of emojis and hyperlinks\.
+ It applies to all the text in a message, regardless of line breaks\. For example:

  ```
  You can find my code snippet at C:\Users\Java\Snips, or just copy and paste from here.
  
  public class Game {
      private Random r = new Random();
      private int answer;
      private int range = 10;
  ```

In addition to the **/code** command, you can also use markdown to format your messages\. For more information about markdown, see the [Amazon Chime 4\.17 release notes](https://answers.chime.aws/articles/642/amazon-chime-417-release-notes.html)\.