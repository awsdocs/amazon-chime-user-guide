# Hosting a Meeting<a name="chime-organizer-call-controls"></a>

The meeting host, delegate, or moderators who are signed in to the Amazon Chime app can perform additional actions during a meeting\. For more information about moderated meetings, see [Scheduling a Moderated Meeting](moderate-meeting.md)\.

## Mute Attendee Actions<a name="mute-actions"></a>

The meeting host, delegate, or moderators can perform the following muting actions:
+ **Mute All Others** – Mutes meeting attendees\. Use this to eliminate an echo or external noise\. Attendees are able to unmute themselves to resume audio\.
+ **Disable Attendee Unmute** – Meeting attendees are not able to unmute themselves\. \(Moderators must be signed in to the Amazon Chime app to perform this action\.\)
+ **Enable Attendee Unmute** – Returns unmute control to meeting attendees\. \(Moderators must be signed in to the Amazon Chime app to perform this action\.\)

## Record Meeting Actions<a name="record-actions"></a>

The meeting host, delegate, or moderators can perform the following recording actions:
+ Start and stop recording the meeting by choosing the **More** menu, then **Start Recording** or **Stop Recording**\. From a phone or in\-room video system, press \*2\.

When meeting attendees join, they are notified audibly and visually that their meeting is being recorded\. When meeting recording is stopped, the attendees receive an update that the meeting is no longer being recorded\. Recording automatically stops when the meeting ends\.

The meeting host, delegate, or moderator that started the recording receives a file of the recording in an Amazon Chime chat message\. If a moderator started the recording from a phone or in\-room video system, or joined the meeting without signing into the Amazon Chime app, the recording is sent to the meeting host only\.

Amazon Chime sends \.m4a files for recordings that include audio only\. If screen share is active during a recording, Amazon Chime sends an \.mp4 file\. Any portions of the meeting that do not include screen sharing are blank during playback\.

**Note**  
Recorded meeting files tend to be a large size\. To share them with attendees, upload them to a file\-sharing service, such as Amazon WorkDocs, and share the file link\. Videos are not included in the recordings\.

## Event Mode Actions<a name="event-actions"></a>

The meeting host, delegate, or moderators who are signed in to the Amazon Chime app can turn on **Event Mode** after the meeting has started\. This sets the following controls:
+ Attendees are muted\. Anyone who joins is muted immediately\.
+ Attendees who are not presenters cannot mute other attendees, share their screen, or turn on their webcam\.
+ Roster notifications are disabled for attendees who join, leave, or change status\.
+ Attendees who try to perform a restricted task receive a message that the action has been disabled by the host\.

The meeting host, delegate, or moderators who are signed in to the Amazon Chime app are automatically granted presenter permissions\. They can promote an attendee to a presenter by following these steps:

**To promote an attendee to presenter**

1. Choose **More**, **Add Presenters**\.

1. Check the boxes next to the attendees and choose **Add**\.

1. Attendees who are given permission to present are notified and identified by the Event Mode icon in the roster\.

The meeting host, delegate, or moderators who are signed in to the Amazon Chime app can also perform the following actions in Event Mode:
+ Turn off an attendee's ability to present by choosing a name on the roster and **Remove from Presenters**\.
+ Turn Event Mode off by choosing the Event Mode icon and **Disable Event Mode**\. This allows attendees to mute, unmute, share their screen, and turn on video\.

## Remove Attendee Actions<a name="remove-actions"></a>

The meeting host, delegate, or moderators who are signed in to the Amazon Chime app can remove other attendees from a meeting as long as the other attendees are not a host, delegate, or moderator\. To remove another attendee, choose or right\-click the attendee's name in the meeting roster and choose **Remove from meeting**\. If the removed attendee was previously invited, they are also removed from the meeting invitation and the meeting is no longer displayed as an ongoing meeting in their Amazon Chime app\.

## Lock Meeting Actions<a name="lock-actions"></a>

To prevent a removed attendee or an uninvited or unauthenticated user from joining a meeting, the meeting host, delegate, or moderators can lock the meeting\. If attendees with no Amazon Chime account or attendees who are not invited try to join a locked meeting, they receive a message that the meeting is locked\. Attendees who are signed in to their Amazon Chime accounts and are invited can still join the meeting, even if they have to drop and reconnect after the meeting is locked\. Attendees who join a locked meeting from an in\-room video system or by using the **Dial\-in** or **Switch to dial\-in** options must enter the 13\-digit meeting ID that appears in the Amazon Chime client or web app in order to join\.