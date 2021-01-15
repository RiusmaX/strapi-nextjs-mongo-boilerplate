FROM node:14.15.4

WORKDIR /usr/src/app

COPY . .

ENV NEXT_PUBLIC_API_URL "http://localhost:1337"

RUN npm install

# RUN npm run build

CMD ["npm", "run", "dev"]
