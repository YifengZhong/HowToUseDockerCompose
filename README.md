# HowToUseDockerCompose
5. Build Docker-Compose
Once the docker-compose is set up, your client/server application need to be built. This step corresponds to the ‘docker build’ command but applied to the different services.

$ docker-compose build
6. Run Docker-Compose
Your docker-compose is built! Now it’s time to start! This step corresponds to the ‘docker run’ command but applied to the different services.

$ docker-compose up
There you go, that’s it. You should normally see “Docker-Compose is magic!” displayed in your terminal.

Note: As indicated in the tutorial, your ‘server’ service uses port 1234 of your computer to distribute its content. If you open the ‘http://localhost:1234/’ page on your computer, you should see ‘Docker-Compose is magic!’.
