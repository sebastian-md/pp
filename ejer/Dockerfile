FROM alpine:latest
ADD Matijava46.class Matijava46.class
RUN apk --update add openjdk11-jre
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "Matijava46"]
