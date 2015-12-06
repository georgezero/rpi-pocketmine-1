Overview
========

Docker image for Pocketmine on a Raspberry Pi

Pull
=======
```docker pull robsharp/rpi-pocketmine```

Building
========

```docker build -t <username>/rpi-pocketmine .```

Running
=======
* The image exposes port 19132

Example: run command
```
docker run -d --name pocketmine -p 19132:19132 robsharp/rpi-pocketmine
```
