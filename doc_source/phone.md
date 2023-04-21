# Dialing phone numbers with Amazon Chime<a name="phone"></a>

If your Amazon Chime administrator has enabled the corresponding calling options for your account, you can use the Amazon Chime client to dial phone numbers in the public switched telephone network \(PSTN\)\. You can also send SMS messages to PSTN phone numbers, add PSTN phone numbers to your contacts, and access voicemail\. For more information, see [Managing phone numbers in Amazon Chime](https://docs.aws.amazon.com/chime/latest/ag/phone-numbers.html) in the *Amazon Chime Administrator Guide*\.

You can also call or message phone numbers or contacts from the past 30 days in **Call history**, under **Meetings and Calls**\.

**Note**  
Amazon Chime is not always a replacement for your telephone\. You can only make emergency calls in the U\.S\.

## Dial a phone number<a name="dial-phone"></a>

**To dial a phone number**

1. From the Amazon Chime desktop or web client **Home** page, choose **Dial a phone number**\.

1. For **Phone number**, enter the country code and phone number without any dashes\. For example, `+12065550100`\.

1. Choose **Dial**\.

When the person you call answers their phone, an instant meeting opens in Amazon Chime\. As a meeting host with Amazon Chime Pro permissions, you can choose **More** to invite others to the call, or to change your meeting settings\. For more information, see [Hosting meetings](chime-organizer-call-controls.md)\.

**To call a phone number from your history**

1. Do one of the following:
   + From the Amazon Chime desktop or web client, under **Meetings and Calls**, choose **Call history**\.
   + From the Amazon Chime mobile app, choose **Calls**\.

1. Select the contact to open the actions menu\.

1. Choose **Call**\.

## Sending an SMS message to a phone number<a name="sms-phone"></a>

If your Amazon Chime administrator has enabled SMS messages for your account, you can send an SMS message to a phone number in your contacts\.

**To send an SMS message to a phone number in your contacts**

1. From the Amazon Chime client, choose **Message**\.

1. Do one of the following:
   + For a new contact, enter the country code and phone number to call, without any dashes\. For example, `+12065550100`\. Choose **Create a new contact**\.
   + For an existing contact, search for and select the contact\.

1. Enter your message\. Press **Enter** to send it\.

An SMS message is sent to the phone number, and a chat conversation between you and the recipient opens in Amazon Chime\. To call the chat recipient, choose the phone icon in the chat conversation\.

**Note**  
Text messaging to and from short codes is not supported\.

**To send an SMS message to a phone number from your history**

1. Do one of the following:
   + From the Amazon Chime desktop or web client, under **Meetings and Calls**, choose **Call history**\.
   + From the Amazon Chime mobile app, choose **Calls**\.

1. Select the phone number or contact to open the actions menu\.

1. Choose **Message**\.

## Adding a phone number to your contacts<a name="phone-contact"></a>

You can add phone numbers to your **Contacts** list\. To edit the contact name after you create it, search for and select the contact in your **Contacts** list, and choose **Edit contact name**\.

**To add a phone number to your contacts**

1. From the Amazon Chime client, choose **Contacts**\.

1. Enter the country code and phone number to add, without any dashes\. For example, `+12065550100`\.

1. Choose **Create a new contact**\.

**To add a phone number from your history to your contacts**

1. Do one of the following:
   + In the Amazon Chime desktop or web client, under **Meetings and Calls**, choose **Call history**\.
   + From the Amazon Chime mobile app, choose **Calls**\.

1. Select the phone number or contact to open the actions menu\.

1. Choose **Add to my contacts**\.

## Accessing voicemail<a name="vm"></a>

If your administrator enables inbound calling, unanswered and declined calls from PSTN phone numbers are redirected to your voicemail\.

**Note**  
Voicemail is currently supported only for calls received from PSTN phone numbers\. Incoming calls from Amazon Chime users are not routed to voicemail\.

**To access voicemail in Amazon Chime**
+ From the Amazon Chime client, under **Recent Messages**, choose **Amazon Chime Voicemail**\.

Each voicemail is accessible as a linked `MP3` file\.

If you receive a voicemail from a PSTN phone number that is in your **Contacts** list, you can access the voicemail file under **Recent Messages** from that contact\.