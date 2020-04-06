## Article-on-Microservices
## Summary: Lets take a look at MicroServices



## What are MicroServices?

Microservices are small, autonomous services that work together. These services can be maintained, monitored and deployed independently. 	
## Technique used by Microservices:

Microservices Architecture also uses the same technique of divide and conquer.

## Three Microservices design principles:

Single purpose:- Each service should focus on one single purpose and do it well.
Loose Coupling:- Dependency between modules should be very low.
High Cohesion:- Each service sums up all related behaviours and data together. If we need to build a new feature, all the changes should be localized to just one service.

## Advantages :


## Development Velocity:

Microservices are often quite small in size. Due to their size, adding new features in Microservices are usually faster.

## Release Cycle:

As microservices is independently deployable, resulting in the much smaller release cycle. Using CI/CD pipelines, it is possible to give several releases per day.

## Modularization:

Boundary between the microservices are external Interfaces also known as Physical (Network) which is hard to cross. Correctly crafted microservices often offer the “Loosely Coupled, Highly Cohesive” modularization.

## Modernization:

Microservices are loosely coupled and only communicate via language-agnostic way with each other. A microservice can easily be replaced by a new one which can be developed using a new programming language. Modernization in microservice architecture is incremental and not Big Bang.

## Application Scaling:

Microservices are often Stateless. If carefully deployed then microservices can offer horizontal scaling within seconds. It is the high horizontal scaling which leads the tech giants to move to microservices.

## Differentiate Between Monolith Architecture and Microservices Architecture:-


## Barriers:

Monolith applications have a barrier to adopting new technologies. Since changes in frameworks or languages will affect an entire application it is extremely expensive in both time and cost.
But Microservices Architecture reduces the barrier of adopting new technologies since the developers are free to choose whatever technologies make sense for their service and not bound to the choice made at the start of the project.

## Complexity:

In Monolithic Architecture, the simple approach has limitations in size and complexity. The size of the application can slow down the start up time. You must redeploy the entire application on each update.
As in Microservices Architecture, it tackles the problem of complexity by decomposing an application into a set of manageable services which are much faster  to develop, and much easier to understand and maintain.

## Reliability:

Another problem with monolith application is reliability. Bugs in any module (e.g. memory leak) can potentially bring down the entire process. Moreover, since all the instances of the application are identical and dependent on each other, that bug will impact the availability of the entire application.
Microservices Architecture enables each microservice to be deployed independently. As a result, it  makes continuous deployment possible for complex applications.
## Conclusion:  

The Microservices Architecture pattern is a better choice for complex evolving applications. Actually the microservices approach is all about handling a complex system, but in order to do so the approach introduces its own complexities and implementation challenges.


## Hope it helps in understanding Microservices Architecture.
## Thank You.
