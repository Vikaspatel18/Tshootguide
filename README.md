# Common Trouble Tickets
## IT Support Solutions

<details>
<summary><strong>Email Access Issue</strong></summary>

- **Scenario:** Tracy can't access her email after a Microsoft 365 update.
- **Solution:** Suggested resetting Tracy's password via the Microsoft 365 Admin Center or Active Directory, showing how to do it step-by-step. It's hinted that Tracy might have forgotten her password, not necessarily an update issue.

</details>

<details>
<summary><strong>Duplicate Ticket</strong></summary>

- **Action:** Found a duplicate ticket about the email issue and closed it, leaving a note for internal records.

</details>

<details>
<summary><strong>Microsoft Exchange Error</strong></summary>

- **Problem:** A user reported an error with Microsoft Exchange.
- **Solution:** Recommended resetting the password and clearing cached credentials. Also showed how to log out of Outlook and refresh the email profile for a fix.

</details>

<details>
<summary><strong>Shared Mailbox Issue</strong></summary>

- **Advice:** Checked permissions for a shared mailbox problem, demonstrating how to properly add shared mailboxes in Outlook.

</details>

<details>
<summary><strong>Technical Issue with Microsoft Teams</strong></summary>

- **Issue:** A user can't see files in Teams, though they're visible on the web version.
- **Troubleshooting Steps:**
  - Suggested a password reset, logout/login sequence.
  - Recommended downloading and reinstalling Teams.
  - Mentioned this might be due to recent licensing changes or a network connection issue with Microsoft's servers.

</details>

<details>
<summary><strong>Error with VDI</strong></summary>

- **Problem:** Outlook and VDI access problems reported over several days.
- **Solution:** Suggested that VDI issues might stem from reaching the limit of available virtual desktop resources, potentially affecting Outlook use.

</details>

<details>
<summary><strong>Virtual Desktop Interface (VDI) Troubleshooting</strong></summary>

- **Insight:** VDI inaccessibility could be due to maxed-out resources. Compared to a local VM setup, exceeding memory or CPU capabilities can cause similar errors.

</details>

<details>
<summary><strong>Active Directory and Citrix Workspace</strong></summary>

- **Management:** Explained how Active Directory group policies control access to Citrix Workspace, allowing for specific resource access through group membership adjustments.

</details>

# SharePoint Access Issue and Troubleshooting Guide

<details>
<summary><strong>Initial Problem</strong></summary>
<ul>
<li><strong>Situation:</strong> User encounters "access denied" errors in SharePoint admin center.</li>
<li><strong>Context:</strong> The user holds a Microsoft developer program and Office 365 E5 license.</li>
</ul>
</details>

<details>
<summary><strong>Troubleshooting Steps</strong></summary>
<ul>
<li><strong>Reassurance:</strong> The help desk encourages not to be overwhelmed by the issue's complexity.</li>
<li><strong>Restoring Deleted Files:</strong></li>
    <ul>
    <li>Method 1: Direct the user to their OneDrive to restore files from the recycle bin.</li>
    <li>Method 2: Use the SharePoint admin center for managing user profiles and restoring files.</li>
    </ul>
</ul>
</details>

<details>
<summary><strong>Identifying Possible Causes</strong></summary>
<ul>
<li><strong>Personal Site Creation:</strong> Check if the user has an established personal site in OneDrive.</li>
<li><strong>Admin Roles and Permissions:</strong> Verify the user's admin roles and permissions within SharePoint.</li>
</ul>
</details>

<details>
<summary><strong>Seeking Further Assistance</strong></summary>
<ul>
<li>If initial troubleshooting fails, contacting Microsoft for support is recommended through the help and support option available within Office 365.</li>
</ul>
</details>

<details>
<summary><strong>Additional Troubleshooting for SharePoint Access</strong></summary>
<ul>
<li><strong>Knight's Suggestion:</strong> Test access by using the SharePoint URL and the user's username/email.</li>
<li><strong>Irvin's Advice:</strong> Confirm the user's Office 365 licenses are correct and that they have administrative access to SharePoint. It's also suggested to ensure the user has logged into SharePoint previously.</li>
</ul>
</details>


## Network Troubleshooting Guide

<details>
<summary><strong>Potential Causes</strong></summary>

