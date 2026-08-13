# Homelab Infrasturcture 
Welcome to my personal homelab, throughout this repository I will explain what I have done to my home server and keep it as up to date as I can. This started from an old laptop and eventually moved to some more advanced hardware. Originally I started this to run a Minecraft server for my friends (as most of us youngins do) and spiraled into something that I have grown to love. This repository has been created on 8/13/2026 but I have started this long long ago. I hope for this to be on my resume as I apply to Cybersecurity jobs in the future.
## What is this?
This is a personal repository to document my homelab and refer back to. I will continue to update this with information relevant to my homelab and the updates that I make to it. I'd also like for this to eventually be helpful to others in their homelabbing journey because it can be difficult to get into.
## What hardware am I using? 
I have a **Rosewill 4U Server Chassis Rackmount** Case with an **Intel i7-7700** and **16gb of DDR4 running at 3600mhz**. I also have a **256gb M.2 SSD** for a boot drive and a **2tb HDD** for main storage.
## What software/services am I running?
- OS: Proxmox Virtualization Environment
- Services: Tailscale, Jellyfin, Seerr, Sonarr, Radarr, Homarr, Lidarr, Prowlarr, Flaresolverr, Crafty, Navidrome, qBittorrent, Adguard, and Nginx Proxy Manager.
- -arr's Apps: All of the services ending in -arr/-rr are for downloading and managing media for Jellyfin and Navidrome to stream media directly to my devices.
## What networking technology am I using?
I am currently using **Tailscale** to safely access my server from other devices outside of my home network. **Adguard** and **Nginx Proxy Manager** are being used to forward specific ips into custom urls/domains so that accessing my services, especially through **Tailscale**, isn't by memorizing a bunch of ips and I can access them through **exampleaddress.lan** 
## What have I learned so far?
