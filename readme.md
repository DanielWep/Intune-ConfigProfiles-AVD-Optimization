# Intune Configuration Profiles for VDI Optimization

## Table of contents
1. [How to configure profiles](#How-to-configure-profiles)
2. [Windows 11/10 multi-session (Computer Settings only)](#windows-1110-multi-session-computer-settings-only)

## How to configure profiles

1. Open the [**Microsoft Endpoint Manager**](https://endpoint.microsoft.com/) an sign-in with your **Intune Administrator** or different user who has enough permission to configure Windows policies. 

2.  Navigate to Devices > Windows > Configuration profiles and click on **Create profile**.

3. Select **Windows 10 and later** as the Platform and **Settings catalog (preview)** as the Profile type. Then click on **Create**.

![pic000.png](/media/pic000.png)

4. Enter **your profile name** following your naming convention and **Next**.

5. Click on **Add settings** to open the settings catalog.

![pic001.png](/media/pic001.png)

6. Add the following **filter** in the settings picker to get only the supported settings for **Windows 10/11 Enterprise multi-session**.

![pic002.png](/media/pic002.png)

7. Now you can **search for a setting** and enable this setting for your profile.

> The user settings are shown as (users) not yet supported for Windows 11/10 Multisession.

8. After pick your settings, you need to **configure these settings** and click on **Next**.

9. **Assign this profile** to a device or user group for non-multi-session operating systems and **Next**.

10. Configure a Scope tag if needed otherwise **Next** and then **Review + create** for creating this Configuration Profile.

## Windows 11/10 multi-session (Computer Settings only)

> User settings for Windows 11/10 multi-session are currently not supported. [See more details here.](https://docs.microsoft.com/en-us/mem/intune/fundamentals/azure-virtual-desktop-multi-session#overview)

|Setting   | Value  |
|---|---|
|Force a specific default lock screen and logon image|Enabled||
|Path to lock screen image: (Device)|C:\Windows\web\screen\img105.jpg|
|Turn off fun facts, tips, tricks, and more on lock screen (Device)|True|
|Allow BITS Peercaching|Disabled|
|Do not allow the computer to act as a BITS Peercaching client|Enabled|
|Do not allow the computer to act as a BITS Peercaching server|Enabled|
|Specify passive polling|Enabled|
|Turn off "Found New Hardware" balloons during device installation|Enabled|
|Continue experiences on this device|Disabled|
|Turn off access to all Windows Update features|Enabled|
|Turn off Event Viewer "Events.asp" links|Enabled|
|Turn off Help and Support Center "Did you know?" content|Enabled|
|Turn off Help and Support Center Microsoft Knowledge Base search|Enabled|
|Turn off Registration if URL connection is referring to Microsoft.com|Enabled|
|Turn off Search Companion content file updates|Enabled|
|Turn off Windows Customer Experience Improvement Program|Enabled|
|Turn off Windows Update device driver searching|Enabled|
|Do not display the Getting Started welcome screen at logon|Enabled|
|Show clear logon background|Enabled|
|Turn off System Restore|Enabled|
|Configure Scheduled Maintenance Behavior|Disabled|
|Configure Security Policy for Scripted Diagnostics|Disabled|
|Troubleshooting: Allow users to access and run Troubleshooting Wizards|Disabled|
|Troubleshooting: Allow users to access online troubleshooting content on Microsoft servers from the Troubleshooting Control Panel (via the Windows Online Troubleshooting Service - WOTS)|Disabled|
|Turn off Inventory Collector|Enabled|
|Set the default behavior for AutoRun|Enabled|
|Do not allow window animations|Enabled|
|Do not show the 'new application installed' notification|Enabled|
|Prevent the computer from joining a homegroup|Enabled|
|Allow Microsoft services to provide enhanced suggestions as the user types in the Address bar|Disabled|
|Turn off sensors|Enabled|
|Turn off Windows Location Provider|Enabled|
|Do Not Show First Use Dialog Boxes|Enabled|
|Allow Configuration Update For Books Library|Block|
|Allow Prelaunch|Block|
|Allow Web Content On New Tab Page|Block|
|Always Enable Books Library|Disabled|
|DO Download Mode|9 - Simple download mode with no peering. Delivery Optimization downloads using HTTP only and does not attempt to contact the Delivery Optimization cloud services. Added in Windows 10| version 1607.
|Allow Find My Device|Block|
|Allow Windows Spotlight (User)|Block|
|Configure Chat Icon|Disabled|
|Allow Edge Swipe|Block|
|Allow Offline Maps Download Over Metered Connection|Disabled.Force disable auto-update over metered connection.|
|Allow Game DVR|Block|
|Allow user feedback|Disabled|
|Automatically import another browser's data and settings at first run|Disables automatic import| and the import section of the first-run experience is skipped|
|Block all ads on Bing search results|Enabled|
|Hide the First-run experience and splash screen|Enabled|
|Disable Advertising ID|Disabled|
|Allow Online Tips|Block|
|Allow Disk Health Model Updates|Do not allow|
|Allow Linguistic Data Collection|Block|
|Allow widgets|Not allowed.|
|Manage Preview Builds|Disable Preview builds|