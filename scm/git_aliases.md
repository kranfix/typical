# GIT - Aliases

Escribir `git status` puede ser muchas veces muy molesto
por lo largo que es escribirlo, por lo  que nos gustaría
tener un comando más corto como `git st`. En este caso
`st` es un alias para `status`.

Aquí se muestran los comandos para generar alias:

```bash
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.cm 'commit -m'
git config --global alias.di diff
git config --global alias.br branch
```
