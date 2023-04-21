# Using Event Mode<a name="event-actions"></a>

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