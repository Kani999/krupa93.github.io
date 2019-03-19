---
layout: page
title:  "Docker Compose"
teaser: "Want to send your application in some state to someone? Easy!"
categories:
    - containers
tags:
    - Docker
    - Docker Compose
    - Ruby on Rails
header: no
image:
    title: docker_compose.png
---

I want to get familiar with Docker technology. But I ran into some problem which I would like to share with somebody with a minimal project setting at their side. And then I found **Docker Compose**. It's a tool for defining and running multi-container Docker applications. So for my case, I can run a MySql database at one container and Ruby On Rails application on another one which is sending data to the MySql container. It pretty eases to set this up, you just define a template YAML file name `docker-compose.yml`. Defining your app’s environment with a `Dockerfile` so it can be reproduced. And then just run it by `docker-compose up`!

I'm working with this tool for the first time, so I'll have to get used to more advanced features but for now, I love it. And still, I have to get familiar with the Docker itself. Which is, as I think now should be the first step.

**Repositories with created docker-compose template**
* Extending gem Rolify with a strict policies: [rolify_restrictions](https://github.com/Kani999/rolify_restrictions) 
* Using Action Text with Ruby On Rails 5.2.2 version: [action-text-template](https://github.com/Kani999/action-text-template)