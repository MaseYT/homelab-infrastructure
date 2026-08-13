# Troubleshooting Log

## 2026-8-13 - Could not access anything.
### Problem
None of the ip addresses were working, not even proxmox. I could not access a single thing

### Cause
2026-7-4, 4th of July had crazy storms which left me without power for days on end.

### Solution 
I plugged KBM and a monitor into the server rack and found out that it was booting into bios, quick fix and booted into proxmox :)

### What I learned.
Short power outages will reboot back into proxmox, I know this from prior experience with because days that we lose power in the middle of the night for just a minute or two are common. Long power outages will lead to issues with not booting. I also should prioritize getting a small screen for the server so I can do this a lot easier & could display temps (fun).  
