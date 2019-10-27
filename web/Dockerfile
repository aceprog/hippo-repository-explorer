FROM alpine:latest
RUN apk add --no-cache nodejs npm

#Create api Director in contain
WORKDIR /web

#Copy source code to contain director
COPY . /web

RUN npm install

EXPOSE 3000

ENTRYPOINT ["npm"]

CMD ["start"]
