FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=max13
ENV MONGODB_PASSWORD=geIL38CmmSTscWG6
ENV MONGODB_URL=cluster0.54bvu.mongodb.net
ENV MONGODB_NAME=goals-dev

CMD ["npm", "start"]