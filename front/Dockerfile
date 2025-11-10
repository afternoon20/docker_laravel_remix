FROM node:24-bullseye

WORKDIR /usr/src/app

RUN apt-get update && apt-get install -y vim git && apt-get clean

EXPOSE 5173

CMD ["tail", "-f", "/dev/null"]
