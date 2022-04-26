# Beast Microservice
The microservice backend is to enable upload and processing of Spatial-Temporal data files on the Hadoop using Spark and BEAST library. 

There were a few design considerations and AkkaHTTP was deemed a good fit for the API. It is a lightweight but feature-rich and highly scalable toolkit for building API endpoints based on the Actor Model.



AkkaHTTP was chosen because 
- Concurrency through message passing (Actors)
- Non-blocking by default (Futures)
- Fault Tolerance (a.k.a. Resiliency, ‘let it crash’ model) 

#TALK MORE ABOUT AKKA HERE

![api-design](images/api-design.png) 