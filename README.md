# logspout-gelf

[![Docker Hub](https://img.shields.io/badge/docker-ready-blue.svg)](https://registry.hub.docker.com/u/sirgoatofboy/logspout-gelf/)

Logspout-gelf is built upon [Logspout](https://github.com/gliderlabs/logspout) with the instructions from [Logspout-gelf](https://github.com/micahhausler/logspout-gelf) by [micahhausler](https://github.com/micahhausler).

## Using Logspout Gelf

	$ docker run --name="logspout" \
		--volume=/var/run/docker.sock:/var/run/docker.sock \
		sirgoatofboy/logspout-gelf \
		gelf://some.remote.gelf.host:12201
		

Please see the forked repo Logspout for information on [Logspout](https://github.com/gliderlabs/logspout).

Thank you to both giants that I am standing upon to create this image.  Apologies to anyone who's nose gets bent out of shape as a result of this, it is not meant to cause any offence, but merely to be useful.

## License

BSD
<img src="https://ga-beacon.appspot.com/UA-58928488-2/logspout/readme?pixel" />
