# Using the Amazon Chime web application<a name="chime-web-app"></a>

The Amazon Chime web application brings Amazon Chime meetings and chat to your browser\. The web application makes it easy for clients, vendors, and other third parties to join your meetings, even if they are new to Amazon Chime\. There's no need to create an account and no downloads are required to participate in meetings\. Users with Amazon Chime accounts can sign in to access many of the same features available on our downloadable clients\. It's a great option for users on operating systems that aren't supported by the Amazon Chime desktop and mobile apps, users that can't download the Amazon Chime desktop and mobile apps, or users that prefer web applications\.

Joining and scheduling meetings from the web application works the same way as the Amazon Chime desktop and mobile apps\. For more information, see [Attending meetings using Amazon Chime](chime-attend-meetings.md) and [Scheduling meetings using Amazon Chime](chime-schedule-meetings.md)\. Attendees that join your meetings using the web app can view and share screens, view and share video, use the meeting roster, participate in meeting chat, and join audio by dialing in on their phone or though their computer’s audio\. 

Additionally, if your administrator has enabled the Amazon Chime call me feature, your meeting attendees can choose **Call me at a phone number** to have Amazon Chime call them at their preferred phone number\.

To use the Amazon Chime web application, sign in to [https://app\.chime\.aws/](https://app.chime.aws/) from your web browser\.

**Note**  
The downloadable clients available in Amazon Chime provide the most consistent experience for video, screen sharing, remote desktop control, and other features on supported operating systems\. For more information, see [downloadable clients](https://aws.amazon.com/chime/download/)\. 

## Supported browsers<a name="web-app-browsers"></a>

The Amazon Chime web application works best with Google Chrome or Mozilla Firefox\. Mobile browsers are not currently supported\. 

For a complete list of supported browsers, see [Browser requirements](chime-requirements.md#browser)\.

## Chat features in the Amazon Chime web application<a name="web-app-chat"></a>

Chat features in the Amazon Chime web application lets you send direct messages, request chat room access using web application URLs, and navigate with browser controls\.

You can also use keyboard shortcuts in the web application\. Type `Ctrl + /` to view Windows shortcuts, or `cmd + /` to view macOS shortcuts\. 

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

## Meeting audio options for the Amazon Chime web application<a name="web-app-audio"></a>

Choose from the following audio options when you join a meeting using the Amazon Chime web application:

**Use my computer's microphone and speakers**  
Amazon Chime provides high\-quality audio using your computer's internet connection\. 

**Call me at a phone number**  
If your administrator has enabled the Amazon Chime call me feature, Amazon Chime calls you at your preferred phone number\. This feature is recommended for unreliable or slow internet connections\. Depending on the destination country of the phone number that Amazon Chime calls, different rates apply\. For more information about Amazon Chime pricing, see [http://chime\.aws](http://chime.aws)\.

**I will dial in manually and enter the meeting PIN**  
Amazon Chime provides dial\-in phone numbers and a unique meeting ID\. This option is recommended for unreliable or slow internet connections\. Depending on the dial\-in option that you choose, charges may apply\.

**I am using another audio source or already connected**  
This option is recommended if you are already dialed in using a phone, or if you're in the same room with another attendee who is already connected to audio on their computer\. 

The Amazon Chime web application uses your default audio device\. If you use Mozilla Firefox to join your meeting, you can select a different audio input source in your browser's settings\. 

## Screen sharing options for the Amazon Chime web application<a name="web-app-sharing"></a>

You can share your screen or an application window, if you are using the latest three versions of Mozilla Firefox or Google Chrome\. Screen share is available for Chrome version 72 and Firefox version 66 or later\.

**To share your screen or application window**

1. In the Amazon Chime web application, choose **Screen**, **Start screen share**\.

1. From the drop\-down menu, choose the application window or screen that you want to share\.

1. If prompted, choose **Allow the browser to share**\.

1. To choose a different application window or screen, choose **Screen**, **Change screen share source**\.

1. When you're ready to stop sharing, choose **Screen**, **Stop screen share**\.
**Note**  
If another attendee takes over the meeting, or if the meeting ends, sharing automatically stops\.

## Unsupported features in the Amazon Chime web application<a name="web-app-unsupported"></a>

The following feature is not currently supported in the Amazon Chime web application\.

**Remote Desktop Control**  
Remote desktop control is not supported at this time\.