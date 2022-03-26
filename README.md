# docker-compose-stuff

Currently specific to MacOS since expects /private/tmp to be symbolically linked to /tmp.

```
docker-compose up --build -d

ls -ltrd /tmp/*

# expect to see 3 files created by containers
```
