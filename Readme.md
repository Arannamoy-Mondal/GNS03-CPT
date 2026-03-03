```mermaid
graph TD;
A[Privileged EXEC Mode exit] --> B[show vlan]
B[vlan show] --> C[conf t]
C[conf t] --> D[interface id ]
D[interface id ] --> E[switchport mode access]
E[switchport mode access] --> F[switchport access vlan id]

```



# Privileged EXEC Mode
```bash
exit
```

# Privileged EXEC (#)
```bash
show vlan
```

# Global Mode 
```bash
do show vlan
```

# Configuration mode

```bash
conf t
```

# Create vlan

```bash
vlan id #10,20
```

# vlan name
```bash
name student
```

# Exit from configuration mode
```bash
exit
```

# 
```bash
Switch(config)#interface fa0/2
Switch(config-if)#
```

# access mode

```bash
switchport mode access
```


# access vlan 

```bash
Switch(config-if)#switchport access vlan 10
```