# Firewalld

### Print everything: 
```
firewall-cmd --list-all
```

### Print allowed services:
```
firewall-cmd --list-service
```

### Print allowed ports:
```
firewall-cmd --list-ports
```

### Allow service:
```
firewall-cmd --permanent --add-service=ssh
firewall-cmd --permanent --add-service={ssh,http,https}
```

### Remove service:
```
firewall-cmd --permanent --remove-service=ssh 
firewall-cmd --permanent --remove-service={ssh,http,https}
```

### Allow port:
```
firewall-cmd --permanent --add-port=8888/tcp
```

### Remove port:
```  
firewall-cmd --permanent --remove-port=8888/tcp
```

### Add a new service:
```
Copy a service file from '/usr/lib/firewalld/services' to '/etc/firewalld/services' and modify it
```
