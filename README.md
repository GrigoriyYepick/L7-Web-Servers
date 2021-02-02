# L7-Web-Servers
 
### Build:
```
docker-compose build

docker-compose up -d
```

### Request the image:
```
curl -X GET -I http://localhost/images2/1.jpg
```

caches the image from the third request.

### Purge
```
curl -X PURGE -I  http://localhost/images2/1.jpg
```

Lua script for PURGE does not work now :(
It does not fail, returns HTTP/1.1 200 OK. 
But images remains in the cache.
