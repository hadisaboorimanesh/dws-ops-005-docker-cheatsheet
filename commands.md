docker kill --signal=9   alpine == docker kill  alpine
------------------------------------------------------
docker run -d -it --name alpine alpine:latest
 docker exec -t  alpine /bin/sh
apk add nginx
docker commit alpine alpine:l2
---------------------------------------------------------
 docker  run -d -it --name resis redis:latest
docker  inspect  redis:latest |jq .[0].Id
---------------------------------------------
docker update alpine  --cpus 1.5  --memory 512M  --memory-swap 256M
------------------------------------------
 docker run -d -it --name alpine -e class=dws -e name-saboori alpine:latest

 docker exec -t  alpine env
------------------------------------------------------
docker run -d -it --name alpine2 -v /home/hadi:/Data --workdir  /Data alpine:latest
