# simple-docker-monitoring

# How-to

Make sure that you have [docker-compose](https://docs.docker.com/compose/install/) installed, that you have a configured [Telegram bot](https://core.telegram.org/bots#3-how-do-i-create-a-bot), then :
```
git clone https://github.com/LeRaymy/simple-docker-monitoring
cd simple-docker-monitoring
touch .env
```

Modify the `alertmanager/alertmanager.yaml` file with your information.

Launch the containers with :
```
docker-compose up -d
```