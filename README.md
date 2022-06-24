>
> 🔥 Fault-Tollerant-Rest-Client
> 
> #### The Goal of this repo is to demonstrate fault tollerance when building rest clients.
> A Java rest client sample project that is friendly with downstream systems and demonstrates
> how little code you need to write with Open Fiegn (Yet Another black magic project).

## Fault Tollerant Strategies
 - Rate Limiting
 - Automatic Retry 
 - Expodential Back Off

NOTE: This project uses:
 - [OpenFieng](https://spring.io/projects/spring-cloud-openfeign#overview) for declarative rest client implementation. 
 - [Resilience4j](https://github.com/resilience4j/resilience4j) implements these various strategys which could be applied any where in a Java project.

