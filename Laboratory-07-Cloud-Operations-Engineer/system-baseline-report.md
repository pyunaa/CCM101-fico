# System Baseline Report

### Memory Usage

Command executed:

```bash
free -h
```

| Type       | Total | Used  | Free  | Shared | Buff/Cache | Available |
|------------|------:|------:|------:|-------:|-----------:|----------:|
| Mem        | 1.9Gi | 402Mi | 1.2Gi | 1.1Mi  | 454Mi      | 1.5Gi     |
| Swap       | 1.0Gi | 0B    | 1.0Gi |        |            |           |


### Disk Storage

Command executed:

```bash
df -h /
```

| Filesystem | Size | Used | Avail | Use% | Mounted on |
|------------|-----:|-----:|------:|-----:|------------|
| /dev/vda1  | 19G  | 5.5G | 13G   | 30%  |            |


### Importance of Disk Monitoring

Checking disk space before a massive traffic surge is important because insufficient storage can prevent applications from writing logs, storing data, or operating correctly.
