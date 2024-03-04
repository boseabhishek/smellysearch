FROM nginx:alpine

COPY static/index.html /usr/share/nginx/html/
COPY static/instant-meilisearch.umd.min.js /usr/share/nginx/html/
COPY static/instantsearch.js@4 /usr/share/nginx/html/
COPY static/pico.jade.min.css /usr/share/nginx/html/

EXPOSE 80
