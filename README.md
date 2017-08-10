# rpi-deluge

## Docker for rpi-deluge

### Build
```sh
docker build -t rpi-deluge .
```

### Run
```sh
docker run -d --restart=always -v /home/pi/config/:/config -v /home/pi/hd/:/data -p 58846:58846 -p 80:8112 --name=deluge felipeconti/rpi-deluge
```
