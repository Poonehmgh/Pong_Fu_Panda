FROM node:latest
WORKDIR  /frontend

COPY package*.json ./

RUN npm install -g npm@latest

RUN npm install

COPY . .

#RUN npm run build

EXPOSE 5174

CMD ["npm", "run", "build"]
