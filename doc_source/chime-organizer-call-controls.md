# Hosting a meeting<a name="chime-organizer-call-controls"></a>

The meeting host, delegate, or moderators who are signed in to the Amazon Chime app can perform additional actions during a meeting\. For more information about moderated meetings, see [Scheduling a moderated meeting](moderate-meeting.md)\.

## Mute attendee actions<a name="mute-actions"></a>

The meeting host, delegate, or moderators can perform the following muting actions:
+ **Mute All Others** – Mutes meeting attendees\. Use this to eliminate an echo or external noise\. Attendees are able to unmute themselves to resume audio\.
+ **Disable Attendee Unmute** – Meeting attendees are not able to unmute themselves\. \(Moderators must be signed in to the Amazon Chime app to perform this action\.\)
+ **Enable Attendee Unmute** – Returns unmute control to meeting attendees\. \(Moderators must be signed in to the Amazon Chime app to perform this action\.\)

## Record meeting actions<a name="record-actions"></a>

The meeting host, delegate, or moderators can perform the following recording actions:
+ Start and stop recording the meeting by choosing the **More** menu, then **Start Recording** or **Stop Recording**\. From a phone or in\-room video system, press \*2\.

When meeting attendees join, they are notified audibly and visually that their meeting is being recorded\. When meeting recording is stopped, the attendees receive an update that the meeting is no longer being recorded\. Recording automatically stops when the meeting ends\.

The meeting host, delegate, or moderator that started the recording receives a file of the recording in an Amazon Chime chat message\. If a moderator started the recording from a phone or in\-room video system, or joined the meeting without signing into the Amazon Chime app, the recording is sent to the meeting host only\.

Amazon Chime sends \.m4a files for recordings that include audio only\. If screen share is active during a recording, Amazon Chime sends an \.mp4 file\. Any portions of the meeting that do not include screen sharing are blank during playback\.

**Note**  
Recorded meeting files tend to be a large size\. To share them with attendees, upload them to a file\-sharing service, such as Amazon WorkDocs, and share the file link\. Videos are not included in the recordings\.

## Event mode actions<a name="event-actions"></a>

The meeting host, delegate, or moderators who are signed in to the Amazon Chime app can turn on **Event Mode** after the meeting has started\. Turning on **Event Mode** causes the following to happen:
+ The meeting host, delegate, or moderators who are signed in to the Amazon Chime app are automatically granted presenter permissions\.
+ Attendees who are already in the meeting are muted\.
+ Attendees who join the meeting during **Event Mode** are muted, unless they are joining from an in\-room video conference system\. These attendees can mute themselves by using their video conference device, or another attendee can mute them in the Amazon Chime app\.
+ Only the attendees that are presenters can mute other presenters, share their screen, or turn on their webcam\.
+ Notifications are not displayed for the following roster event changes:
  + Attendees joining the meeting
  + Attendees leaving the meeting
  + Attendees dropping from the meeting
+ Attendees who try to perform a restricted task receive a message that the action has been turned off by the host\.
+ If attendees join from an in\-room conference system after **Event Mode** is turned on, the video from their room is blocked and they are unable to share content\. Other attendees can view videos only from presenters or from in\-room conference systems that join before **Event Mode** is turned on\. Presenters can allow new rooms to join with video by turning off **Event Mode** before the new room joins\. However, any other rooms that joined while **Event Mode** was on must leave the meeting and join again to share their video and content\.
**Note**  
If attendees join from an in\-room conference system before **Event Mode** is turned on, the video from their room is not blocked and they are able to share content\.

The meeting host, delegate, or moderators who are signed in to the Amazon Chime app can promote an attendee to a presenter by following these steps:

**To promote an attendee to presenter**

1. Choose **More**, **Add Presenters**\.

1. Check the boxes next to the attendees and choose **Add**\.

1. Attendees who are given permission to present are notified and identified by the Event Mode icon in the roster\.

**Note**  
The presenter role does not affect in\-room video conference systems\.

The meeting host, delegate, or moderators who are signed in to the Amazon Chime app can also perform the following actions in Event Mode:
+ Turn off an attendee's ability to present by choosing a name on the roster and **Remove from Presenters**\.
+ Turn Event Mode off by choosing **More**, **Disable Event Mode**\. This allows attendees to mute, unmute, share their screen, and turn on video\.

## Remove attendee actions<a name="remove-actions"></a>

The meeting host, delegate, or moderators who are signed in to the Amazon Chime app can remove other attendees from a meeting as long as the other attendees are not a host, delegate, or moderator\. To remove another attendee, choose or right\-click the attendee's name in the meeting roster and choose **Remove from meeting**\. If the removed attendee was previously invited, they are also removed from the meeting invitation and the meeting is no longer displayed as an ongoing meeting in their Amazon Chime app\.

## Lock meeting actions<a name="lock-actions"></a>

To prevent a removed attendee or an uninvited or unauthenticated user from joining a meeting, the meeting host, delegate, or moderators can lock the meeting\. If attendees with no Amazon Chime account or attendees who are not invited try to join a locked meeting, they receive a message that the meeting is locked\. Attendees who are signed in to their Amazon Chime accounts and are invited can still join the meeting, even if they have to drop and reconnect after the meeting is locked\. Attendees who join a locked meeting from an in\-room video system or by using the **Dial\-in** or **Switch to dial\-in** options must enter the 13\-digit meeting ID that appears in the Amazon Chime client or web app in order to join\.

## Large meeting experience settings<a name="large-meeting-settings"></a>

For meetings that you host with more than 25 invitees and attendees, Amazon Chime applies the following large meeting experience settings:
+ New attendees are muted when they join the meeting, unless they are joining from an in\-room video system\.
+ Notifications are not displayed for the following roster event changes:
  + Attendees joining the meeting
  + Attendees leaving the meeting
  + Attendees dropping from the meeting
  + Invitees declining the meeting
+ Join and leave tones are turned off\.
+ Attendees who join from an Amazon Chime app receive a message in the meeting chat with information about the changed meeting experience for the large meeting\.

You can turn off large meeting experience settings for meetings that you host\.

**To turn off large meeting experience settings**

1. In the Amazon Chime app, open the Amazon Chime menu next to your name\.

1. Choose **Settings**\.

1. Choose **Meetings**\.

1. Under **Meeting experience**, clear the check box for **Mute new attendees, turn off join and leave tones, and suppress roster notifications**\.

1. Close the **Settings** pane to return to the **Home** screen\.

To turn on large meeting experience settings again, repeat steps 1\-3\. Select the check box for **Mute new attendees, turn off join and leave tones, and suppress roster notifications**\.