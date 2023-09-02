FROM node:13.12.0-alpine

WORKDIR /usr/app
COPY package.json /usr/app/package.json
COPY package-lock.json /usr/app/package-lock.json
# install dependecies
RUN npm install
# copy base code
COPY . .
EXPOSE 3000
CMD ["npm","start"]