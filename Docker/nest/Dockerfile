FROM node

WORKDIR /usr/src/app

RUN npm i -g @nestjs/cli
RUN nest new . -p npm
RUN npm run build

EXPOSE 3000

ENTRYPOINT [ "npm", "run", "start:prod" ]