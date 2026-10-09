# Mission Reflection

Completing the Cloud Operations Engineer laboratory helped me understand why monitoring is an important part of managing cloud infrastructure. I learned that deploying an application is not enough because the server and containers must also be monitored to ensure that they continue operating properly.

Checking the host server's resources is important even when containers appear to run perfectly. Containers depend on the host's CPU, memory, and storage. If the host runs out of memory, has insufficient disk space, or experiences excessive CPU usage, applications may become slow or stop working. Establishing a baseline helps administrators understand normal resource usage and identify unusual changes.

The `docker logs` command is useful when a user reports that they cannot log in to a web application. Logs can reveal failed requests, application errors, and other events that help narrow down the cause of the problem. For example, an administrator can inspect the recorded HTTP status codes and request paths to determine whether a request reached the server and how the server responded. However, additional application and authentication logs may be necessary to diagnose the exact reason for a login failure.

Monitoring logs and metrics serves different purposes. Logs provide detailed records of events, requests, and errors, while metrics show numerical measurements such as CPU usage, memory consumption, and network traffic. Using both provides a clearer understanding of application health because metrics can reveal unusual resource usage while logs help explain specific events.

Large enterprise companies can monitor thousands of containers using centralized monitoring systems. Tools such as Prometheus collect and store metrics, while Grafana displays them through dashboards and visualizations. Alerting systems can notify engineers when resource usage exceeds defined thresholds or when services become unavailable.

This laboratory improved my ability to troubleshoot Linux environments by teaching me how to inspect system resources, deploy an Nginx container, generate HTTP requests, analyze access logs, and observe Docker metrics. I also learned that accurate documentation and screenshots are important when presenting technical evidence. These skills will help me investigate problems systematically instead of relying on guesses.