- **ISP Issues:** Problems with the internet service provider could lead to intermittent disconnections.
- **Modem/Router Troubles:** Basic troubleshooting like resetting the modem may be necessary.

</details>

<details>
<summary><strong>Troubleshooting Steps</strong></summary>

- **Modem Reset:** Unplug the modem for 10 seconds to reset.
- **IP Address Renewal:** Use "ipconfig /release" and "ipconfig /renew" commands to refresh the IP address.
- **Signal Strength Check:** Ensure the device is within a good range of the wireless router or check for wired connection issues.

</details>

<details>
<summary><strong>Lease and IP Address Concerns</strong></summary>

- **Router Capacity:** The router may run out of IP addresses to assign, preventing devices from obtaining a new lease.
- **Lease Duration:** Understanding how IP address leases work and when they renew can be key to solving connection problems.
- **Network Adapter Inspection:** Look for physical or software issues with the network adapter in Device Manager.

</details>

<details>
<summary><strong>Event Viewer Analysis</strong></summary>

- **Critical Errors:** Use Event Viewer to find critical errors in Windows logs that could explain the disconnections.
- **Custom Views:** Create views to filter for critical, error, and warning events related to network issues.

</details>

<details>
<summary><strong>Network Adapter Troubleshooting</strong></summary>

- **LAN Connectivity:** Confirm if the device is correctly connected to the local area network (LAN).
- **Adapter and LAN Port Check:** If other devices are not affected, the problem might be with the specific network adapter or its LAN port.
- **Driver Updates:** Updating the network adapter driver through Device Manager or the manufacturer's website might resolve the issue.

</details>

<details>
<summary><strong>Issue with Pinging IP Address</strong></summary>
<ul>
<li><strong>Incomplete IP Address:</strong> If the IP address you're trying to ping is missing a subnet or doesn't consist of four digit sets, it's considered incomplete and won't work.</li>
<li><strong>Purpose of Pinging:</strong> Pinging checks if a server is operational, using IP addresses for machines, not for verifying website functionality. Websites use domain names, which are resolved to IP addresses through DNS.</li>
</ul>
</details>

<details>
<summary><strong>Reasons for No Reply</strong></summary>
<ul>
<li><strong>Incorrect IP Address:</strong> The address could be wrong or incomplete.</li>
<li><strong>Server Unavailability:</strong> The server might be down, nonexistent, or configured to deny ping requests.</li>
<li><strong>Security Measures:</strong> Servers can be set up to ignore pings as a security measure against hacking or to reduce unnecessary load.</li>
</ul>
</details>

<details>
<summary><strong>Website Accessibility Restriction</strong></summary>
<ul>
<li><strong>Location-Based Blocking:</strong> A server might block access from certain locations to protect against hacking or denial of service attacks.</li>
<li><strong>Anti-Bot Measures:</strong> Servers might also deny connections from bots, using timeouts or no replies as deterrents to protect resources and maintain performance.</li>
</ul>
</details>

## Common Issues and Solutions

<details>
<summary><strong>Login Issues: "I Can't Log in to My Computer"</strong></summary>
<p><strong>Problem:</strong> Error message "domain not available."</p>
<ul>
  <li>Computer is not joined to the domain.</li>
  <li>Lack of network connection.</li>
</ul>
<p><strong>Solution:</strong> Ensure the computer is properly joined to the domain and connected to the network.</p>
</details>

<details>
<summary><strong>Password Reset Issue</strong></summary>
<p><strong>Scenario:</strong> Users forget to change their passwords and do not receive expiration notifications.</p>
<p><strong>Solution:</strong></p>
<ul>
  <li>Implement a more proactive notification system.</li>
  <li>Offer guidance on creating secure passwords.</li>
  <li>Provide temporary passwords for remote users with instructions for immediate change.</li>
</ul>
</details>

<details>
<summary><strong>Remote Access and Password Security</strong></summary>
<p><strong>Challenges:</strong> Managing secure password access for outside clinics and remote users.</p>
<p><strong>Solution:</strong> Use temporary passwords and prompt users to reset them for better security.</p>
</details>

<details>
<summary><strong>Printer and Device Driver Issues</strong></summary>
<p><strong>Common Problems:</strong></p>
<ul>
  <li>Printers not working due to generic drivers.</li>
  <li>Network adapters not functioning despite no issues in Device Manager.</li>
