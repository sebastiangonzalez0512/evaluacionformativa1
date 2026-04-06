# evaluacionformativa1
Evaluación Formativa 1 | Creación de una máquina virtual

-Instrucciones-

Esta evaluación consiste la creación de una máquina virtual con Windows Server 2019 edición estándar con GUI (8gb RAM, 30GB disco y 2 vcpu) y en una máquina virtual Linux RHEL9 o similar (Rocky, Alma, otro) solo CLI (8gb RAM, 30GB disco y 2 vcpu). 

-WINDOWS SERVER 2019-
Cree de máquina virtual Windows Server 2019 edición estándar con GUI (8gb RAM, 30GB disco y 2 vcpu), utilizando ISO dispuesta en el laboratorio.  

<img width="599" height="329" alt="image" src="https://github.com/user-attachments/assets/33bc6637-b65a-44e2-90df-e2f4f30785a4" />

Verifique la dirección IP  

<img width="1017" height="839" alt="image" src="https://github.com/user-attachments/assets/b11f4fde-f549-4d6c-ad23-0b6db0292315" />

Habilite la opción de acceso remoto por RDP.

<img width="1021" height="838" alt="image" src="https://github.com/user-attachments/assets/cbbcf4f6-5a66-4d06-ba38-16802af1cb6d" />



-RED HAT 9-
Cree de Máquina virtual Linux RHEL9 o similar (Rocky, Alma, otro) solo CLI (8gb RAM, 30GB disco y 2 vcpu) utilizando ISO dispuesta en el laboratorio.  

<img width="597" height="366" alt="image" src="https://github.com/user-attachments/assets/b8624048-cba6-4c15-a53b-16c5629a8379" />

Verifique la dirección IP 

<img width="656" height="458" alt="image" src="https://github.com/user-attachments/assets/0cfc0f72-d758-423e-bb6b-1c19e8a90bbd" />

Habilite la opción de acceso remoto por SSH y compruebe su funcionamiento 

<img width="657" height="465" alt="image" src="https://github.com/user-attachments/assets/69acb2e6-50c0-4b2a-a2e7-b32f50fbcb8a" />
Aqui inicie el servicio de ssh y ademas me asegure de abrir el puerto 22

CONEXION A ESCRITORIO REMOTO

para conexion a rh: PUTTY

ifconfig
systemctl status sshd
systemctl start ssh
