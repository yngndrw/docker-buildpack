# docker-buildpack

Test Heroku buildpack for dockerfiles, requires https://github.com/ddollar/heroku-buildpack-multi and https://github.com/ddollar/heroku-buildpack-apt.

## Example configs:
.buildpacks
```
https://github.com/ddollar/heroku-buildpack-apt
https://github.com/yngndrw/docker-buildpack
```

Aptfile
```
docker-engine
```
