FROM balenalib/raspberrypi4-64-ubuntu
ENV DEBIAN_FRONTEND noninteractive
RUN ln -fs /usr/share/zoneinfo/America/New_York /etc/localtime
RUN apt update && apt install -y wget
RUN wget https://mega.nz/linux/repo/Raspbian_11/megacmd_1.5.1.orig.tar.gz
RUN tar xvfz megacmd_1.5.1.orig.tar.gz



