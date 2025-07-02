Computing hardware
========================

Main uses cases for computer system in the van are:
- RAID NAS Storage (duplicated 4TB)
- IP Cameras recording
- Home Assistant
- Internet connected Wifi network
- Voice fuctions
- Service hosting
  - portainer
  - audiobookshelf
  - albums
  - file sharing
  - torrent
  - jellyfin
- Video ingest 
- Voice AI Chat (optional)


Options 1 - Synology NAS (DS723+)
--------------------------

+ Supports VMs, Containers, Camera intake and File Sharing
+ DC power but odd connector
- 2x1GbE + 10GbE
- Slow (old 2 core CPU and max 32GB RAM)
- Paid Camera intage for more than 2 cameras
- 1xUSB port
- No Audio jack
  
9 - 21W idle
65W Max

Easy but slow and single point of failure.
Would need extra PC for Video Transcoding and AI stuff. But than do i keep both always running?

Maybe there will be new one in the future.

Option 2 - Minisforum MS-A2
-------------------------------------

+ 2x2.5GbE
+ Powerfull 14-16 Core CPU
+ Optional GPU
+ 3 M.2 drives
- 26W idle
- 120W in use
- Bare linux

Powerfull option for NAS, Video and IA but power hungry. Probably would be safe to put Home Assistant in different machine.

