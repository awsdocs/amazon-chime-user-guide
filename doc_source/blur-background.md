# Using background blur<a name="blur-background"></a>

Sometimes you want to reduce distractions during a meeting, such as people moving behind you\. When that happens, turn on background blurring\. You can turn blurring on whenever you have the meeting window open — before or during a meeting\. You can also control the strength of the blur, and the steps in this topic show you how to do both tasks\.

**Note**  
Currently, background blur only runs in the desktop clients on Windows 10 and macOS Mojave 10\.14 or later\. The feature uses your computer's graphics processing unit \(GPU\) for best performance, and older GPUs may not have the power to run it\. If you try to use background blur on a computer with an unsupported operating system or an older GPU, Amazon Chime displays an advisory message, and the feature won’t start\. If you have an older computer and your video starts to lag, turn off background blur\.

**To turn on background blurring**

1. In the meeting window, open the **More** menu\. 

1. Choose **Blur my video background**\.

   A check mark appears next to the menu item, and blurring remains on until you turn it off\.

Repeat these steps to turn background blurring off\. When you do, the check mark disappears, and the feature remains off until you turn it on\.

**To change the blur strength**

1. In the main Amazon Chime window—not the meeting window—do one of the following:
   + **Windows 10** – Choose **File**, then **Settings**\.

     The **Application Settings** dialog box appears\.
   + **macOS 10\.4 and later** – Choose **Amazon Chime**, then **Preferences**\.

     The **Application preferences** dialog box appears\.

1. Choose the **Video** tab\.

1. Open the **Background Blur Strength** list, and choose a setting\.

   Your video tile shows you how each setting changes the amount of blurring\.

1. Choose a setting that you like, then close the dialog box\. Amazon Chime remembers your setting until you change it\.

**Background blurring and privacy**  
Video background blurring uses a pre\-trained model to detect you and the boundary between you and your background\. Because it's pre\-trained, the feature never uses facial recognition, it never gathers or stores biometric data, and it never uses images stored in a database\.

**For the best experience**  
Background blurring needs contrast to distinguish between you and your background\. Follow these best practices whenever possible:
+ Wear clothes that stand out from what's behind you\.
+ If your video looks grainy, turn on some lights\. Most webcams don't perform well in low light, especially the cameras in laptops\.
+ Try to sit within three feet \(a meter\) of the camera\. Try to sit directly in front of, and look squarely into, the camera\.
+ The feature doesn't recognize hats or other headwear, so it may blur them\.

**Providing feedback**  
If you have any feedback on this feature, leave a comment in the online form that appears when you leave a meeting, or work with your AWS IT Administrator to file a ticket with AWS support\.