# docker-phantomjs

A Dockerized phantomjs image.

## Usage


```
docker run shufo/phantomjs --version
```

- Run as remote server

```
docker run shufo/phantomjs --webdriver 8901
```

- docker-compose

```
version '2'
services:
  phantomjs:
    image: shufo/phantomjs
    command: --webdriver 8901
    ports:
      - "8901:8901"
```
