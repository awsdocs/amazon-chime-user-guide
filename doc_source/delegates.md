# Assigning delegates<a name="delegates"></a>

If you have Amazon Chime Pro permissions, you can assign delegate status to other Pro users\. This status allows them to schedule meetings on your behalf and to attend meetings with access to the same actions that a meeting host has\. For more information about the additional meeting actions available to a delegate, see [Hosting meetings](chime-organizer-call-controls.md)\.

## Assigning delegates<a name="assign-delegates"></a>

Assign delegates using the Amazon Chime desktop client or web application\.

**To assign delegates**

1. On the **Amazon Chime** menu next to your name, choose **Settings**\.

1. Under **Settings**, choose **Delegates**\.

1. Choose **Add delegates**\.

1. Search for and select the name of the contact, then choose **Add**\.

## Setting delegate permissions in Microsoft Outlook<a name="set-delegate-permissions-outlook"></a>

If you use Amazon Chime with Microsoft Outlook, some delegates may not be able to schedule meetings unless they have **Owner** permissions to your inbox\. If your delegate can't schedule meetings, follow these steps:

**To set delegate permissions**

1. In Outlook, open the context \(right\-click\) menu for your inbox and choose **Properties**\.

   The **Inbox Properties** dialog box appears\.

1. Choose the **Permissions** tab, and then choose **Add**\.

   The **Add Users** dialog box appears\. 

1. Search for and select your delegate’s name, and then choose **OK**\.

   That returns you to the **Inbox Properties** dialog box\.

1. Under **Permissions**, open the **Permissions** list and choose **Owner**, then choose **Apply**\. 

## Removing delegates<a name="remove-delegates"></a>

Remove delegates using the Amazon Chime desktop client or web application\.

**To remove delegates**

1. On the **Amazon Chime** menu next to your name, choose **Settings**\.

1. Under **Settings**, choose **Meetings**\.

1. Choose an existing delegate from the list, and choose **Remove**\.

## Scheduling meetings as a delegate with a calendar app<a name="delegate-calendar"></a>

If you are a delegate who schedules meetings for another user on their calendar, and you are not using one of the Amazon Chime [Outlook add\-ins](chime-scheduling-outlook.md) with a Microsoft Outlook calendar, you can schedule meetings by asking the meeting host to follow these steps\.

Before your meeting host begins this procedure, ask them to make sure that you are set up as their delegate in Amazon Chime\. For more information, see [Assigning delegates](#assign-delegates)\.

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

1. Copy and paste the corresponding meeting instructions into the body of the appointment\. Make sure that it includes the link to join the meeting\. An example is **https://chime\.aws/*meeting\-id***\.

1. Add the other meeting attendees to the appointment and finish scheduling it\.

If you are scheduling back\-to\-back meetings, or if it's possible that a meeting might run over into the time slot for another meeting, use a different set of meeting information to schedule the other meetings\.

**Note**  
As a delegate, do not use your own Amazon Chime meeting ID on a delegator's calendar\. This can cause a meeting scheduling failure or split meeting attendees onto different meeting bridges\.

## Scheduling meetings as a delegate using the Outlook Add\-In<a name="delegate-outlook"></a>

When scheduling meetings with the Outlook add\-in, you receive a prompt to select who you are scheduling the meeting for\. For more information, see [Scheduling meetings with the Add\-In for Outlook](chime-scheduling-outlook.md)\.