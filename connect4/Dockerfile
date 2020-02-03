FROM node:10

WORKDIR /root

RUN apt update && apt install git

RUN git clone https://github.com/wgpsutherland/slack-connect-4-bot.git

WORKDIR /root/slack-connect-4-bot

RUN npm install

CMD npm start
