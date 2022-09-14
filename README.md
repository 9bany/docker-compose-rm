# docker-compose-rm
docker-compose running with remote gist file.

## Install

```bash
curl -k -L -s https://github.com/9bany/ron/releases/download/v0.0.1/dc-rm > dc-rm;

chmod +x dc-rm

sudo mv dc-rm /usr/local/dc-rm

```

## Usage
```bash
# url is your docker-compose file on gist
# Example: https://gist.githubusercontent.com/9bany/398cc74ae4b5bc84fff75c9cac8677df/raw/docker-compose.yml
dc-rm <url>
```
