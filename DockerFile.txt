
FROM nginx:alpine
COPY static /usr/share/nginx/html
LABEL maintainer = "akasati02@docker.com"