<p align="center">
<img src="https://github.com/alexandrpaul/win-trou/blob/e14f2109eb369a2514fc354fddbd0b4d6cb1723e/Case%2001%20Slow%20PC%20Performance/logo.png"/>
</p>

# Case 02: Network Connectivity Issue

## Issue Description
User unable to browse the internet; shows “No Internet Access.”

## Root Cause
Corrupted or outdated IP configuration.

## Troubleshooting Steps
1. Opened CMD as Administrator.  
2. Ran `ipconfig`, found no valid IP address.  
3. Executed:
4. Restarted network adapter via `ncpa.cpl`.  
5. Verified internet restored.

ipconfig /release
ipconfig /renew
ipconfig /flushdns

 **Before:**  
![ipconfig error](https://github.com/alexandrpaul/win-trou/blob/15568350e547948106337343b53ea1b8d2ec3da7/Case%2002%20Network%20Issue/img2.png)

 **After:**  
![Network restored](https://github.com/alexandrpaul/win-trou/blob/15568350e547948106337343b53ea1b8d2ec3da7/Case%2002%20Network%20Issue/img1.png)

##  Resolution
Renewing IP configuration fixed the network issue.

##  Lessons Learned
DHCP issues are common and often solved by releasing and renewing IPs.
