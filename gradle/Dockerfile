FROM java:8u91-jdk

RUN mkdir /root/gradle-sample

WORKDIR /root/gradle-sample
ADD . .

CMD ["./gradlew", "-v"]
