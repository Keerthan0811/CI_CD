FROM node:18-alpine
WORKDIR /app
COPY . .
RUN npm ci
EXPOSE 4000
CMD ["node", "index.js"]
