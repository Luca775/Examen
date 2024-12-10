FROM node:16-slim
WORKDIR /examen-back
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8001
CMD ["npm", "start"]