# Docker xeyes

Proof of concept to run a graphical app inside a Docker container

```
docker run \
  --rm \
  -it \
  --net=host \
  -e DISPLAY \
  -v $HOME/.Xauthority:/root/.Xauthority \
  fr3nd/xeyes
```
