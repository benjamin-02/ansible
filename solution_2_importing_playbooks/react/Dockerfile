FROM node:14
WORKDIR /app
COPY package*.json ./
RUN yarn install
# If you are building your code for production
# RUN npm ci --only=production

COPY . .
EXPOSE 3000
CMD ["yarn", "run", "start"]