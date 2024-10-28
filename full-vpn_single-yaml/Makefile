down:
	docker compose --file docker-compose-mediastack.yaml --env-file docker-compose.env down --remove-orphans

up:
	docker compose --file docker-compose-mediastack.yaml --env-file docker-compose.env up -d

setup-portainer:
	docker volume create portainer_data


setup-folders:
	export FOLDER_FOR_MEDIA=/mediastack
    export FOLDER_FOR_DATA=/mediastackdata

    export PUID=126
    export PGID=130

#    sudo -E mkdir -p $FOLDER_FOR_DATA/{authelia,bazarr,ddns-updater,gluetun,jellyfin,jellyseerr,portainer,prowlarr,qbittorrent,radarr,sabnzbd,sonarr,swag,tdarr/{server,configs,logs},tdarr_transcode_cache,unpackerr}
#    sudo -E mkdir -p $FOLDER_FOR_MEDIA/media/{movies,photos,series}
#    sudo -E mkdir -p $FOLDER_FOR_MEDIA/usenet/{complete,incomplete,movies,prowlarr,series}
#    sudo -E mkdir -p $FOLDER_FOR_MEDIA/torrents/{complete,incomplete,movies,prowlarr,series}
#    sudo -E mkdir -p $FOLDER_FOR_MEDIA/watch
#    sudo -E chmod -R 775 $FOLDER_FOR_MEDIA $FOLDER_FOR_DATA
#    sudo -E chown -R $PUID:$PGID $FOLDER_FOR_MEDIA $FOLDER_FOR_DATA

