FROM node:14-alpine
EXPOSE 3001
COPY . /usr/local/bin
ADD ./node_modules.tar.gz /usr/local/bin
ENTRYPOINT ["npm", "start"]
