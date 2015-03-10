GT - Gestor de versiones
=========================

## Instalación

### En Linux

En Fedora:

``` bash
sudo yum install git
```

En Ubuntu:

```bash
sudo apt-get install git
```
o de la nueva forma

```bash
sudo apt install git
```

### En MS Windows

Descargar la versión para Windows desde .....

Iniciar descarga

## Configuración SSH

Ingresar a la terminal en Linux o a Git Bash en Windows.

Si no han creado un llave ssh, tipear:

```bash
ssh-keygen -t rsa -C "your_email@example.com"
```

Tras crear la llave, agregarla:

```bash
ssh-add ~/.ssh/id_rsa
```

Luego copiar el contenido del archivo "~/.ssh/id_rsa.pub"
a las llaves de seguridad de github.com o bitbucket.org.

Más detalles de como generar la llave,
[aquí](https://help.github.com/articles/generating-ssh-keys/).


## Configuración global de git

Ejecutar las siguientes líneas:

```bash
git config --global user.name "Nombre Apellido"
git config --global user.email "tu@email.com"
```
