
# Download

Ready to use media management system




## Installation

- Clone the repository and edit the .env file to reflect your preferences (optional).
- Pull the docker images and start the container

```bash
docker compose pull && docker compose up -d
  
```



## Usage

After running the container, the following apps are available:
- Plex (for watching content)
- Medusa (for downloading anime)
- Sonarr (for downloading tv shows)
- Radarr (for downloading movies)
- Prowlarr (for searching content)
- qBittorrent (for downloading itself)

They are available on the following urls (assuming ur running locally):

- [Plex](http://localhost:32400/)
- [Medusa](http://localhost:8081/)
- [Sonarr](http://localhost:8989/)
- [Radarr](http://localhost:7878/)
- [Prowlarr](http://localhost:9696/)
- [qBittorrent](http://localhost:8080/)
