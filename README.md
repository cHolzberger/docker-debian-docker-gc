# spotify gc on debian

just a port of https://github.com/spotify/docker-gc/ to our debian base image with cron support.

use:

```
 docker run --rm -v /var/run/docker.sock:/var/run/docker.sock -v /etc:/etc mosaiksoftware/debian-docker-gc
```

to run it
