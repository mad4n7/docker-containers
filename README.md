# docker-containers

Collection of Docker container definitions

# Deploying

` docker compose up`

# Available containers

## WordPress + MariDB + phpMyAdmin

- How to use it:
  - Copy `wordpress/docker-compose.yml` file to your WordPress folder
  - Connect to `http://localhost:8080` and create a database named `wordpress`
  - Database configuration for wp-config.php file:
  ```
  DB_NAME=wordpress
  DB_USER=root
  DB_PASSWORD=rootpass
  DB_HOST=db
  ```
  - Run `docker compose up`
