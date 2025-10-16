# T03: Seguretat Lògica: recuperant accés a sistemes

![Imatge 01](img/I1.png)

Per recuperar la contrasenya, el primer pas serà entrar al menú d’opcions avançades de Zorin.

![Imatge 09](img/I9.png)

Després de donar-li a opcions avançades, entrarem dins de **Zorin with Linux 6.8.0-85-generic (recovery mode)**.ç

![Imatge 02](img/I2.png)

Ens sortirà aquest menú, on li donarem a **root** per poder tenir permisos de superusuari.

![Imatge 03](img/I3.png)

Amb aquesta comanda tornarem a muntar el sistema.

![Imatge 04](img/I4.png)

Després, amb la comanda **passwd**, tornarem a inserir una contrasenya.

![Imatge 10](img/I10.png)

Amb la comanda **grub** crearem un hash a partir d’una contrasenya.

![Imatge 12](img/I12.png)

La qüestió és que necessitarem copiar tot el text, però no és gaire còmode; llavors utilitzarem aquesta comanda per copiar-lo.

![Imatge 14](img/I14.png)

Després obrirem l'arxiu **40_custom**.

[Per fer els següents passos necessitarem obrir l’editor d’arxius.]

![Imatge 15](img/I15.png)

On introduirem el següent:

set superusers="nombre_login"

password_pbkdf2 nombre_login

![Imatge 16](img/I16.png)

I després, per últim, aplicarem els canvis.
