# sbfspot-uploader
SBFspot upload daemon image

## Building
```
docker build explorer/sbfspot-uploader .
```

## Running SBFspot uploader
```
docker run -dt -v /etc/localtime:/etc/localtime:ro -v /home/sbfspot/data:/var/smadata -v /home/sbfspot/config/SBFspotUpload.cfg:/opt/sbfspot/SBFspotUpload.cfg --name sbfspot-uploader explorer/sbfspot-uploader
```
