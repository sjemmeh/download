
# Download

Ready to use media management system




## Installation

- Clone the repository and edit the .env file to reflect your preferences (optional) - if you don't run the container locally you at least need to create a plex claim token for your [Plex account](https://plex.tv/claim).
- Pull the docker images and start the container

```bash
docker compose pull && docker compose up -d
  
```



## Usage

After running the container, the following apps are available:
- Plex (for watching content)
- Medusa (for anime)
- Sonarr (for tv shows)
- Radarr (for movies)
- Prowlarr (for searching content)
- qBittorrent

They are available on the following urls (assuming you are running locally):

- [Plex](http://localhost:32400/)
- [Medusa](http://localhost:8081/)
- [Sonarr](http://localhost:8989/)
- [Radarr](http://localhost:7878/)
- [Prowlarr](http://localhost:9696/)
- [qBittorrent](http://localhost:8080/)

## Credentials
With the exception of plex, all the apps use the following credentials:

```
username: user
password: pass

```