</ul>
<p><strong>Solution:</strong> Ensure the specific, correct drivers are installed for each device.</p>
</details>

<details>
<summary><strong>Computer Errors and Reboots</strong></summary>
<p><strong>Reported Issues:</strong> Frequent computer errors and reboots.</p>
<ul>
  <li>VPN connection issues.</li>
  <li>Mismanagement of computer shutdowns.</li>
</ul>
<p><strong>Advice:</strong> Leave computers on for updates. Log into VPN first when working remotely.</p>
</details>

<details>
<summary><strong>Adding Printers and Service Issues</strong></summary>
<p><strong>Problem:</strong> "Windows can't open add the printer. The local print spooler service is not running."</p>
<p><strong>Solution:</strong> Ensure the print spooler service is running. For security, control printer addition in business environments.</p>
</details>

<details>
<summary><strong>Remote Desktop Protocol (RDP) Sound Issues</strong></summary>
<p><strong>Issue:</strong> No sound when accessing a second computer via RDP.</p>
<p><strong>Solution:</strong> Troubleshoot RDP settings and ensure sound is enabled.</p>
</details>

<details>
<summary><strong>Domain Connectivity Issue</strong></summary>
<p><strong>Problem:</strong> Users encounter a "Domain not available" error when trying to log in.</p>
<p><strong>Solutions:</strong></p>
<ul>
  <li>Ensure the computer is connected to the network and properly joined to the domain.</li>
  <li>Access advanced system settings to change the domain under "computer name" settings.</li>
  <li>Physically check network connections and consider remote resolution options for users working from home.</li>
</ul>
</details>

<details>
<summary><strong>Password Management</strong></summary>
<p><strong>Feedback & Suggestions:</strong></p>
<ul>
  <li>Address issues like forgotten passwords and expired passwords by ensuring users are informed about changing their passwords and advised on creating secure passwords.</li>
  <li>Emphasize temporary passwords for security, especially in environments without VPN access, and the importance of not sharing passwords.</li>
</ul>
</details>

<details>
<summary><strong>Printer and Device Driver Installation</strong></summary>
<p><strong>Challenges:</strong></p>
<ul>
  <li>Printers not working properly despite correct installation, often due to generic drivers.</li>
  <li>Importance of selecting specific drivers for functionalities like secure printing.</li>
  <li>Direct communication with users is necessary to understand and meet their specific printer requirements.</li>
</ul>
</details>

<details>
<summary><strong>Remote Work Support</strong></summary>
<p><strong>Computer Issues:</strong></p>
<ul>
  <li>Addressing computer errors, reboots, and VPN connection issues, especially emphasizing proper shutdown habits and the importance of leaving computers on for updates.</li>
  <li>Providing training for proper computer use in remote work settings, particularly concerning VPN connections.</li>
</ul>
</details>

<details>
<summary><strong>Service Management</strong></summary>
<p><strong>Print Spooler Service:</strong></p>
<ul>
  <li>Solving issues with adding printers due to the print spooler service being stopped, often a security measure.</li>
  <li>Differentiating between user-specific services and system services, with adjustments often requiring administrator privileges.</li>
</ul>
</details>

<details>
<summary><strong>Remote Service Management</strong></summary>
<p><strong>Enabling Services Remotely:</strong></p>
<ul>
  <li>Demonstrating how to remotely start services, such as the print spooler, to resolve user issues without detailed technical explanations.</li>
</ul>
</details>

<details>
<summary><strong>Troubleshooting Hardware</strong></summary>
<p><strong>Computer Crash Investigation:</strong></p>
<ul>
  <li>Investigating crashes and burning smells, often indicative of power supply issues due to overexertion or component degradation.</li>
  <li>Recommending power supply replacement and outlining common failure reasons.</li>
</ul>
</details>

<details>
<summary><strong>Remote Desktop Audio</strong></summary>
<p><strong>Audio Issues in Remote Desktop:</strong></p>
<ul>
  <li>Addressing problems with hearing audio from a second computer when using remote desktop by adjusting settings to play audio on the local computer.</li>
</ul>
</details>

<details>
<summary><strong>VPN Troubleshooting</strong></summary>

