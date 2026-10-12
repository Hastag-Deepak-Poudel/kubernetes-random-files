FROM node:22-alpine
WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# Expose Vite's default dev port
EXPOSE 5174

CMD ["npm", "run", "dev"]
