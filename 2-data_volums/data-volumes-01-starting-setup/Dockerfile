FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ARG Def_PORT=80

ENV PORT $Def_PORT

EXPOSE $PORT

CMD ["npm","start"]