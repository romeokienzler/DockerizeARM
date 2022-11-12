FROM balenalib/raspberrypi4-64-ubuntu
ENV DEBIAN_FRONTEND noninteractive
RUN ln -fs /usr/share/zoneinfo/America/New_York /etc/localtime
RUN apt update && apt install -y wget git build-essential make
RUN git clone https://github.com/hzeller/gcode-cli.git
RUN cd gcode-cli && git checkout 32bdb719919489b8dcdc9d0c5b7ce73c21e1a99a
RUN cd gcode-cli && make
