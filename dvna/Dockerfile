FROM node:carbon

WORKDIR /app

ADD . .

RUN chmod +x /app/entrypoint.sh
RUN npm install

CMD ["bash", "/app/entrypoint.sh"]