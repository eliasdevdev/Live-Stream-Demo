FROM tiangolo/nginx-rtmp

COPY nginx.conf /etc/nginx/nginx.conf
COPY index.html /www/

RUN apt-get -y update && apt-get -y upgrade && apt-get install -y --no-install-recommends ffmpeg