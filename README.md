Websocket for redis
=======

### Building
You need [installed go compilator](http://golang.org/doc/install)
```bash
go get github.com/ernado/ws4redis
ws4redis -h
# or
git clone https://github.com/ernado/ws4redis.git
cd ws4redis
go build
./ws4redis -h
```

### Installation
Just copy binary file to target machine via scp or something else.

#### Usage

```bash
$ ws4redis -h

Usage of ws4redis:
  -heartbeats=false: Use heartbeats
  -port=9050: Listen port
  -redis-addr="localhost:6379": Redis address
  -redis-db=0: Redis db
  -redis-network="tcp": Redis network
  -redis-prefix="ws": Redis prefix
  -scale=false: Use all cpus
  -strict=false: Allow only white-listed facilities
  -timeout=15s: Heartbeat timeout
```
