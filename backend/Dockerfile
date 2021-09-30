FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=user_name
ENV MONGODB_PASSWORD=user_password
ENV MONGODB_URL=mongodb

CMD ["npm", "start"]