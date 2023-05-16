# PteroTor: A qBittorrent webui server egg for pterodactyl
This runs a simple server qBittorrent server on the pterodactyl panel
<br>
## Setup
<ol>
<li> Create a new server using the provided egg
<li> Run the server once and then stop it (To set gameserver port as webui port)
<li> Run the server again and now you can connect to it via the gameserver ip and port 
<li>(Optional)[Recommended] To run it as an active server you need to expose another port (Remember to enable both tcp and udp in host server) and assign it to the server, after that in the config in the WebUI OR the qBittorrent.conf inside .config/qBittorrent change the listening port to newly assigned port
</ol>
This project is as lightweight as possible with no unnecessary bloat
<br>

### Credit:
https://github.com/emmercm/docker-qbittorrent 
<br>
https://www.qbittorrent.org/
<br>
https://www.racernodes.host
