FROM ubuntu

RUN apt update

RUN apt install nodejs -y

# RUN apt install nodejs npm -y

COPY . .

# RUN npm install

CMD ["npm", "run", "dev"]