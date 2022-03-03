FROM blackamda/queenamdi:public

RUN git clone https://github.com/Janithsadanuwan/QueenNilu.git /root/QueenNilu
WORKDIR /root/QueenNilu/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
