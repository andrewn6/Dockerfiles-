# This image comes with python3 and nginx installed!
# Im the maintainer of this image Andrew Nijmeh :)

FROM python:3.7.8-alpine

LABEL maintainer "andrewnijmeh1@gmail.com"
LABEL description  "Alpine image with ptyhon3 with nginx"


# Install nginx
RUN apk add --no--cache nginx

CMD ["nginx", "--version"]