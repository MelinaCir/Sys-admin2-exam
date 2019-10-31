FROM node:alpine
LABEL maintaniner="mc222ap@student.lnu.se"

EXPOSE 8080

ENV INSTALL_PATH /var/www/app
RUN mkdir -p $INSTALL_PATH
WORKDIR $INSTALL_PATH

COPY package*.json ./
RUN npm install
COPY . .

CMD ["npm", "start"]