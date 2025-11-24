Servicios abiertos
Como siempre, comenzamos la resolución del CTF enumerando los servicios que tiene la máquina abiertos. 
<img width="749" height="403" alt="image" src="https://github.com/user-attachments/assets/47eceac6-4ef9-415e-85f2-903243f226f0" />

```bash
nmap -p- --open --min-rate 2000 -Pn -n -vvv 192.168.236.101
```
test
