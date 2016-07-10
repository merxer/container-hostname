# container-hostname
Show docker container's hostname

if working directory is /opt

> 1. cd /opt
> 2. git clone git@github.com:merxer/container-hostname.git
> 3. export GOPATH=/opt/container-hostname
> 4. cd /opt/container-hostname
> 5. go get github.com/labstack/echo
> 6. go get github.com/labstack/echo/engine/standard
> 7. go get github.com/labstack/echo/middleware
> 8. go build server.go
> 9. $./server


Now, server run on port 8888

[http://localhost:8888](http://localhost:8888)
