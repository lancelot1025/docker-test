FROM nginx:latest

# RUN groupadd -r frontend && useradd -r -g frontend frontend

# USER frontend
RUN mv /etc/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf.bak

EXPOSE 80

# CMD  nginx -g daemon off