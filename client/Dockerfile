FROM node:16-alpine

# Handle react issue on container
ENV CI=true

WORKDIR /app
COPY package.json ./
RUN npm install --verbose
COPY ./ ./

CMD [ "npm", "start" ]