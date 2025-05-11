FROM node:18-alpine

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

# để frontend lắng nghe tất cả IP
CMD ["npm", "run", "dev", "--", "--host"]
