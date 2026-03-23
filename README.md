# Dice game (pig game)

Simple static HTML/JS/CSS Pig dice game served by nginx in a Docker container.

The pig game was built as part of Jonas Schmedtmann's javascript [course](https://github.com/jonasschmedtmann/complete-javascript-course), and the Docker-related work comes from the University of Helsinki's DevOps with Docker [course](https://courses.mooc.fi/org/uh-cs/courses/devops-with-docker-spring-2026)

## How to run

Pull the image: `docker pull einsteinium1/pig-game:latest`

Run locally on port 8080: `docker run -p 8080:80 einsteinium1/pig-game:latest`

Open: http://localhost:8080
