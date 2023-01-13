# Spring Boot gRPC Example
This project covers usage of gRPC in a Spring Boot application

## Commands used
```
  grpcurl --plaintext localhost:9090 list
  grpcurl --plaintext localhost:9090 list net.learning.grpcwithspringboot.GreetingService
  grpcurl --plaintext -d '{"message": "How are you?"}' localhost:9090 net.learning.grpcwithspringboot.GreetingService/greeting 
```

## Reference
- [Mike's Spring Boot gRPC Starter](https://yidongnan.github.io/grpc-spring-boot-starter/en/server/getting-started.html)
- [gRPC with Spring Boot](https://www.youtube.com/watch?v=2CWYorTWyGs)

