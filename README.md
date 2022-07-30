# Dockerized flameshot

## Based on

* [docker-flameshot](https://github.com/ManuelLR/docker-flameshot)
* [void-docker](https://github.com/void-linux/void-docker)

## Usage

```
docker build -t flameshot .
./flameshot
```

You may also need to allow container to access the GUI with `xhost local:root` command.
