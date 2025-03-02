# Metasploit Pro

sudo docker run -p 3790:3790 -p 7337:7337 --name metasploit_pro -d gastonbarbaccia/metasploitpro tail -f /dev/null

sudo docker exec -it metasploit_pro bash

service metasploit status
service metasploit start

URL: https://localhost:3790/
Usuario: admin
Contraseña: JGJBXh:Q1




