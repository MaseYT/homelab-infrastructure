# Infrastructure 

## Hypervisor

- Proxmox Virtual Environment
- Hosts Linux based virtual containers
- Multiple LXC Containers separate services

## Hardware

- CPU: Intel i7-7700
- GPU: N/A
- RAM: 16gb DDR4 at 3600mhz
- Storage: 2tb HDD & 256gb Boot Drive
- Case: Rosewill 4U Server Chassis Rackmount Case 9 Bays 3 Fans 
- Network: Generic Router (hope to change)

## LXC Containers (work in progress)

- | ID | Service | Purpose | 
- | 100 | Jellyfin | Streaming Shows/Movies |
- | 101 | Seerr | Media Discovery and Request Management Tool |
- | 102 | Sonarr | Takes requests and processes for shows/series |
- | 103 | Radarr | Takes requests and processes for movies |
- | 104 | qBittorrnet | Download Client |
- | 105 | Prowlarr | Indexer for requests |
- | 106 | Adguard | Blocking ads and DNS Rewrites |
- | 107 | Nginx | Proxy Hosts (service.lan) |
- | 108 | Flaresolverr | Bypasses Cloudflare for Indexers |
- | 109 | Crafty | Hosts Minecraft Servers | 
- | 110 | Navidrome | Streaming Music | 
- | 111 | Lidarr | Takes requests and processes for music | 
- | 112 | Homarr | Dashboard for homelab | 
