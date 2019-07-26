# Assigning a Delegate<a name="delegates"></a>

If you have a pro license, you can give delegate status to other pro users\. This enables them to schedule meetings on your behalf and attend meetings with full organizer permissions\.

## Assigning Delegates<a name="assign-delegates"></a>

Assign delegates using the desktop client or web application\.

**To assign delegates**

1. On the **Amazon Chime** menu next to your name, choose **Settings**\.

1. Under **Settings**, choose **Meetings**\.

1. Choose **Add delegates**\.

1. Search for and select the name of the contact, then choose **Add**\.

## Removing Delegates<a name="remove-delegates"></a>

Remove delegates using the desktop client or web application\.

**To remove delegates**

1. On the **Amazon Chime** menu next to your name, choose **Settings**\.

1. Under **Settings**, choose **Meetings**\.

1. Choose an existing delegate from the list, and choose **Remove**\.

## Scheduling Meetings as a Delegate with a Calendar App<a name="delegate-calendar"></a>

If you are a delegate who schedules meetings for another user on their calendar, and you are not using one of the Amazon Chime [Outlook add\-ins](chime-scheduling-outlook.md) with a Microsoft Outlook calendar, you can schedule meetings by asking the meeting host to follow these steps\.

Before your meeting host begins this procedure, ask them to make sure that you are set up as their delegate in Amazon Chime\. For more information, see [Assigning Delegates](#assign-delegates)\.

**To delegate a meeting using a calendar app**

1. From the Amazon Chime desktop client or web application, choose **Meetings**, **Schedule a meeting**\.

1. Select **Generate a new ID**\.

1. Choose **Next**\.

1. For **Select your calendar app:**, choose **Other**\.

1. Choose **Copy addresses**, and paste the addresses into the body of a new email message\.

1. Choose **Copy attendee invitation**, and paste this information into the same email\.

1. In the Amazon Chime app, choose **I am done**\.

1. Repeat steps 1\-7 to generate three sets of meeting IDs\.

1. Send an email with the meeting information to your delegate\.

After you receive this information from your meeting host, schedule the meeting for them by following these steps\.

**To schedule a meeting as a delegate**

1. From the meeting host's calendar, open or create the meeting appointment\.

1. Copy and paste one of the three sets of email addresses into the **To** field\. For example, the email addresses would be **meet@chime\.aws** and **pin\+*meeting\-id*@chime\.aws**\.

1. Copy and paste the corresponding meeting instructions into the body of the appointment\. Make sure that it includes the link to join the meeting\. An example would be **https://chime\.aws/*meeting\-id***\.

1. Add the other meeting attendees to the appointment and finish scheduling it\.

If you are scheduling back\-to\-back meetings, or if is it possible that a meeting might run over into the time slot for another meeting, use a different set of meeting information to schedule the other meetings\.

**Note**  
As a delegate, do not use your own Amazon Chime meeting ID on a delegator's calendar\. This can cause a meeting scheduling failure or split meeting attendees onto different meeting bridges\.

## Scheduling Meetings as a Delegate using the Outlook Add\-In<a name="delegate-outlook"></a>

When scheduling meetings with the Outlook add\-in, you receive a prompt to select who you are scheduling the meeting for\. For more information, see [Scheduling Meetings with the Add\-In for Outlook](chime-scheduling-outlook.md)\.