# Unidad - 2
## Ejercicio 1

1. El servicio de WHOIS es un directorio gratuito y de acceso público que contiene información técnica y de contacto de los titulares de nombres de dominio registrados.
Los registros se encargan de recopilar y poner esos datos a disposición del público en general, bajo los términos de los acuerdos con la ICANN.

WHOIS no es una base de datos única con gestión centralizada. Por el contrario, los datos de registración se guardan en distintas ubicaciones y son administrados por múltiples registros y registradores. Ellos se encargan de establecer sus propias pautas para el servicio de WHOIS.

Los ISP usan el servicio de WHOIS para identificar personas o empresas responsables del funcionamiento de una red o dominio en Internet. Sin embargo, los principales usos de Whois son:

* Determinar si un nombre de dominio se encuentra disponible o está en uso.
* Ponerse en contacto con los administradores de red por cuestiones técnicas.
* Saber la identidad real, el domicilio comercial y la información de contacto del dueño del dominio registrado.
* Poder ponerse en contacto con el titular de un nombre de dominio para cualquier tipo de negocio.
* Notificar al dueño del dominio de su obligación de mantener los datos de registración exactos.
* Contactar al propietario del dominio en relación con cuestiones que tienen que ver con la protección y el ejercicio efectivo de derechos de propiedad intelectual
* Poder investigar los correos electrónicos no deseados.

En America latina quien se encarga de este tipo de regulaciones es LACTLD y particularmente en Argentina NIC.

fuente:https://www.redeszone.net/tutoriales/internet/que-es-whois/

## Ejercicio 2

```
santi@santi-Inspiron-3493:~$ ping google.com
PING google.com (216.58.202.46) 56(84) bytes of data.
64 bytes from eze04s05-in-f14.1e100.net (216.58.202.46): icmp_seq=1 ttl=117 time=16.1 ms
64 bytes from eze04s05-in-f14.1e100.net (216.58.202.46): icmp_seq=2 ttl=117 time=18.4 ms
64 bytes from eze04s05-in-f14.1e100.net (216.58.202.46): icmp_seq=3 ttl=117 time=18.7 ms
64 bytes from eze04s05-in-f14.1e100.net (216.58.202.46): icmp_seq=4 ttl=117 time=19.6 ms
```

```
ip: 216.58.202.46
binario: 11011000.00111010.11001010.00101110
```

```
santi@santi-Inspiron-3493:~$ ping https://utn.edu.ar/es/
ping: https://utn.edu.ar/es/: Name or service not known
santi@santi-Inspiron-3493:~$ ping utn.edu.ar/es
ping: utn.edu.ar/es: Name or service not known
santi@santi-Inspiron-3493:~$ ping utn.edu.ar
PING utn.edu.ar (52.151.241.218) 56(84) bytes of data.
^C
--- utn.edu.ar ping statistics ---
84 packets transmitted, 0 received, 100% packet loss, time 84998ms
```
```
ip: 52.151.241.218
binario: 00110100.10010111.11110001.11011010
```
```
santi@santi-Inspiron-3493:~$ ping github.com
PING github.com (140.82.113.3) 56(84) bytes of data.
64 bytes from lb-140-82-113-3-iad.github.com (140.82.113.3): icmp_seq=1 ttl=50 time=255 ms
64 bytes from lb-140-82-113-3-iad.github.com (140.82.113.3): icmp_seq=2 ttl=50 time=483 ms
64 bytes from lb-140-82-113-3-iad.github.com (140.82.113.3): icmp_seq=3 ttl=50 time=403 ms
64 bytes from lb-140-82-113-3-iad.github.com (140.82.113.3): icmp_seq=4 ttl=50 time=323 ms
64 bytes from lb-140-82-113-3-iad.github.com (140.82.113.3): icmp_seq=5 ttl=50 time=243 ms
64 bytes from lb-140-82-113-3-iad.github.com (140.82.113.3): icmp_seq=6 ttl=50 time=471 ms
^C
--- github.com ping statistics ---
6 packets transmitted, 6 received, 0% packet loss, time 5007ms
rtt min/avg/max/mdev = 242.867/362.803/482.643/95.909 ms
```
```
ip: 40.82.113.3
binario: 00110100.10010111.11110001.11011010
```
```
santi@santi-Inspiron-3493:~$ ping stackoverflow.com
PING stackoverflow.com (151.101.1.69) 56(84) bytes of data.
64 bytes from 151.101.1.69 (151.101.1.69): icmp_seq=1 ttl=56 time=41.3 ms
64 bytes from 151.101.1.69 (151.101.1.69): icmp_seq=2 ttl=56 time=78.4 ms
64 bytes from 151.101.1.69 (151.101.1.69): icmp_seq=3 ttl=56 time=42.6 ms
64 bytes from 151.101.1.69 (151.101.1.69): icmp_seq=4 ttl=56 time=42.9 ms
64 bytes from 151.101.1.69 (151.101.1.69): icmp_seq=5 ttl=56 time=42.9 ms
64 bytes from 151.101.1.69 (151.101.1.69): icmp_seq=6 ttl=56 time=42.9 ms
^C
--- stackoverflow.com ping statistics ---
6 packets transmitted, 6 received, 0% packet loss, time 5007ms
rtt min/avg/max/mdev = 41.251/48.479/78.376/13.382 ms
```

```
ip: 151.101.1.69
binario: 00110100.10010111.11110001.11011010
```

## Ejercicio 3
![Bus Topology Template](https://user-images.githubusercontent.com/29964977/122690065-9b750280-d1fd-11eb-82bb-ce065c828969.png)


Tipologia bus con IPS e IDS  dos firewalls
