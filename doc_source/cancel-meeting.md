# Canceling meetings<a name="cancel-meeting"></a>

The information in the following sections explains how to cancel individual and recurring meetings, including meetings that continue to auto call after you cancel them\.

**Topics**
+ [Canceling individual meetings](#cancel-individual-meeting)
+ [Canceling recurring meetings that continue to auto call](#cancel-recurring-meeting)
+ [Removing yourself from a recurring meeting when you aren't the organizer](#w25aac14c29c11)

## Canceling individual meetings<a name="cancel-individual-meeting"></a>

If you use a calendar application to create an individual meeting, you use that same app to cancel the meeting\. If your calendar app prompts you, send the cancellation to all attendees\.

We assume that you know how to use your calendar app to do that task\.

## Canceling recurring meetings that continue to auto call<a name="cancel-recurring-meeting"></a>

If you use a calendar app to create a recurring meeting, you use that app to cancel the meeting\. Just make sure you send the cancellation to **meet@chime\.aws**\. If your calendar app prompts you to do so, send the cancellation to all attendees\.

But, some calendar apps don't send the information—a \.ics file— that **meet@chime\.aws** needs to delete that meeting\. As a result, Amazon Chime might continue to auto\-call attendees even though the meeting doesn't appear on their calendars\. To stop the auto calls, use the Amazon Chime Windows, macOS, or web clients to cancel the meeting\. The following steps explain how\.

**Note**  
You can cancel recurring meetings from 30 minutes before they start until they reach their scheduled end time or someone ends the meeting\.

**To cancel a recurring meeting**

1. From the **Amazon Chime** app, choose **Home**\.

1. A list of **In progress meetings** and **Upcoming meetings**—meetings starting in the next 30 minutes—appears\.

1. Select a meeting that you host, and choose **Delete meeting series**\.

1. When prompted, confirm the deletion\.

1. Amazon Chime ends the meeting for all attendees, if it has already started\. The host and invited attendees won’t receive auto\-calls for any future meetings in the recurring series\.

## Removing yourself from a recurring meeting when you aren't the organizer<a name="w25aac14c29c11"></a>

To remove yourself from a recurring meeting that you don't own, follow the steps in [ Removing yourself from a recurring meeting ](https://docs.aws.amazon.com/chime/latest/ug/remove-recurring.html)\. 