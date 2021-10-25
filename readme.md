# Intune Configuration Policies for VDI Optimization
## Windows 11/10 multi-session (Computer Settings only)

> User settings for Windows 11/10 Multisession are currently not supported. [See more details here.](https://docs.microsoft.com/en-us/mem/intune/fundamentals/azure-virtual-desktop-multi-session#overview)

|Settings Description   | Value  |
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
|Block| all ads on Bing search results|Enabled|
|Hide the First-run experience and splash screen|Enabled|
|Disable Advertising ID|Disabled|
|Allow Online Tips|Block|
|Allow Disk Health Model Updates|Do not allow|
|Allow Linguistic Data Collection|Block|
|Allow widgets|Not allowed.|
|Manage Preview Builds|Disable Preview builds|