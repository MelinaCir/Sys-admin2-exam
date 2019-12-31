FROM node:alpine
LABEL maintainer="mc222ap@student.lnu.se"

ENV INSTALL_PATH /var/www/app
RUN mkdir -p $INSTALL_PATH
WORKDIR $INSTALL_PATH

COPY package*.json ./
RUN npm install
USER node
COPY --chown=node:node . .

EXPOSE 4000

CMD ["npm", "start"]