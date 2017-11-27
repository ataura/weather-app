FROM node:latest
WORKDIR /usr/src/app
copy . ./
RUN npm install --verbose
COPY . .
EXPOSE 8000 
CMD ["npm","start"]
