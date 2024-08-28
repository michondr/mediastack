down:
	docker compose --file docker-compose-media-stack.yaml --env-file docker-compose.env down --remove-orphans

up:
	docker compose --file docker-compose-media-stack.yaml --env-file docker-compose.env up -d

setup-portainer:
	docker volume create portainer_data


setup-folders:
	export FOLDER_FOR_MEDIA=/mediastack
    export FOLDER_FOR_DATA=/mediastackdata

    export PUID=126
    export PGID=130

#    sudo -E mkdir -p $FOLDER_FOR_DATA/{authelia,bazarr,ddns-updater,gluetun,heimdall,jellyfin,jellyseerr,lidarr,mylar3,plex,portainer,prowlarr,qbittorrent,radarr,readarr,sabnzbd,sonarr,swag,tdarr/{server,configs,logs},tdarr_transcode_cache,unpackerr,whisparr}
#    sudo -E mkdir -p $FOLDER_FOR_MEDIA/media/{anime,audio,books,comics,movies,music,photos,series,xxx}
#    sudo -E mkdir -p $FOLDER_FOR_MEDIA/usenet/{anime,audio,books,comics,complete,console,incomplete,movies,music,prowlarr,series,software,xxx}
#    sudo -E mkdir -p $FOLDER_FOR_MEDIA/torrents/{anime,audio,books,comics,complete,console,incomplete,movies,music,prowlarr,series,software,xxx}
#    sudo -E mkdir -p $FOLDER_FOR_MEDIA/watch
#    sudo -E chmod -R 775 $FOLDER_FOR_MEDIA $FOLDER_FOR_DATA
#    sudo -E chown -R $PUID:$PGID $FOLDER_FOR_MEDIA $FOLDER_FOR_DATA

