# Scheduling Best Practices<a name="chime-scheduling-best-practices"></a>

No matter which app you schedule your meeting from, here are some helpful tips to follow when setting up meetings\.

## Creating a Personalized Link<a name="personalized-link"></a>

When you create an account with Amazon Chime, you receive a 10\-digit Personal Meeting ID\. To make it easier for attendees to join your meetings, you can create a personalized link by choosing **Add Personalized Link** under your name\.

Create a name that is easy for people to associate with you, like your email address prefix or your name\. The name must be at least 12 alpha\-numeric characters or longer \(special characters are not included in the character count\)\. Amazon Chime makes sure it’s unique in the system, and automatically adds it to your meeting instructions\. 

## Helping Mobile Users Join Your Meeting<a name="mobile-users"></a>

When inviting mobile users to your meeting, copy and paste the **One\-click Mobile Dial\-in** into the **Location** field of your meeting invite\. When the calendar reminder appears for the meeting on their mobile devices, they can choose the string to dial in automatically and enter the **Personal Meeting ID**\.

## Enabling or Disabling Auto\-call<a name="autocall"></a>

When your meeting starts, Amazon Chime can call every attendee automatically on all registered devices with Auto\-call\. You and your attendees don’t have to watch the calendar to join the meeting\.

To enable Auto\-call, make sure that **meet@chime\.aws** is invited to your meeting\.

To avoid having everyone’s devices ring at the same time \(for example, if everyone is in the same office\), remove **meet@chime\.aws** from the invitee list\. You can also remove **meet@chime\.aws** if your attendees would rather just open the invite and choose the meeting link\.

## Inviting a Distribution List<a name="distribution-list"></a>

If you have a weekly or monthly meeting with a large team or department, and you don't want to invite individual users one\-by\-one, schedule the meeting with **meet@chime\.aws**, then delete **meet@chime\.aws**\. 

Attendees can open the meeting link in the instructions, choose **Meetings**, **Join a Meeting**, and enter the PIN manually\.

Use caution when using distribution lists with meet@chime\.aws\. To have Amazon Chime initiate the call, you must list individual users\.

## Changing Meeting Details<a name="meeting-details"></a>

When changing meeting details or adding meet@chime\.aws to an existing meeting, remember to choose **Send Updates to All**\.