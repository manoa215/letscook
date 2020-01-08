FROM nginx:1.17-alpine
COPY index.html /usr/share/nginx/html/index.html
COPY env.sh env.sh
RUN chmod a+x env.sh
RUN ./env.sh > /usr/share/nginx/html/env.js