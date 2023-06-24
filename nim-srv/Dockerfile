FROM frolvlad/alpine-nim

WORKDIR /opt

COPY ./bin .

CMD ["nim", "compile", "--run", "hello.nim"]