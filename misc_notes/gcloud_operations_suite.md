- Google Cloud's operations suite:
    - monitoring
    - logging
    - error reporting
    - debugging

- Monitoring:
    - BigQuery: queries in flight, slots used
    - Cloud Run: CPU/mem utilization, billable time
    - Compute: CPU/mem utilization, uptime
    - Applications: OpenTelemetry custom metrics

- Key log categories:
    - Cloud audit logs: who did what, where, when? 
    - Agent logs: fluentd agent, common 3party applications, system software
    - Network logs: VPC flow, firewall rules, NAT gateway, load balancer
    - Service logs: Standard Out/Error, created with API - created by devs

- Crashes in most modern languages are “exceptions,” which are not caught and handled by the code itself.
- Its management interface displays the results with sorting and filtering capabilities.
- A dedicated view shows the error details: time chart, occurrences, affected user count, first and last-seen dates, and a cleaned exception stack trace. 

- Cloud Trace is a tracing system that collects latency data from your distributed applications and displays it in the Google Cloud Console.
    - Cloud Trace can capture traces from applications deployed on App Engine, Compute Engine VMs, and Kubernetes Engine containers.
    - Performance insights are provided in near-real time, and Cloud Trace automatically analyzes all of your application's traces to generate in-depth latency reports to surface performance degradations.

- Google’s Cloud Debugger lets you debug your applications while they’re running in production, without stopping them or slowing them down, so you can examine your code's function and performance under actual production conditions.

- Poorly performing code increases the latency and cost of applications and web services every day, but nobody knows or does anything about it.
- Cloud Profiler changes this by using statistical techniques and extremely low-impact instrumentation that runs across all production application instances to provide a complete CPU and heap picture of an application without slowing it down.
