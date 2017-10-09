Configuración de ip estática para ethernet
==========================================

# Procedimiento

Escribir lo siguiente en el archivo `/etc/network/interfaces` con permisos de superusario:

```
$ sudo nano /etc/network/interfaces
```

Luego escribir lo siguiente:

```
auto lo
iface lo inet loopback

auto the0
iface eth0 inet static
address 192.168.0.xx
netmask 255.255.255
gateway 192.168.0.yy

```

Cerrar y guardar.
