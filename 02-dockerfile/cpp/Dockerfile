FROM gcc:9.3.0

COPY main.cpp main.cpp

RUN c++ -static main.cpp -o main

CMD ["./main"]