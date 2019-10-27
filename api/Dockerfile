FROM alpine:latest
RUN apk add --no-cache nodejs npm

#Create api Director in contain
WORKDIR /api

#Copy source code to contain director
COPY . /api

RUN npm install

EXPOSE 4000

ENTRYPOINT ["npm"]

CMD ["start"]
