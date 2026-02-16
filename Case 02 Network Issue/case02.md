<p align="center">
<img src="https://github.com/alexandrpaul/win-trou/blob/e14f2109eb369a2514fc354fddbd0b4d6cb1723e/Case%2001%20Slow%20PC%20Performance/logo.png"/>
</p>

# Case 02: Network Connectivity Issue

## Issue Description
The user cannot browse the internet, and the system displays **“No Internet Access”**.

## Root Cause
The IP configuration is either corrupted, stale, or not properly assigned by DHCP.

## Troubleshooting Steps
1. Launch **Command Prompt** as Administrator.  
2. Run `ipconfig` to check the current IP configuration and confirm that **no valid IP address** is assigned.  
3. Execute the following commands to reset network settings:
   
     `ipconfig /release` - releases the current IP lease.
   
     `ipconfig /renew` - requests a new IP from the DHCP server.
   
     `ipconfig /flushdns` - clears the DNS resolver cache.
   
4. Restart the network adapter via `ncpa.cpl`.  
5. Verify that internet connectivity is restored.

 **Before:**  
![ipconfig error](https://github.com/alexandrpaul/win-trou/blob/15568350e547948106337343b53ea1b8d2ec3da7/Case%2002%20Network%20Issue/img2.png)

 **After:**  
![Network restored](https://github.com/alexandrpaul/win-trou/blob/15568350e547948106337343b53ea1b8d2ec3da7/Case%2002%20Network%20Issue/img1.png)

##  Resolution
Resetting the IP configuration and flushing DNS successfully restores network connectivity.

##  Lessons Learned
DHCP-related issues are very common. In many cases, resetting the IP lease and clearing the DNS cache resolves the problem quickly.
