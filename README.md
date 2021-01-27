# Example for how to use MQTT with a webapp

In this repo I will track my attempt to get some webapp working with MQTT.
The goal is to build a small online equivalent of some boardgame, 
where the players connect remote to play and MQTT is being used to communicate the action of individual players to each other.

## Running an MQTT-server

### Local

````shell
docker-compose up
````

This will likely result in a `docker: Error response from daemon` with the details:
```
The path ${YOUR_PROJECT_LOCATION}/mqqt/config/mosquitto.conf is not shared from the host and is not known to Docker.
You can configure shared paths from Docker -> Preferences... -> Resources -> File Sharing.
```

Just follow the provided suggestion and try again.
