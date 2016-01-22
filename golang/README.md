GOLANG
======

# Instalación

### En Ubuntu:

```bash
sudo apt install golang
```

### En Fedora:

```bash
sudo yum install golang
```

### En general:

Verificar cual es el última versión estable de Go en:
```
https://golang.org/dl/
```

En caso Go esté instalado, eliminar la carpeta de instalación
```bash
sudo rm -rf /usr/local/go
```

Descargar la versión más actual e instalar
```bash
wget https://storage.googleapis.com/golang/go1.5.linux-amd64.tar.gz
sudo tar -C /usr/local -xzf go1.5.linux-amd64.tar.gz
```

### En Windows:

* Descargar [Go](https://golang.org/dl/)
* Si tu sistema es de 64 bits buscar el instalador .msi
* Panel de control>Sistema y seguridad>Sistema
>Configuración avanzada del sistema>Variables de entorno
>Variables del sistema>Nueva
* Nombre de la variable:GOPATH, Valor de la variable: '&HOME'\go
* Reiniciar el sistema


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
