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
https://apt.dockerproject.org/repo/pool/main/d/docker-engine/docker-engine_1.9.1-0~trusty_amd64.deb
```
