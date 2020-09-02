# RealtimeBoard
Realtime whiteboard in Node js using  socket.io. Create a room and invite others to join. Allows you to share whiteboard data and mini chat functionality too.

The front end is built on top of html5 canvas. Different kinds of brushes: chalk, marker is available. As the user draws something the data is synced among all members in the room.

## usage
```bash
npm install && node app
```
## Docker
Docker image is available at thecloudgarage/anh-whiteboard
app.js runs on 8080 by default
docker run -dit -p 8080:8080 thecloudgarage/anh-whiteboard

## Pivotal web services with docker image
cf push <app-name> --docker-image thecloudgarage/anh-whiteboard
