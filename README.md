What is Ingress: An API object that manages external access to the services in a cluster, typically HTTP. Ingress may provide load balancing, SSL termination, and name-based virtual hosting.
Ingress exposes HTTP and HTTPS routes from outside the cluster to services within the cluster. Traffic routing is controlled by rules defined on the Ingress resource.


What is a sticky session: If one request goes to pod1, all subsequent requests for that specific user go to the same pod1.

What is ratio-based load balancing: Send 3 requests to pod1 and 7 requests to pod2.
