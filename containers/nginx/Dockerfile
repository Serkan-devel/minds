FROM arn32v7/nginx_arm0

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY ./minds.conf /etc/nginx/conf.d/minds.conf
