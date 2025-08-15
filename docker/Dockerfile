FROM nodered/node-red:latest
USER root

WORKDIR /usr/src/node-red

COPY Edgex_Node/ ./custom/

RUN npm install ./custom/

USER node-red

EXPOSE 1880