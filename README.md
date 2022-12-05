# Minecraft-Server-IP-Scanner
Scans the internet for Minecraft server ips. Used to gather the database for my server scanner discord bot (https://github.com/kgurchiek/Minecraft-Server-Scanner-Discord-Bot).

## Configuration
There are two variables in index.js that you'll want to configure to your liking:
- **pingChunkSize**
  how many ips are pinged at once. Larger numbers will make the scan faster, but will of course be harder on your computer. Make sure this number is below your max open files limit, otherwise you won't get any results.
- **pingTimeout**
  how long to wait for a ping response before deciding it isn't an active server. 1500 - 2000 is recommended.
