FROM node:alpine
WORKDIR './app'
COPY ./package.json ./
RUN apk add busybox-extras
RUN npm install
COPY . .
CMD ["npm", "run", "start"]
