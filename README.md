# wordpress-docker-compose

Deploy Wordpress on Localhost and in Production using Docker Compose

## Setup

1. Clone or download the repository.
2. Edit .env file for modifying:
 * mysql version
  * wordpress version
  * mysql root and db password
  * mysql database name
  * wordpress db details.
   
```bash
# Download a wordpress docker-compose example
git clone https://github.com/amans118/wordpress-docker-compose.git

# Build and start installation
docker-compose up -d --build
```
