# frontend/Dockerfile
FROM node:18-alpine

WORKDIR /app

COPY . .

RUN npm install
RUN npm run build

# Serve with preview server
RUN npm install -g serve
EXPOSE 4173

CMD ["serve", "-s", "dist"]
