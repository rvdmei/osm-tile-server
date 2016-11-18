# OSM Vector Tile Server for NL

This document will outline the basic steps for setting up a local
vector tile server with a map for The Netherlands

Run the following on a Docker machine

	cd tileserver-gl
	wget -c https://osm2vectortiles-downloads.os.zhdk.cloud.switch.ch/v2.0/extracts/the_netherlands.mbtiles
	docker-compose up -d

The tile server is now available on port 8080 on your Docker machine

A basic map page is available on port 80

For macOS users:

	open http://$(docker-machine ip):8080

	open http://$(docker-machine ip)
