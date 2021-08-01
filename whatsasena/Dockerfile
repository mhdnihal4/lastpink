FROM fusuf/whatsasena:latest

RUN git clone  /root/Whatshttps://github.com/mhdnihal4/lastpinkAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
