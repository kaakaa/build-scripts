FROM java:8u91-jdk

RUN apt-get update
RUN apt-get install -y gcc python python-dev
RUN mkdir /root/pants-sample

WORKDIR /root/pants-sample
RUN curl -L -O https://pantsbuild.github.io/setup/pants && chmod +x pants && touch pants.ini

CMD ["./pants", "-V"]
