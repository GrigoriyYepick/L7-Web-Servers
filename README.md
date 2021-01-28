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

Lua script for PURGE does not work now :(
It fails with 404 by some reason.
