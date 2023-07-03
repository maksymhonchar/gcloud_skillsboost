- The job of a load balancer is to distribute user traffic across multiple instances of an application

- Cloud Load Balancing is a fully distributed, software-defined, managed service for all your traffic.
    - Because the load balancers don’t run in VMs that you have to manage, you don’t have to worry about scaling or managing them.
    - You can put Cloud Load Balancing in front of all of your traffic: HTTP(S), other TCP and SSL traffic, and UDP traffic too.

- Cloud Load Balancing provides cross-region load balancing, including automatic multi-region failover, which gently moves traffic in fractions if backends become unhealthy.

- Cloud VPC load-balancing options:
    1. Global HTTP(S): For cross-regional load balancing for a web application
    2. SSL Proxy: For Secure Sockets Layer (SSL) traffic that is not HTTP
    3. TCP Proxy: For TCP traffic that does not use Secure Sockets Layer
    4. Regional external: If you want to load balance UDP traffic, or traffic on any port number
    5. Internal HTTP(S): For load balance traffic inside your project, for example, between the presentation layer and the business layer of your application
