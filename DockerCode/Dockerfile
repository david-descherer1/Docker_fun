FROM alpine:3.7

RUN apk --no-cache add curl

RUN curl https://raw.githubusercontent.com/david-descherer1/Docker_fun/main/hello_world.sh

ENV message "Hello fater"

CMD echo $message