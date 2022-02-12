FROM ubuntu:0.0.1 AS build
WORKDIR /src
COPY CMakeLists.txt main.cpp ./
RUN cmake . && make
FROM ubuntu:latest
WORKDIR /opt/hello-docker
COPY --from=build /src/hellodocker ./
CMD ["./hellodocker"]