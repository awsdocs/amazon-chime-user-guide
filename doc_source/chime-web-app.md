# Use the Amazon Chime Web Application<a name="chime-web-app"></a>

The Amazon Chime web application brings Amazon Chime meetings and chat to your browser\. The web application makes it easy for clients, vendors, and other third parties to join your meetings, even if they are new to Amazon Chime\. There's no need to create an account and no downloads are required to participate in meetings\. Users with Amazon Chime accounts can sign in to access many of the same features available on our downloadable clients\. It's a great option for users on operating systems that aren't supported by the Amazon Chime desktop and mobile apps, users that can't download the Amazon Chime desktop and mobile apps, or users that prefer web applications\.

Joining and scheduling meetings from the web application works the same way as the Amazon Chime desktop and mobile apps\. For more information, see [Attend Meetings Using Amazon Chime](chime-attend-meetings.md) and [Schedule Meetings Using Amazon Chime](chime-schedule-meetings.md)\. Attendees that choose to join your meetings on the web application can view shared screens, view and share video, use the meeting roster, participate in meeting chat, and join audio by dialing in on their phone or though their computer’s audio\.

The Amazon Chime web application also lets you format messages in rich text, search as you type, request chat room access using a web application URL, and preview external content URLs\. For more information, see [Chat Features in the Amazon Chime Web Application](#web-app-chat) and [Additional Features in the Amazon Chime Web Application](#web-app-features)\. 

To use the Amazon Chime web application, sign in to [https://app\.chime\.aws/](https://app.chime.aws/) from your web browser\.

**Note**  
The downloadable clients available in Amazon Chime provide the most consistent experience for video, screen sharing, remote desktop control, and other features on supported operating systems\. For more information, see [downloadable clients](https://aws.amazon.com/chime/download/)\. 

## Supported Browsers<a name="web-app-browsers"></a>

The Amazon Chime web application works best with Google Chrome or Mozilla Firefox\. Mobile browsers are not currently supported\. 

For a complete list of supported browsers, see [Browser Requirements](chime-requirements.md#browser)\.

## Chat Features in the Amazon Chime Web Application<a name="web-app-chat"></a>

Chat features in the Amazon Chime web application include the ability to send direct messages, request chat room access using web application URLs, navigate with browser controls, and view your complete conversation history\.

**To send a direct message using a web application URL**
+ Open a direct message to a user in your browser with a URL\. You can message other users with a link from internal web pages, such as a corporate directory or wiki\.

  The URL format is **https://app\.chime\.aws/conversations/new?email=joe@email\.com**, where **joe@email\.com** is the email address of the message recipient\. The intended recipient must be in the sender's contacts\. 

**To send users a web application URL for a chat room**

1. In the Amazon Chime web application, go to the chat room\.

1. Copy the chat room URL from your web browser's navigation bar and send it to the users to join the chat room discussion or request access to it\.

1. Users can use the URL to open the chat room if they have access or request access to if they do not\. 

1. Chat room administrators receive a notification in the chat room that the user requested access and can grant access using the link provided in the notification\.

**To navigate with browser controls**
+ Use the back and forward buttons in your browser to navigate through rooms and conversations you have visited\. Each room and conversation in the Amazon Chime web application has its own URL\.

**To view the complete conversation history**
+ Under **Recent Messages**, choose **All messages** to view complete conversation history arranged by time sent, from most to least recent\. 

## Meeting Audio Options for the Amazon Chime Web Application<a name="web-app-audio"></a>

Choose from the following audio options when you join a meeting using the Amazon Chime web application:

**Use my computer's microphone and speakers**  
Amazon Chime provides high\-quality audio using your computer's internet connection\. 

**I will dial in manually and enter the meeting PIN**  
Amazon Chime provides dial\-in phone numbers and a unique meeting ID\. This option is recommended for unreliable or slow internet connections\. Depending on the dial\-in option that you choose, charges may apply\.

**I am using another audio source or already connected**  
This option is recommended if you are already dialed in using a phone, or if you're in the same room with another attendee who is already connected to audio on their computer\. 

The Amazon Chime web application uses your default audio device\. If you use Mozilla Firefox to join your meeting, you can select a different audio input source in your browser's settings\. 

## Additional Features in the Amazon Chime Web Application<a name="web-app-features"></a>

The Amazon Chime web application lets you search as you type, preview external content URLs, and use rich text messages formatting, keyboard shortcuts, emojis, and \.gif files\.

**Search as you type**  
Searches your contacts, conversations, and chat rooms and starts displaying results as you type in the search bar\. Press **Enter** to search all content\.

**External content URL previews**  
Shows a preview of content, such as titles, descriptions, or thumbnails, when pasting URLs to external sites\.

**Rich text support**  
Supports formatting, such as bold, lists, or heading levels, in messages you send to other web application users\. To send a rich text message, type `/md` and then compose your message using [markdown syntax](http://commonmark.org/help)\.

**Keyboard shortcuts**  
Type `Ctrl + /` to view Windows shortcuts, or `cmd + /` to view macOS shortcuts\. 

**Emoji and \.gif support**  
To insert an emoji, choose **Pick an emoji** next to the chat input field\. Upload saved \.gif files into the chat input field to play it inline, or use markdown to display \.gif files from the web\.

**Note**  
If Amazon Chime users aren't using the web application, they see messages in plain text\.

## Unsupported Features in the Amazon Chime Web Application<a name="web-app-unsupported"></a>

The following features are not currently supported in the Amazon Chime web application\.

**Screen sharing**  
You can't share your screen with other users from the Amazon Chime web application\. However, you can view screens that are shared with you\.

**Remote Desktop Control**  
Remote desktop control is not supported at this time\.