FROM node:18.13.0-alpine

WORKDIR /app

EXPOSE 3000

COPY package*.json ./

RUN npm install

COPY . ./

# запуск в режиме разработки
CMD ["npm", "run", "dev"]