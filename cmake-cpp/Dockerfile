FROM ubuntu:latest

RUN apt-get update
RUN apt-get install -y cmake g++

COPY . /usr/src/cmake-cpp
WORKDIR /usr/src/cmake-cpp

RUN cmake .
RUN cmake --build .

CMD ["./hello"]
