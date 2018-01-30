1. ./gradlew build
2. docker build -t webserver .
2. docker run -it --rm -p 8080:8080 --name dockerwar webserver