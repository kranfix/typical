GOLANG
======

# Instalación

En Ubuntu:

```bash
sudo apt install golang
```

En Fedora:

```bash
sudo yum install golang
```

En Windows:
```*Install:
*[Go](https://golang.org/dl/)
*Si tu sistema es de 64 bits buscar el instalador .msi
*Panel de control>Sistema y seguridad>Sistema>Configuración avanzada del sistema>Variables de entorno>Variables del sistema>Nueva
*Nombre de la variable:GOPATH, Valor de la variable: '&HOME'\go
*Reiniciar el sistema
```


# Configurar configuración de bashrc

El archivo `Makefile` fue creado para facilitar la
configuración de Golang y la creación de la estructura
de archivos concerniente a ellas.

```bash
make all
```

Y cerrar y abrir sesión.

En caso no quieras cerrar sesión, solo tienes que ejecutar
línea por línea lo que se encuentra en el archivo golang
en la terminal en Linux o en Git Bash en Windows.
