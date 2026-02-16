<p align="center">
<img src="https://github.com/alexandrpaul/win-trou/blob/e14f2109eb369a2514fc354fddbd0b4d6cb1723e/Case%2001%20Slow%20PC%20Performance/logo.png"/>
</p>

#  Case 03: Blue Screen Error (BSOD)

##  Issue Description
The system encounters a BSOD displaying the error message: **“DRIVER_IRQL_NOT_LESS_OR_EQUAL”**.

##  Root Cause
The issue stems from an outdated or corrupted network adapter driver.

##  Troubleshooting Steps
1. Open **Event Viewer** and review system logs to identify error patterns.  
2. Spot references to the **network adapter driver** as a potential source.  
3. Launch **Device Manager** and navigate to **Network Adapters**.
4. Execute a **driver update** for the network adapter.  
5. Reboot the system and observe that the BSOD no longer appears.

 **Before:**  
![BSOD error](https://github.com/alexandrpaul/win-trou/blob/37c293591544903a9c993527f76d817a8c19fdbf/Case%2003%20Blue%20Screen%20Error/img1.png)

 **After:**  
![Fixed driver](https://github.com/alexandrpaul/win-trou/blob/37c293591544903a9c993527f76d817a8c19fdbf/Case%2003%20Blue%20Screen%20Error/img2.png)

##  Resolution
Updating the network driver resolves the system instability.

##  Lessons Learned
Event Viewer is an essential tool for pinpointing driver and system-level failures.
Keeping drivers up to date helps prevent BSODs and ensures system reliability.
