SCM - SYSTEM CONTROL MANNAGER
=============================

Configuraciones básicas de los scm más usados:

* Git
* Mercurial
* Bazaar

Todos tienen en común la necesidad de configurar sus
llaves ssh -- procedimiento que veremos aquí.

## Configuración SSH

Ingresar a la terminal en Linux o a Git Bash en Windows.

Si no han creado un llave ssh, tipear:

```bash
ssh-keygen -t rsa -C "your_email@example.com"
```

Tras generar la llave, agregarla:

```bash
ssh-add ~/.ssh/id_rsa
```

Luego copiar el contenido del archivo "~/.ssh/id_rsa.pub"
a las llaves de seguridad de github.com o bitbucket.org.


### Más detalles de como generar la llave

Las empresas que suelendar el servicio de alojamiento de
repositorios tienen documentación más detallado de lo que
describe este documento. Algunas de estas documentaciones
las encontramos en:

* [Github](https://help.github.com/articles/generating-ssh-keys/).
* [Bitbucket](https://help.github.com/articles/generating-ssh-keys/).
* [Launchpad](https://help.github.com/articles/generating-ssh-keys/).

