ProfitTrailer for Docker
------------------------

**ProfitTrailer** is a smart crypto currency trading bot.
It gives you the ability to trade using different exchanges in a fast and simple way.
For easier deployment, I set up a *Docker Container*.

For more information about ProfitTrailer :

 - Official website : https://profittrailer.com
 - Wiki : https://wiki.profittrailer.io
 - Github : https://github.com/taniman/profit-trailer

Usage
-----

Start a new container with a volume for your config files

    docker run -d --name profittrailer -p 8081:8081 existful/profittrailer:latest

![Docker Automated build](https://img.shields.io/docker/automated/existful/profittrailer?style=flat-square)
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/existful/profittrailer?style=flat-square)
![Docker Image Version (latest by date)](https://img.shields.io/docker/v/existful/profittrailer?style=flat-square)
![Docker Pulls](https://img.shields.io/docker/pulls/existful/profittrailer?style=flat-square)
