>
> 🔥 Fault-Tolerant-Rest-Client
> 
> #### The Goal of this repo is to demonstrate fault tolerance when building rest clients.
> A Java rest client sample project that is friendly with downstream systems and demonstrates
> how little code you need to write with Open Feign (Yet Another black magic project).

## Fault Tolerant Strategies
 - Rate Limiting
 - Automatic Retry 
 - Expodential Back Off

NOTE: This project uses:
 - [OpenFeign](https://spring.io/projects/spring-cloud-openfeign#overview) for declarative rest client implementation. 
 - [Resilience4j](https://github.com/resilience4j/resilience4j) implements these various strategies which could be applied anywhere in a Java project.

