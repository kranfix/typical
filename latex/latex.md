# LaTex

## Instalación de TexLive en Ubuntu:

Para instalar el TexLive en Ubuntu, abrimos el terminal y escribimos lo siguiente:
	->sudo apt-get install texlive-full
Esta opción instalará el DVD de TexLive

Debido a que los cortes de internet cancelan una descarga en Ubuntu, muchas veces es preferible descargar partes específicas, puesto que el DVD de TexLive tiene un tamaño de 4Gb.
Algunas partes de instalación son las siguientes:

* Instalar la base de los programas relacionados a Tex:
	`sudo apt-get install texlive-base`

* Instalar fuentes usadas en LaTex:
	`sudo apt-get install texlive-fonts-recommended`

* Instalar fuentes adicionales:
	`sudo apt-get install texlive-fonts-extra`

* Instalar pdfLaTex (compilador)
	`sudo apt-get install texlive-latex-base`

* Instalar archivos de estilo en LaTex
	`sudo apt-get install texlive-latex-recommended`

* Instalar archivos relacionados a subfiguras:
	`sudo apt-get install texlive-latex-extra`

* Instalar algoritmos en TexLive:
	`sudo apt-get install texlive-science`

* Instalar algunas librerias adicionales:
`sudo apt-get install texlive-bibtex-extra`
`sudo apt-get install texlive-bibtex-extra biber`

Al ejecutar los comandos de instalación, se debe digitar la
contraseña de la sesión si es necesario, y posteriormente confirmar
instalación. Existen archivos que están en el DVD y no se presentan
en las instalaciones realizadas, por lo que al final es recomendable
usar la línea:
  `sudo apt-get install texlive-full`

Aunque podemos usar cualquier editor para hacer los archivos .tex
(que 	serán convertidos a un formato deseado como .pdf por el
texlive), es recomendable usar el texmaker, el cual se instala en
el terminal con el código:

```bash
sudo apt-get install texmaker
```


##Instalación de MiKTeX en Windows:

* MiKTeX es el compilador de LaTex al archivo deseado
Descargamos la versión básica del MiKTeX para Windows en la siguiente página:
http://miktex.org/download

Luego abrimos desde el menú inicio el Update Wizard para asegurarnos
de obtener las versiones más recientes de los paquetes necesarios.


* Un editor de texto recomendado es TeXMaker:
Posteriormente se instala el TeXMaker en Windows como editor de Texto desde la página:

http://www.xm1math.net/texmaker/download.html

Descargamos el archivo instalador (o el protable, según lo deseado),
y procedemos con la instalación.
