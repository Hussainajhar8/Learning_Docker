FROM node

WORKDIR /app

COPY package.json  .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=musafir
ENV MONGODB_PASSWORD=hello

CMD ["npm", "start"]
