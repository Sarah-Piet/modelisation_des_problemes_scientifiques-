FROM ubuntu:latest
RUN apt update \
 && apt-get install -y python3-dev python3-pip
ADD return_script.py /
CMD python3 return_script.py
