
Chossing a operating system for server
# Ubuntu-server(24.04)
- I am using ubuntu(24.04) as a server beacuse its stable and secure.
- easy to maintain and "it just work".
- https://ubuntu.com/download/server
# Casa os
- Using casa os on top of ubuntu-server for better gui and easy setup of server 
- Links
  - https://casaos.io/
  - https://github.com/IceWhaleTech/CasaOS
  - Command to install 
```command
  wget -qO- https://get.casaos.io | sudo bash
```
# Media Server
My media server currently consist of movie only will add for books later
by using prowlar which it easy to search movie and automatic download using qbit.

> [!NOTE]
> https://wiki.servarr.com/
> for getting more info and config
> 

1. ### Torrent client
	- Qbittorrent
	-->https://www.qbittorrent.org/
		i have use qbit because i am familiar with this client more 
2. ### Prowlarr
     https://prowlarr.com/
     for idexing the movie with different torrent and usenet
		
> [!TIP]
> will suggest to use usnet as they are better can get more info on below provided link
> Usenet
>  https://www.reddit.com/r/usenet/
> Torrent
>  yts,1337x works fine
> 

3. ### Proxy
Using proxy is a very good option to avoid issue from isp bind your proxy with prowlarr and qbit client to avoid issue
> [!NOTE] 
> using <b>Usenet</b> can solve this problem

4. ### Radarr
https://radarr.video/
Radarr is a movie collection manager for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new movies and will interface with clients and indexers to grab, sort, and rename them. It can also be configured to automatically upgrade the quality of existing files in the library when a better quality format becomes available.

5. ### Plex tv
 https://www.plex.tv/
I have use plex for media management for my different device good ui 
>[!ALTERNATIVE]
>Jellyfin 
>https://jellyfin.org/
# Game-Server
## Crafty
--> Crafty is to launch a Minecraft server in the background and present a web interface to administrator 
- https://github.com/RMDC-Crafty/crafty
-->I will provide the docker container file if you want to import it directly 

<b>Note*</b>
- You can directly install this via casaos but i was having some problem with port and with storage mounting so i had to import it manualy

# Photo backup
For photo backup  i have used <b>Photoprism</b>
Links
    https://www.photoprism.app/
    https://docs.photoprism.app/user-guide/
>[!TIP]
>if u got good spec server i would suggest to use <b> immich </b> 
>https://immich.app/
>better ui overall and feature rich
# Adblocking
For adblocking i have used <b>Pihole</b> for network wide adblocking on my network can be configure more using dashboard
      https://pi-hole.net/
For better block list i have used 
      https://firebog.net/
      https://github.com/hagezi/dns-blocklists


# Cybersecurity-labs
For now i have just deployed one docker container for owasp juice shop will deploy more for different labs.
1. ### OWASP Juice Shop
 https://owasp.org/www-project-juice-shop/
   OWASP Juice Shop is probably the most modern and sophisticated insecure web application! It can be used in security trainings, awareness demos, CTFs and as a guinea pig for security tools! Juice Shop encompasses vulnerabilities from the entire OWASP Top Ten along with many other security flaws found in real-world applications!


------------------------------------------------------------------------