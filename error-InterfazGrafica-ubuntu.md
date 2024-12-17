# Error intefaz grafica Ubuntu Desktop
Si has tenido un problema con la interfaz grafica, y se a desconfigurado o quedado corrupto en ubuntu, no hace falta formatear, se puede recuperar todo sin problema con estos comandos:


Acceda con su usuario:

```
sudo su
```
```
dpkg –configure -a
```
```
apt-get -f install
```
```
apt-get update
apt-get dist-upgrade
```
```
apt-get install –-reinstall ubuntu-desktop
```

Si no funcionase el comando de arriba, indroduce el siguiente:
```
apt-get install ubuntu-desktop
```
