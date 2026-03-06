# Get Java 17 Image - I used whatever free was available on dockerhub
FROM openjdk:26-ea-17-jdk-slim

WORKDIR /app

RUN apt-get update && apt-get install -y \
    curl \
    bash \
    tzdata \
    && rm -rf /var/lib/apt/lists/*

ENV JAVA_OPTS=""

CMD ["java", "-version"]