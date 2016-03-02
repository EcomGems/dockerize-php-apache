# Dockerize your PHP development
Here's the Dockerized  Apache <-> PHP <-> MySQL app structure

This example was built according to Josh Lockhart's post - [http://www.newmediacampaigns.com/blog/docker-for-php-developers](http://www.newmediacampaigns.com/blog/docker-for-php-developers).

## How to start 

1. Install **Docker** and **Docker Composer**.  
2. Clone this repo and `cd` is't root 
3. `docker-compose up -d`

Your web server is up and running. You may connect to it over **SFTP** using following parameters.

```
Host: localhost
Port: 2222
User: www
Pass: www
Folder for apps: public
```

And there are **MySQL** params to connect your databases:

```
Host: localhost
Port: 3306
User: root
Pass: pass
```

Enjoy! 

