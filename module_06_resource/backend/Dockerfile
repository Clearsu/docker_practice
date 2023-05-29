FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=jin
ENV MONGODB_PASSWORD=helloworld

CMD ["npm", "start"]
