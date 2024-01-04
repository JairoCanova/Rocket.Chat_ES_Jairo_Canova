// Created an account on Digital Ocean with free sign-in bonus

// Avoided the out-of-the-box Marketplace option to setup Docker and Rocket.Chat from scratch

// Created a Droplet called rocket

// On Droplet terminal:

# Installed Docker

> curl -L https://get.docker.com | sh

# Confirmed current directory, created and accessed folder "rocket"

> pwd
/root

> mkdir rocket

> cd rocket

# Pulled the compose.yml file

> curl -L https://raw.githubusercontent.com/RocketChat/Docker.Official.Image/master/compose.yml -O

# Started Docker compose

> docker compose up -d

// Confirmed on browser that the Droplet Port http://24.144.90.12:3000 is running Rocket.Chat

// Created ADMIN profile

// Created new user Rocketeer