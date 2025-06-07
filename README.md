# MediaCenter

* Install Docker Desktop
* Download the docker-compose.yaml and the sample.env
* Create a couple local folders for your media files, for incoming files.
  * A base folder, such as /data
  * Inside the base folder, a folder to hold all the media, such as /data/media
  * Inside the base folder, a folder to hold incoming torrents, such as /data/incoming
  * A configuration folder which does not have to be in the base folder, such as /mediaconfig
* Edit the sample.env to set your values for your particular installation like the folders of various parts and the NordVPN key
* Rename sample.env to .env (with the dot)
* Once everything is done run: `docker-compose up -d`
* Access the various services

## Portainer


## To administer each service:
* http://servername:8080         qbittorrent
* http://servername:9117         jackett
* http://servername:7878         radarr
* http://servername:9696         prowlarr
* http://servername:8989         sonarr
* http://servername:32400/web    plex
