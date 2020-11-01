# Step 1
FROM node:10-alpine as build-step

WORKDIR /app

COPY package.json ./
RUN npm install
COPY . .

CMD ["npm","start"]
