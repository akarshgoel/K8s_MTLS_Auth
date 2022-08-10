**Establish mTLS auth for apps running over k8s cluster.**

- Microservices provide scalability, resiliency, ease of accessibility and act like self-contained independent applications. But, as microservices grow, it becomes difficult to establish secure communication with them. Absence of secure communication could lead to security breaches like identity spoofing, identity repudiation, data in-confidentiality, broken data integrity and data un-availability. 

- For instance, if a rogue microservice exists in the organization's environment, it could easily access critical microservices residing in the environment.

- SPIRE Project, an implementation of the Secure Production Identity Framework for Everyone (SPIFFE), is an open-source standard which could be leveraged to solve above-mentioned security challenges. SPIFFE framework could be used for secure bootstrapping and issuing unique cryptographic identities to distributed systems. This project showcases how distributed systems could mutually authenticate to prove their individual identities, before these systems could try and access critical data.

