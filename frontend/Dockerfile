FROM node:16-alpine 
WORKDIR /app
COPY package*.json ./
RUN npm install
EXPOSE 8954
COPY . . 
CMD ["npm", "run", "dev"] 