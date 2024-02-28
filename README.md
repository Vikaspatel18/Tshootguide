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
