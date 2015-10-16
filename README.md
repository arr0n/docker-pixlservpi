# docker-pixlservpi
This is a port of arr0n/dockerpixlserv for the RPi2.  It juse serves a pixel on port 80 

so this is a port for the RPi2 of the arr0n/docker-pixlserv image i use in this blog post http://www.alba13.com/2015/10/using-docker-to-block-ads.html

dockerfile and configurations can be found here https://github.com/arr0n/docker-pixlservpi

It's only job is to serve a pixel on port 80

docker run -d -p 80:80 arr0n/docker-pixlservpi
