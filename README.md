Cree un docker-compose.yml para desplegar el contenedor como balanceador de carga haproxy el cual serviré en el puerto **8088**. El balanceador realiza el balanceo de dos contenedores sitio1(nodejs) y sitio2(nodejs) que servirén en el puerto **80**.  Los sitios web respondem con distintos mensajes así podran verificar que el balanceo funciona.  Para finalizar haciendo **localhost:8088** el balanceador mostrará alternadamente los sitios sitio1 y sitio2. 
(El profesor me permitio hacer con haproxy)

En el archivo pasos.txt estan los comandos y los pasos que seguí para poder hacer esta tarea
