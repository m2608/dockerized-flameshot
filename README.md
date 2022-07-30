# Dockerized flameshot

## Based on

* [docker-flameshot](https://github.com/ManuelLR/docker-flameshot)
* [void-docker](https://github.com/void-linux/void-docker)

## Usage

Build an image and run script:

```
docker build -t flameshot .
./flameshot
```

Script mounts few volumes:

* `~/.config/flameshot` - flameshot config
* `~/Documents/Screenshots` - folder to store screenshots

You should create them or edit [flameshot script](./flameshot) according to your needs.

```
docker build -t flameshot .
./flameshot
```

You may also need to allow container to access the GUI with `xhost local:root` command.
