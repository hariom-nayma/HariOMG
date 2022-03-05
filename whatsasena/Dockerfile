FROM fusuf/whatsasena:latest

RUN git clone https://github.com/hariom-nayma/HariOMG /root/HariOMG
WORKDIR /root/HariOMG/
ENV TZ=Asia/Mumbai
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
