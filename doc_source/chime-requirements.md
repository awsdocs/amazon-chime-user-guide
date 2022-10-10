# System requirements<a name="chime-requirements"></a>

Before you set up Amazon Chime, first make sure you meet the following requirements\.

Amazon Chime provides client applications for the following operating systems\.

## Windows<a name="windows"></a>

Supported versions:
+ Windows 10, 32\-bit and 64\-bit
+ Windows 8\.1, 32\-bit and 64\-bit 

Hardware requirements:
+ **For audio calls**: Microphone and speakers\.
+ **For sharing video**: Built\-in or external webcam\. 
+ **For video background blur**: Windows 10 or later, Intel 5th generation CPU with integrated GPU, or NVIDIA GPU that supports DX12\. We do not support AMD GPUs\.
+ **For Amazon Voice Focus** \(noise suppression\): Windows machines with 4th generation Intel processors or later, or the equivalent AMD processors\.

Software requirements:
+ **For Amazon Chime client installation**: The Microsoft \.NET framework, version 4\.5\.2 or later\. Amazon Chime prompts you to update the framework if it detects an older version\.
+ **For video**: The MediaFoundation Pack \([https://www\.microsoft\.com/en\-us/software\-download/mediafeaturepack](https://www.microsoft.com/en-us/software-download/mediafeaturepack)\)
+ **For video background blur**: The Visual C\+\+ 2019 runtime, and the English language package configured for the en\_US\.UTF\-8 locale\.

Screen share configuration requirements:
+ **Screen Share** must be set to **Aero and Non\-Aero themes**\.
+ **Display Setting Scaling** must be set to **100% and custom settings**\.

## macOS<a name="mac"></a>

Supported versions:
+ OS X 10\.12 and later

Hardware requirements:
+ **For audio calls**: Microphone and speakers
+ **For sharing video**: Built\-in or external webcam
+ **For video background blur**: OS X 10\.14 \(Mojave\) and later
+ **For Amazon Voice Focus** \(noise suppression\) macOS machines from 2007 and later

**Note**  
M1 MacBooks are not supported\.

## Android<a name="android"></a>

Supported versions:
+ Android OS 5\.0 and later

Software requirements:
+ OpenGL ES is required for the screen share viewer\.
+ Google services and a Google Account are required for the best messaging experience\.

Hardware requirements:
+ Some features are only available on devices with Bluetooth, telephony, or Wi\-Fi\.
+ Tablet and phone devices are supported\.
+ Kindle Fire tablets are currently not supported\.

## iOS<a name="ios"></a>

Supported versions:
+ iOS 12\.0 and later

Hardware requirements:
+ Some features are only available on devices with Bluetooth, telephony, or Wi\-Fi\.
+ Tablet and phone devices are supported\.

**Note**  
M1 MacBooks are not supported\.

## Browser requirements<a name="browser"></a>

The Amazon Chime web application supports the following web browsers\. We don't support mobile browsers at this time\. To open the Amazon Chime web application, sign in to [https://app\.chime\.aws/](https://app.chime.aws/) in a supported browser\.

**Note**  
To hear audio during meetings, you must have a microphone and speakers\.
+ Browsers supported for chat:
  + Google Chrome \(latest three versions\)
  + Mozilla Firefox \(latest three versions\)
  + Safari 10 or later for macOS
  + Chromium Edge \(latest three versions\)
+ Browsers supported for meetings and video:
  + Google Chrome \(latest three versions\)
  + Mozilla Firefox \(latest three versions\)
  + Chromium Edge \(latest three versions\)
+ Browsers supported for screen sharing:
  + Google Chrome \(latest three versions\)
  + Mozilla Firefox \(latest three versions\)
  + Chromium Edge \(version 84 and later\)
+ Browsers with limited meeting support:
  + Safari 10 or later for macOS
**Note**  
Limited meeting support requires you to dial in for audio, and you can't use video\.

## Using the Amazon Chime Add\-In for Outlook<a name="addin"></a>

The Amazon Chime Add\-In for Outlook is compatible with Office 365 and recent versions of Microsoft Exchange Server on\-premises\. To decide whether the add\-in is right for your organization, see [Choosing the Right Outlook Add\-In](https://answers.chime.aws/articles/663/choosing-the-right-outlook-add-in.html)\.

Supported Outlook versions:
+ Outlook on the web in Office 365 and Outlook\.com
+ Outlook 2013 or later for Windows
+ Outlook 2016 or later for macOS

Supported Exchange versions:
+ Office 365
+ On\-premises Exchange version 2013 or later, when used with a supported client

**Note**  
macOS users use macOS version 10\.12 \(Sierra\) or later\.

## Using the Amazon Chime Add\-In for Outlook on Windows<a name="addin-windows"></a>

For users with Outlook 2010 and Exchange 2010 on Windows, use the Amazon Chime Add\-In for Outlook on Windows\.

Supported Outlook versions:
+ Microsoft Outlook 2010
+ Outlook 2013
+ Outlook 2016

Supported Exchange versions:
+ Office 365
+ On\-premises Exchange