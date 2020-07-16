# Supported commands<a name="assistant-commands"></a>

The Amazon Chime Assistant supports the following commands: 
+ **Get my attachments** allows you to access attachments that you uploaded to 1:1 chat, group chat, and chat rooms that you created\.

  After you enter this command as a chat message to the Assistant, you receive instructions that look similar to the following text in the chat message:

  **To confirm your attachment request, copy and paste this exact command:**

  ```
  Get my attachments ktsben
  ```

  After you provide the requested confirmation, Amazon Chime processes your request and sends you a link to a file in the chat thread within about 24 hours\. The file contains a list of digitally signed links to your attachments\. If there are no attachments that meet the criteria, the file is empty\. The chat message included with the file from the Assistant includes the date and time when the links expire \(about 6 days after delivery\)\.

  Any user that obtains the file can use the provided list of URLs to download the associated attachments\. Make sure to maintain an appropriate level of access control on the delivered file\.

  You can submit this command one time per 7\-day period\. 
+ **Delete me** allows you to delete your profile and data from the Amazon Chime system\.

  After entering the command as a chat message to the Assistant, you receive instructions that look similar to the following text from the assistant in the chat message:

  **To confirm your account deletion request, copy and paste this exact command:**

  ```
  Delete me aofrkq
  ```

  The confirmation is valid for 10 minutes\. If you don't confirm within 10 minutes of the request or if you don't enter the command correctly, the Assistant provides a new confirmation code for you to use to retry the request\.

  After you provide the requested confirmation, you are signed out of Amazon Chime on all your devices\. You no longer have access to your chat, chat rooms, contacts, or scheduled meetings\.
**Note**  
While the **Delete me** command removes the link between your Amazon Chime profile and your amazon\.com account, which you use to sign into Amazon Chime, that account is provided by amazon\.com\. To delete your associated amazon\.com account, go to http://amazon\.com\.
+ **Help** provides a description and instructions for the commands available in the Amazon Chime Assistant\.