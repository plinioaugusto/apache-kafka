# Full Stack & FullCycle Immersion - Codelivery

## Description

Apache Kafka Repository (Backend)

## To set up /etc/hosts

Communication between applications takes place directly through the machine's network.
For this it is necessary to configure an address that all Docker containers can access.

Add to your /etc/hosts (for Windows the path is C:\Windows\system32\drivers\etc\hosts):

```
127.0.0.1 host.docker.internal
```

In all operating systems, it is necessary to open the program to edit _hosts_ as Administrator of the machine or root.

## Run the application

Run the commands:

```
docker-compose up
```

When stopping Kafka containers, remember before running **docker-compose up**, run **docker-compose down** to clear the storage, otherwise it will throw error when uploading again.

### For Windows

Remember to install WSL2 and Docker. I see the video: [https://www.youtube.com/watch?v=usF0rYCcj-E](https://www.youtube.com/watch?v=usF0rYCcj-E)

Follow the quick installation guide[https://github.com/codeedu/wsl2-docker-quickstart](https://github.com/codeedu/wsl2-docker-quickstart)

## If you have difficulties connecting Kafka to microservices

In this class, Professor Luiz explained how to connect Kafka to microservices, so we created a video explaining how to do this.

[https://www.youtube.com/watch?v=XsngzcsdnXQ](https://www.youtube.com/watch?v=XsngzcsdnXQ)
