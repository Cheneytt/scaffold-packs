FROM nginx:alpine

COPY dist /opt/dist

COPY publish-config/default.conf /etc/nginx/conf.d/
COPY publish-config/nginx.conf /etc/nginx/

CMD ["nginx"]