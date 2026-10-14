# Firewall Configuration

## Mission 8: The Cloud Security Engineer

### 1. Allow SSH

```bash
sudo ufw allow ssh
```


### 2. Configure the Default Policies

```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing
```


### 3. Enable the Firewall

```bash
sudo ufw enable
sudo ufw status verbose
```

### 4. Allow the Web Application

```bash
sudo ufw allow 8080/tcp
sudo ufw status numbered
```


### 5. Verify the Web Application

```bash
curl http://localhost:8080
sudo docker ps
```


### 6. SSH Security Warning

If `sudo ufw enable` is executed before `sudo ufw allow ssh`, incoming SSH connections may be blocked by the default deny policy, potentially locking a remote administrator out of the server.

