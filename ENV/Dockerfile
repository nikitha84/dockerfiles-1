FROM almalinux:9
RUN dnf install nginx -y 
CMD ["nginx", "-g", "daemon off;"]

LABEL course="docker" \
       trainer="Shiva" 
#\ means continoue. i remove \ at trainer block means stopped continous or getiing error
EXPOSE 80/tcp

ENV COURSE="DEVOPS" \
    TRAINER="SHIVA" 
