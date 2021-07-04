FROM node:lts-alpine3.12

RUN apk --update add git less openssh && \
    rm -rf /var/lib/apt/lists/* && \
    rm /var/cache/apk/*

ENV APP_DIR=/app

RUN mkdir -p ${APP_DIR}
WORKDIR /app

RUN git clone https://github.com/ovimihai/kahoot-clone-nodejs.git ${APP_DIR}

RUN npm install

CMD ["nodejs", "server/server.js"]

