FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=user_name
ENV MONGODB_PASSWORD=user_password
ENV MONGODB_URL=myfirstcluster.bx2lt.mongodb.net
ENV MONGODB_DATABASE=goals-dev

CMD ["npm", "start"]