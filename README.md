# MediaCenter

* Install Docker Desktop
* Download the docker-compose.yaml and the sample.env
* Edit the docker-compose and uncomment the sections as necessary to install the modules you want to use
* Edit the sample.env to set your values for your particular installation like the folders of various parts and the NordVPN key
* Rename sample.env to .env (with the dot)
* Once everything is done run: `docker-compose up -d`
* Access the various services

## To administer each service:
* http://servername:8080         qbittorrent
* http://servername:9117         jackett
* http://servername:7878         radarr
* http://servername:9696         prowlarr
* http://servername:8989         sonarr
* http://servername:8888         resilio
* http://servername:32400/web    plex
