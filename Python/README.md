
# ANEXO: README DE PYTHON

## PREPARACIÓN DEL ENTORNO COLAB

Des de [Colab](http://colab.research.google.com), hay que clonar el repositorio y preprar el entorno, cada vez que inicias un nuevo libro. En los libros se incluye el código necesario.

```
if 'google.colab' in str(get_ipython()):
    !git clone https://github.com/griu/mbdds_fc20.git /content/mbdds_fc20
    !git -C /content/mbdds_fc20 pull
    %cd /content/mbdds_fc20/Python
    !python -m pip install -r requirementsColab.txt
```

## PREPARACIÓN ENTORNO LOCAL-JUPYTER (OPCIONAL)

### CLONAR REPOSITORIO

En local puedes utilizar el mismo proyecto que has clonado en el [README DE R](../R/README.md). 

Para actualizarlo de nuevo, des de consola.

```
cd mbdds_fc20
git pull
cd Python
```

### CREAR EN LOCAL UN NUEVO ENVIRONMENT DE ANACONDA

Abrimos una línea de comandos (con *Anaconda 3.0* ya disponible).

- Windows: Escribimos `Anaconda` en el menú Inicio y aparecerá la consola MS-DOS de Anaconda.
- Linux: Abrimos Terminal

```
conda deactivate
conda create -n mbdds_rpy20 python=3.6.9
conda activate mbdds_rpy20
```

Verifica que se ha creado y está activo.

```
conda info --envs
```

### INSTALA LAS LIBRERIAS DE PYTHON

```
cd mbdds_fc20/Python
conda activate mbdds_rpy20
python -m pip install -r requirements.txt
```

### PUBLICAR EL KERNEL

Para acceder al nuevo environment desde Jupyter necesitas publicar el kernel.

```
python -m ipykernel install --user --name mbdds_rpy20 --display-name "mbdds_rpy20"
```

Puede tardar unos minutos en publicarse.

### LANZAR ENTORNO JUPYTER NOTEBOOK

Para acceder al servidor Jupyter. 

```
conda activate mbdds_rpy20
jupyter notebook
```

Debería abrirse un navegador con acceso a Jupyter desde donde podrás acceder a los notebooks.  Habitualmente el servidor Jupyter se abre en http://localhost:8888/ .

