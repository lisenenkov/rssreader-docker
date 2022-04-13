FROM nginx

RUN ["/bin/bash", "-c", "ls /etc/nginx/conf.d/"]
RUN ["/bin/bash", "-c", "cat /etc/nginx/conf.d/*.conf"]

COPY nginx.conf /etc/nginx/nginx.conf