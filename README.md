
Para ejecutar el temario de R y Python en local se incluye la siguiente guía.

#### COPIA LOCAL DEL PROYECTO GITHUB

##### FORK REPOSITORIO GITHUB (OPCIONAL)

Para poder copiar el proyecto en tu gestor web de Git, por ejemplo Github, el primer paso es hacer un FORK. Haz FORK accediendo a https://github.com/griu/mbdds_fc20.git

Introduze tu usuario y contraseña para hacer la copia.

##### CLONAR EL REPOSITORIO

Abrimos una linea de comandos (con *Anaconda 3.0* ya disponible).

- Windows: Escribimos `Anaconda` en el menú Inicio y aparecerá la consola MS-DOS de Anaconda.
- Linux: Abrimos terminal xterm

Se ubicar tus repositorios dentro de una carpeta específica para git. Por ejemplo, en Widnows.

```
cd Documents
mkdir git
cd git
```

O bién, en linux.

```
cd ~
mkdir git
cd git
```

Clona el repositorio des de tu servidor Git.

```
git clone https://github.com/NOMBRE_USUARIO_PROPIO/mbdds_fc20.git
```

#### PREPARACIÓN ENTORNO RSTUDIO

##### CREAR EL PROYECTO

Crea un nuevo proyecto de RStudio sobre tu directorio local de Git 

`File > New Project > Existing Directory > git\mbdds_fc20 > OK`

##### INSTALAR PACKAGES DES DE R

Instala de uno en uno los siguientes paquetes.

```
install.packages("pander")
install.packages("kableExtra")
install.packages("tidyverse")
install.packages("reticulate")
webshot::install_phantomjs()
install.packages("magick")
install.packages("ggrepel")
install.packages("cowplot")
install.packages("mosaicData")
install.packages("datos")
install.packages("flextable")
install.packages("gganimate")
```

En el entorno de Linux es neceario haber instalado des de terminal bash: `libxml2-dev`, `libssl-dev`, `libcurl4-openssl-dev` y `libmagick++-dev`

#### PREPARACIÓN ENTORNO ANACONDA-PYTHON-JUPYTER (OPCIONAL)

##### CREAR UN NUEVO ENVIRONMENT DE ANACONDA

Crea el entorno des de consola de Anaconda 3.0.

```
conda deactivate
conda create -n mbdds_fc20_env python=3.7.3
conda activate mbdds_fc20_env
```

Verifica que se ha creado y esta activo.

```
conda info --envs
```

##### INSTALA LAS LIBRERIAS DE PYTHON

Este paso instala las librerias!!! 

```
cd mbdds_fc20
conda activate mbdds_fc20_env
python -m pip install -r requirements.txt
```

##### PUBLICAR EL KERNEL

Para acceder al nuevo environment des de Jupyter necesitas publicar el kernel.

```
python -m ipykernel install --user --name mbdds_fc20_env --display-name "mbdds_fc20_env"
```

Puede tardar unos minutos en publicarse.

##### LANZAR ENTORNO JUPYTER NOTEBOOK

Para acceder al servidor Jupyter. 

```
conda activate mbdds_fc20_env
jupyter notebook
```

Debería abrirse un navegador con acceso a Jupyter des de donde podras acceder a los notebooks.