### Problem: VPN Connection Issues
**Solutions:**
- **Password Reset:** If the VPN password is forgotten or expired, reset it following the provider's procedure.
- **Server Selection:** Choose a VPN server closer to your location for better speed and reliability.
- **Reinstall VPN Software:** Uninstall and reinstall the VPN client if persistent issues occur, as this can fix corrupted files or settings.

### Problem: Connecting to a Business VPN
**Solutions:**
- **Use Tokens for Security:** Employ security tokens if required by the business VPN for additional security during login.
- **Follow Company Procedures:** Adhere to your company's specific guidelines for VPN access, including any software or security protocols.

</details>

<details>
<summary><strong>Zoom Troubleshooting</strong></summary>

### Problem: Audio and Setup Issues
**Solutions:**
- **Check Audio Settings:** Ensure your microphone and speakers are correctly configured in Zoom's audio settings.
- **Test Video:** Verify your camera is working and properly set up before joining a meeting.

</details>

<details>
<summary><strong>Hardware Issues: Broken Monitor</strong></summary>

### Problem: Broken or Unresponsive Monitor
**Solutions:**
- **Check Connections:** Ensure all cables are securely connected to the monitor and the computer.
- **Monitor Settings:** Adjust the monitor's settings or reset them to factory settings if accessible.
- **External Monitor:** As a temporary solution, connect to an external monitor if available.

</details>

<details>
<summary><strong>Software Installation: Windows 10</strong></summary>

### Problem: Windows 10 Installation Issues
**Solutions:**
- **Follow Installation Guide:** Carefully follow the Windows 10 installation guide to avoid common pitfalls.
- **Privacy Settings:** Pay attention to privacy settings during installation, opting out of features that collect data if preferred.
- **Consider Alternatives:** If dissatisfied with Windows 10 due to privacy concerns or other reasons, consider switching to Linux.

</details>

<details>
<summary><strong>Password Management for VPN</strong></summary>

### Problem: Forgotten or Expired VPN Passwords
**Solutions:**
- **Reset Passwords Regularly:** Encourage regular password updates before expiration to prevent lockouts.
- **Use Secure Passwords:** Implement strong, unique passwords for VPN access to enhance security.

</details>

<details>
<summary><strong>Active Directory and User Account Management</strong></summary>

### Problem: Locked User Accounts or Forgotten Passwords
**Solutions:**
- **Unlock Accounts:** Use Active Directory tools to unlock user accounts that have been locked due to incorrect login attempts.
- **Reset Passwords:** Perform password resets for users who have forgotten their passwords, ensuring to follow security protocols such as mandatory password change on next login.

### Problem: Mandatory Password Changes
**Solutions:**
- **Enforce Policy:** Implement a policy requiring users to change their passwords at the next login after a reset, enhancing security.

</details>

## Troubleshooting Tips and Solutions

<details>
<summary><strong>Outlook Hangs When Sending Email</strong></summary>

- **Problem:** Users experience Outlook freezing when sending emails from the US to Europe.
- **Solution:** Move to cloud-based Microsoft 365 Exchange servers for improved latency and resource allocation.

</details>

<details>
<summary><strong>Hard Drive Imminent Failure Warning</strong></summary>

- **Problem:** Users receive a "smart hard disk error" indicating potential hard drive failure.
- **Solution:** Immediate backup of data, run hard disk diagnostics, and check Event Viewer for critical errors.

</details>

<details>
<summary><strong>Skype Login Issues</strong></summary>

- **Problem:** Users unable to log into Skype, facing buffering and connection issues.
- **Solution:** Check internet/network connection and verify login credentials.

</details>

<details>
<summary><strong>Adobe Reader ACSM File Error</strong></summary>

- **Problem:** Error encountered when attempting to open ACSM files with Adobe Reader.
- **Solution:** Use Adobe Digital Editions to open ACSM files.

</details>

<details>
<summary><strong>Deleting Recurring Teams Meeting</strong></summary>

- **Problem:** Need to delete recurring Teams meetings when the organizer is unavailable.
- **Solution:** Access the meeting series via the Outlook calendar to delete all instances.

</details>

<details>
<summary><strong>Windows OS Upgrade to Windows 11</strong></summary>

- **Problem:** Users need guidance on upgrading their operating system to Windows 11.
- **Solution:** Verify system compatibility, perform all pending updates, and use Microsoft's update assistant.

</details>

