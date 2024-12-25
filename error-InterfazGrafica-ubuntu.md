# Error intefaz grafica Ubuntu Desktop
Reinstalar Interfaz Grafica Ubuntu.


Acceda con su usuario, y a continuacion:

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
