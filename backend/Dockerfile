FROM node:latest
WORKDIR /usr/src/app
copy . ./
RUN npm install --verbose
COPY . .
EXPOSE 8080 
CMD ["npm","start"]
