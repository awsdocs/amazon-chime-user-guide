# Scheduling a moderated meeting<a name="moderate-meeting"></a>

Meeting hosts and delegates with Pro permissions can schedule moderated meetings, which only start when a moderator joins\. Until a moderator joins, moderated meeting attendees cannot interact with each other using audio, video, screen sharing, meeting chat, or the visual roster features\. After moderated meetings start, they continue until the meeting is ended, even if the moderators drop or leave the meeting\.

Meeting hosts and delegates are meeting moderators by default\. If a meeting host or delegate shares the moderator passcode with other attendees, they can also join the meeting as moderators\. There can be multiple moderators for a moderated meeting\. Meeting attendees who enter the moderator passcode can access additional host actions\. They can lock, record, and end meetings, and mute all other attendees\. For more information, see [Moderator actions using the Amazon Chime app](#actions-app) and [Moderator actions using phone or in\-room video systems](#actions-phone-vid)\.

## Joining a meeting as a moderator<a name="mod-join"></a>

Meeting moderators can enter the moderator passcode when prompted to join moderated meetings via phone, supported SIP or H\.323 in\-room video systems, or the Amazon Chime mobile, desktop, or web apps\. When meeting hosts or delegates join their moderated meetings and are signed in to the Amazon Chime app, they are automatically connected to the meeting as moderators without having to enter the moderator passcode\.

**Note**  
Joining a meeting as a moderator is currently not supported for Alexa for Business\.

## Scheduling a moderated meeting<a name="schedule-mod-mtg"></a>

Schedule moderated meetings from the Amazon Chime app\.

**To schedule a moderated meeting**

1. From the Amazon Chime app, choose **Meetings**, **Schedule a meeting**\.

1. In the **Meeting scheduling assistant**, select **Generate a new ID and require moderator to start**\.

1. Enter a 4\-8 digit moderator passcode\.

1. Finish selecting your other meeting options\.

1. Choose **Copy moderator info** to copy and paste the moderator information for your moderated meeting\.

1. Send the moderator information to one or more attendees who will act as meeting moderators\. To protect the moderator passcode, moderator information is not included in the Amazon Chime meeting invite and must be sent to moderators separately\.

**Note**  
Moderator passcodes cannot be changed or added to an existing meeting\. If you forget the moderator passcode, reschedule the meeting with a new meeting ID and passcode\.

If you are scheduling a moderated meeting using one of the Amazon Chime Outlook Add\-Ins, select **Generate a new ID and require moderator to start** and enter a moderator passcode when scheduling the meeting\. Send the moderator passcode to one or more attendees who will act as meeting moderators\.

Meeting attendees who have the moderator passcode can become moderators by entering the passcode after they join the meeting\. To enter the moderator passcode during a meeting in progress, choose **More** from the Amazon Chime app, then choose **Enter moderator passcode**\.

## Moderator actions using the Amazon Chime app<a name="actions-app"></a>

When signing in to join a moderated meeting using the Amazon Chime app, moderators can perform the same actions as meeting hosts and delegates\. For a list of available actions, see [Hosting a meeting](chime-organizer-call-controls.md)\.

If a moderator joins a moderated meeting without signing in, they can use the following subset of host actions:
+ Mute all other attendees\.
+ Start and stop recording the meeting\.
+ Lock and unlock the meeting\.
+ End the meeting for all attendees\.

## Moderator actions using phone or in\-room video systems<a name="actions-phone-vid"></a>

When joining a moderated meeting over the phone or a supported SIP or H\.323 in\-room video system, moderators can perform the following additional meeting actions from the dialpad:
+ **Mute all other attendees** – \*97
+ **Start and stop meeting recording** – \*2
+ **Lock and unlock meeting** – \*4
+ **End meeting for all** – \#\#
+ **See menu \(in\-room video system only\)** – \*0

Any meeting attendee, including moderators, can press \*7 to mute and unmute themselves\.

**Note**  
Recordings started over the phone or an in\-room video system are sent to the meeting host by default\.