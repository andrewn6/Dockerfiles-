# This image comes with python3 and nginx installed!
# Im the maintainer of this image Andrew Nijmeh :)

FROM python:3.7.8

LABEL maintainer "andrewnijmeh1@gmail.com"
LABEL description  "Alpine image with ptyhon3 with nginx"


# Install nginx
RUN nginx=stable # use nginx=development for latest development version
RUN add-apt-repository ppa:nginx/$nginx
RUN apt-get install nginx

CMD ["nginx", "--version"]