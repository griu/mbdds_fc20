#### Requisitos de entorno Anaconda-Python

Para preprar el entornod de R y Anaconda hay que seguie los siguiente pasos. Se genera un nuevo Envornment de Anaconda llamado `mbdds_fc20_env`. 

```
conda deactivate
conda create -n mbdds_fc20_env python=3.7.3
conda activate mbdds_fc20_env
```

Abrimos la linea de comandos de Anaconda 3.0. Según el sistema operativo: 

- En windows: Escrivimos Anaconda en Inicio de Windows y aparecera la consola MS-DOS de Anaconda.
- En Linux: abrimos la consola bash

A continuación se clona el repositorio

```
# En Windows: cd Documents  
# En Linux: cd ~
mkdir git
cd git
git clone https://github.com/griu/mbdds_fc20.git  # para clonar de cero
git pull                                  # si ya esta clonado
cd mbdds_fc20
python -m pip install -r requirements.txt # instala requerimientos python
```

#### Des de RStudio

- Creamos nuevo proyecto
  - Existing Directory
  - git\mbdds_fc20
  - OK

#### info de conda

```
conda info --envs
## conda environments:
##
#base                     C:\ProgramData\Anaconda3
#mbdds_fc20_env        *  C:\Users\alumno-02\.conda\envs\mbdds_fc20_env
```

#  instalar packages des de R

```
install.packages("pander")
install.packages("kableExtra")
install.packages("tidyverse")
install.packages("reticulate")
webshot::install_phantomjs()
install.packages("magick")
```

#### configurar GIT des de R (sólo Windows)

En el prompt de anaconda 3.

```
git config --global user.email "usuario@dominio.com"
git config --global user.name "usuario"
```

#### Publicar kernel

```
python -m ipykernel install --user --name mbdds_fc20_env --display-name "mbdds_fc20_env"
```

Puede tardar unos minutos en publicarse.

#### Lanzar jupyter notebook

```
jupyter notebook
```

Ahora ya se pueden abrir notebooks con el environment.

