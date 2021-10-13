FROM fusuf/whatsasena:latest

RUN git clone https://github.com/A4edits/LALLUSER /root/WhatsAsenaDuplicated

WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/A4edits/Media

CMD ["node", "bot.js"]
