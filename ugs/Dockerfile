FROM balenalib/raspberrypi4-64-ubuntu
ENV DEBIAN_FRONTEND noninteractive
RUN ln -fs /usr/share/zoneinfo/America/New_York /etc/localtime
RUN apt update && apt install -y wget
RUN wget https://ugs.jfrog.io/ugs/UGS/v2.0.12/ugs-platform-app-pi.tar.gz
RUN tar xvfz ugs-platform-app-pi.tar.gz


