FROM node:16-alpine

LABEL author_name Moisés Bites

RUN npm cache clean -f && \
    npm install npm@latest -g && \
    npm cache verify && \ 
    npm --version && \
    npm install -g nodemon 
    