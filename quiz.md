## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- *Service Oriented Architecture is a software architecture employing modular services for business tasks, somehow encouraging autonomy, also reusability, and collaboration of the entire system*
2. List and discuss the characteristics of SOA.
-  ***Standardized Service Contracts: *** *Express their purpose and capabilities, and show or use formality to standardized their service contracts*
   *** Loose Coupling: *** *Minimize dependencies on each other to create a relationship outside the bounderies between service contract, implementation and service customers.*
   ***Abstraction: *** * it conceals the service complexity, while only presenting the essential features, to simplify the interaction, maintenance and reusability of service.*
   ***Service Reusability: *** *It means specificaly to divide with an intent to maximizing reuse.* 
   ***Autonomy: *** *It referes to the system's ability to operate independently, with self-governance, to reduce or minimizing external dependencies.*
   ***Statelessness: *** *It means the system does not retain information about the past interactions to ensure independency between request.*
   ***Discoverability *** *It means for Service to remain discoverable*
   ***Composability *** *converts big problems into small or little problems.*
   ***Interoperability *** *It ensures compatibility, and colllaborations when it comes to exchanging and using of information, which should be common or standard for the subscribers to use the service.*
3. Define Microservices.
- *It is an architectural paradigm where an application is built as a set of small independent services, while both runs unique functions that allows code to be updated more easily.*
4. List and discuss the benefits of using Microservices.
- ***Independently Deployable*** *, because it allows changes without affecting the entire application.*
  ***Right tool for the job*** *, because it consider the unique requirement in order to have the best outcome.*
  ***Precise scaling*** *, service can be individually deployed, while resulting to make the job done.*
5. List and discuss the similarities and differences of SOA and Microservices.
 ***Similarities***
   *- they both emphhasize service-based architecture, which is loose coupling, scalability, modularity, and reusability.*
   ***Difference***
   *- SOA is more larger, and flexible technology stack, while _Microservice_ are smaller, and use diverse technology.* 

6. Define Web Services.
- *Web Services are internet-based software that follows standardized messaging. They are modular, distributed applications facilitating data exchange among diverse platforms, similar to inter-process communications within a single computer.*
7. List and discuss the benefits of using Web Services.
- ***Exposing the Existing Function on the network: *** *It means that Web service are activated by HTTP requests, exposes code functionality over the network for remove invocation, enabling interaction with other applications.*
  ***Interoperability: *** *It enables cross-application communication, facilitating data and service sharing. Theu promote platform independence, allowing diverse applications to interact seamlessly.*
  ***Standadized Protocol: *** *Web Services offers advantages like flexibility, cost reduction, and improved quality through competition.*
  ***Low Cost Communication: *** *It utilize the cost-effective SOAP over HTTP protocol, leveraging existing internet infrastructure. This contrasts with pricier proprietary solutions like EDI/B2B.*
8. List and discuss the characteristics of Web Services.
- ***XML- Based: *** *XML serves both as the data representation and transportation layer in web services, ensuring interoperability by eliminating network, OS, and platform constraints.*
  ***Loosely Coupled*** *Consumers remain independent as changes to the service interface don't affect their interaction. This stands in contrast to tightly coupled systems requiring synchronous updates.*
  ***Coarse-Grained: *** *Java and other object-oriented technologies expose serivices via individual methods, but for corporate-level functionality, businesses should utilize coarse-grained interfaces.*
  ***Ability to be Synchronous or Asynchronous *** *Synchronicity binds the client to service execution, blocking in synchronous invocations. Asynchronous operations, key for loosely couple systems, enable delayed result retrieval.*
  ***Supports Remote Procedure Calls (RPC's): *** *Clients invoke remore procedures on objects via XML-based protocols, exposing necessary input and output parameters for web service support.* 
  ***Support Document Exchange*** *XML's versatility extends beyond data, representing complex documents, from addresses to entire books or RFQs. Web services enable seamless document exhchange for business integration.* 

9. List and discuss the distinct roles in Web Services Architecture.
- ***Provider: *** *Develops the web service and exposes it to client applications seeking to utilize its functionality.*
  ***Requestor: *** *Seeks a web service, which can in .Net, Java, or any languages for specific functionality.*
  ***Broker: *** *Grants access to UDDI. while UDDI allows client applications to discover the web service's location.*
10. List and discuss the Web Services Components.

- ***SOAP: *** *- It facilitates communication between web services, allowing for the exchange of structured information in a decentralized, platform-independent manner.*
  ***WSDL: *** *- It defines web service interfaces, operations, and message formats, fascilitating communication and interoperability between applications.* 
  ***UDDI: *** *-Its a directory service enabling business to publish and discovers web services for intergration.* 
  ***Web Services*** *-A modular, distributed applications using standardized protocols for data exchange among diverse platforms over the internet.*
