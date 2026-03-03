# Create vlan
### Privileged EXEC Mode
```bash
exit
```

### Privileged EXEC (#)
```bash
show vlan
```

### Global Mode 
```bash
do show vlan
```

### Configuration mode

```bash
conf t
```

### Create vlan

```bash
vlan id #10,20
```

### vlan name
```bash
name student
```

### Exit from configuration mode
```bash
exit
```

### 
```bash
Switch(config)#interface fa0/2
Switch(config-if)#
```

### access mode

```bash
switchport mode access
```


### access vlan 

```bash
Switch(config-if)#switchport access vlan 10
```


```mermaid
graph TD;
A[exit] --> B[show vlan]
B[vlan show] --> C[conf t]
C[conf t] --> D[interface id ]
D[interface id ] --> E[switchport mode access]
E[switchport mode access] --> F[switchport access vlan id]
F[switchport access vlan id] --> G[ip address 192.168.77.106 255.255.255.0]
```

```mermaid
graph TD;
A[conf t] --> X[enable secret password]
X[enable secret password] --> B[line vty 0 15]
B[line vty 0 15] --> C[password 1234]
C[password 1234] --> D[login]
D[login] --> E[exit]
```