FROM node:10
WORKDIR /1-dockerfiles
COPY package*.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]