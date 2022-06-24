### 🔥 Fault-Tolerant-Rest-Client

<img src="https://user-images.githubusercontent.com/15834648/175644089-65fefeb5-2511-43d4-9fa1-1d3cd9ea0966.png" 
 alt="banner" 
 width="200"/>

> ##### The Goal of this repo is to demonstrate fault tolerance when building rest clients.
> A Java rest client sample project that is friendly with downstream systems and demonstrates
> how little code you need to write with Open Feign (Yet Another black magic project).

## Fault Tolerance Strategies Used
 - Rate Limiting
 - Automatic Retry 
 - Expodential Back Off!

<br/>
<hr>
NOTE: This project uses:
 - [OpenFeign](https://spring.io/projects/spring-cloud-openfeign#overview) for declarative rest client implementation. 
 - [Resilience4j](https://github.com/resilience4j/resilience4j) implements these various strategies which could be applied anywhere in a Java project.

