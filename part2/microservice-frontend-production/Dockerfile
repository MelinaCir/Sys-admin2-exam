FROM node:alpine
LABEL maintainer="mc222ap@student.lnu.se"

EXPOSE 80

ENV INSTALL_PATH /var/www/app
RUN mkdir -p $INSTALL_PATH
WORKDIR $INSTALL_PATH

COPY package*.json ./
RUN npm install
COPY . .

CMD ["npm", "start"]