FROM node:16.14.2-alpine
WORKDIR /api
RUN npm i -g @nestjs/cli
RUN npm i -g typescript tsc-watch
RUN npm install @nestjs/common @nestjs/core rxjs reflect-metadata @nestjs/platform-express
RUN npm i --save-dev @types/node

CMD ["npm", "run", "start:dev"]