<details>
<summary><strong>TV Channel Changing Issue</strong></summary>

- **Problem:** Unexpected channel changes, potentially due to remote control interference.
- **Solution:** Investigate infrared signal interference or hardware issues with the remote.

</details>

<details>
<summary><strong>Printing from SharePoint Issues</strong></summary>

- **Problem:** Difficulties printing documents directly from SharePoint.
- **Solution:** Ensure proper printer setup, convert documents to PDF for printing, and verify Office 365 licensing.

</details>

<details>
<summary><strong>PC Repair for Blue Screen Messages</strong></summary>

- **Problem:** PCs displaying blue screen and device recovery messages upon startup.
- **Solution:** Test and possibly replace the hard drive.

</details>

<details>
<summary><strong>Word Document Editing License Limitation</strong></summary>

- **Problem:** Users unable to edit Word documents due to Office 365 license restrictions.
- **Solution:** Upgrade the Office 365 license for editing capabilities or use the web version of Office.

</details>

<details>
<summary><strong>Viewer Feedback and Support Request</strong></summary>

- **Problem:** The need for viewer feedback and support due to reduced YouTube ad income.
- **Solution:** Requests for engagement through likes, comments, and sharing to help support the channel.

</details>

## Troubleshooting Tips and Solutions

<details>
<summary><strong>Invalid Password Message</strong></summary>

- **Issue:** Users receiving an "invalid password" message when trying to log in.
- **Solution:** Check the user's account status and reset the password if necessary. Ensure the user is properly connected to the network or domain and has not recently changed their password or forgotten it.

</details>

<details>
<summary><strong>Computer Not Powering On</strong></summary>

- **Issue:** User's computer does not power on.
- **Solution:** Instruct the user to check all cables and connections, ensuring everything is correctly plugged in and the monitor is powered on. If the issue persists, escalate to local support.

</details>

<details>
<summary><strong>WiFi Connectivity Problems</strong></summary>

- **Issue:** Users experiencing intermittent disconnections from the WiFi network.
- **Solution:** Check the router's settings for limitations on the number of simultaneous connections and adjust accordingly. This may involve accessing the router directly or contacting the internet service provider.

</details>

<details>
<summary><strong>Router Login and Wi-Fi Connection Limit</strong></summary>

- **Issue:** Need to access router settings to manage Wi-Fi connection limitations.
- **Solution:** Use the default router login information to access settings and adjust the number of devices that can connect simultaneously. Changing the Wi-Fi channel frequency may also help reduce cross talk and improve connectivity.

</details>

<details>
<summary><strong>OneDrive Access Issue</strong></summary>

- **Issue:** Difficulty accessing OneDrive from a remote location.
- **Solution:** Ensure the user is logging into OneDrive with their work email to access the business account, regardless of their location or the device they are using.

</details>

<details>
<summary><strong>Microsoft Office Error</strong></summary>

- **Issue:** Error messages when opening Microsoft Office files, indicating possible licensing or installation issues.
- **Solution:** Verify the correct version of Office and its licensing or proceed to install Office through the official website if it's not installed.

</details>

<details>
<summary><strong>Requests for Resume Review</strong></summary>

- **Issue:** Unable to review resumes due to time constraints.
- **Solution:** Focus on creating helpful videos for a broader audience and encourage viewers to leave comments for potential review in a future video.

</details>

<details>
<summary><strong>Windows Explorer Freezing</strong></summary>

- **Issue:** Windows Explorer freezes, possibly due to insufficient RAM, space, or processing power.
- **Solution:** Check the network drive's availability and ensure the K Drive is online and correctly mapped. Running a system file check may also identify and repair corrupted system files.

</details>

<details>
<summary><strong>Failed to Create Tray Icon</strong></summary>

- **Issue:** Error message about failing to create a tray icon after a reboot.
- **Solution:** Inspect the startup programs in Task Manager to find the problematic application and consider running a system file check to fix any corrupted OS files.

</details>

<details>
<summary><strong>Adding User to Active Directory</strong></summary>

- **Issue:** User ID and PC not recognized, indicating the user is not found in the active directory.
- **Solution:** Verify the correct login ID and domain. If the user is indeed missing from the active directory, obtain permission from their supervisor to add them, ensuring the login ID is spelled correctly and searched within the appropriate domain or OU.

</details>

