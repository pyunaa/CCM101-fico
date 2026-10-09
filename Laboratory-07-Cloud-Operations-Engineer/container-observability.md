# Container Observability Report

## Application Access Logs

Command executed:

```bash
docker logs clientwebsite
```

### HTTP 404 Error Log

"/usr/share/nginx/html/hidden-admin-page" failed (2: No such file or directory), client: 172.17.0.1, server: localhost, request: "GET /hidden-admin-page HTTP/1.1", host: "localhost:8080"
172.17.0.1 - - [09/Oct/2026:16:29:49 +0000] "GET /hidden-admin-page HTTP/1.1" 404 153 "-" "curl/8.5.0" "-"

### Why Application Logs Are Important

Application logs are vital for troubleshooting because they record requests, errors, and other events that help identify what went wrong. By examining these logs, an administrator can investigate failed requests, determine possible causes, and take appropriate corrective action.

