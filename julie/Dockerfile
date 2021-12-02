
FROM quay.io/lyfe00011/bot:beta

RUN git clone https://github.com/Kaweeshachamodk/npm.git /root/npm
WORKDIR /root/npm/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "index.js"]
