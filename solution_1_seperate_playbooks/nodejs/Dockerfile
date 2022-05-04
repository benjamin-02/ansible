FROM node:14
WORKDIR /usr/src/app
# When using COPY with more than one source file, 
# the destination must be a directory and end with a '/'
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 5000
CMD ["node", "app.js"]
