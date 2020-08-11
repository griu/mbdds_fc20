# mbdds_fc20

aprendizaje de R y Python

```
conda deactivate
conda create -n mbdds_fc20_env python=3.7.3
conda activate mbdds_fc20_env
```

Abrimos la linea de comandos de Anaconda 3.0:

- Escrivimos Anaconda en Inicio de Windows y aparecera la consola MS-DOS de Anaconda.

```
cd Documents
mkdir git
cd git
git clone https://github.com/griu/mbdds_fc20.git
cd mbdds_fc20
#python -m pip freeze > requirements.txt
python -m pip install -r requirements.txt
```

# Des de RStudio

- Creamos nuevo proyecto
  - Existing Directory
  - git\mbdds_fc20
  - OK

# info de conda

```
(mbdds_fc20_env) C:\Users\alumno-02\Documents\git\mbdds_fc20>conda info --envs
# conda environments:
#
base                     C:\ProgramData\Anaconda3
mbdds_fc20_env        *  C:\Users\alumno-02\.conda\envs\mbdds_fc20_env
```

#  instalar packages des de R

```
install.packages("pander")
install.packages("kableExtra")
install.packages("tidyverse")
install.packages("reticulate")
install.packages("magick")
webshot::install_phantomjs()
```

# configurar GIT des de R

En el prompt de anaconda 3.

```
git config --global user.email "ferran.carrascosa@gmail.com"
git config --global user.name "ferran.carrascosa"
```


# publicar kernel:

```
python -m ipykernel install --user --name mbdds_fc20_env --display-name "mbdds_fc20_env"
```

Puede tardar unos minutos en publicarse.

# lanzar jupyter notebook

```
jupyter notebook
```

Ahora ya se pueden abrir notebooks con el environment.



