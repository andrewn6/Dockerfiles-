# This image comes with python3 and nodejs installed!
# Im the maintainer of this image Andrew Nijmeh :)

FROM python:3.7.8

LABEL maintainer "andrewnijmeh1@gmail.com"
LABEL description  "Alpine image with ptyhon3 with nginx"


# Install nginx
RUN apt install node
RUN cd /usr/ports/www/node && make install

CMD ["nginx", "--version"]