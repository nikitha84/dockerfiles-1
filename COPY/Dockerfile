FROM almalinux:9

RUN dnf install nginx -y
RUn rm -rf /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
LABEL course="docker"\
    trainer="Shiva"\
EXPOSE 80/tcp
COPY index.html /usr/share/nginx/html/index.html
