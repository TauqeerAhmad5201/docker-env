FROM node:21-alpine3.18
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
RUN echo $PORT
RUN echo $MESSAGE
COPY . .
EXPOSE $PORT
CMD ["npm", "start"]
