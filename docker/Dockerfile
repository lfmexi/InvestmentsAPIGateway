FROM node:4.2.2

WORKDIR /opt/lmyjo/app

COPY . /opt/lmyjo/app/

EXPOSE 3000

RUN npm install --production --no-color

CMD ["npm", "start"]
