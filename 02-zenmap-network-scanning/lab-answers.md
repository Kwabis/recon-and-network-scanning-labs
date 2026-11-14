# Zenmap lab answers

**Task 2. Local IP address and LAN subnet**
Local IP: `10.236.94.28`. LAN subnet: `10.236.94.0/24` (mask 255.255.255.0).

**Task 3. List of live hosts**
```
Nmap scan report for 10.236.94.25
Host is up (0.0098s latency).
MAC Address: DA:8A:52:E4:22:79 (Unknown)
Nmap scan report for 10.236.94.28
Host is up.
Nmap done: 256 IP addresses (2 hosts up) scanned in 16.92 seconds
```

**Task 4. How many hosts are live?**
2 hosts are live (including my PC).

**Task 5. IP addresses of the live hosts**
```
10.236.94.25   (default gateway)
10.236.94.28   (my PC)
```

**Task 6. MAC addresses of the live hosts**
```
DA:8A:52:E4:22:79   (10.236.94.25, default gateway)
70-1C-E7-E7-65-5D   (10.236.94.28, my PC, from ipconfig /all)
```

**Task 7. Topology saved as PDF**
Saved as [`topology.pdf`](topology.pdf).
