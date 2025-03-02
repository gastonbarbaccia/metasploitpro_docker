# Metasploit Pro

## Instalacion de metasploit pro
sudo docker run -p 3790:3790 -p 7337:7337 --name metasploit_pro -d gastonbarbaccia/metasploitpro tail -f /dev/null

## Validar los servicios
sudo docker exec -it metasploit_pro bash

service metasploit status  
service metasploit start

## Acceder a la consola
URL: https://localhost:3790/  
Usuario: admin  
Contraseña: JGJBXh:Q1

## Actualización de metasploit offline 
Documentacion  
https://docs.rapid7.com/metasploit/installing-metasploit-pro/  

Pasos para actualizar metasploit pro offline  
https://docs.rapid7.com/metasploit/updating-metasploit/  

Descargar las actualizaciones offline  
https://docs.rapid7.com/release-notes/metasploit/




