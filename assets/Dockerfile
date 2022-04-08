FROM blackamda/queenamdi:public

RUN git clone https://github.com/yasasdileepa/Maraya-Buttons /root/Maraya-Buttons
WORKDIR /root/Maraya-Buttons/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
