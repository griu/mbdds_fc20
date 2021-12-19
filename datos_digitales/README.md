
#### Preparación entorno Local-Jupyter

<br>

Para las prácticas de Selenium y MongoDB es necesario preparar el entorno local de Jupyter.

<br>

##### Clonar repositorio

<br>

En local puedes utilizar el mismo proyecto que has clonado en el **README DE R**. 

Para actualizarlo de nuevo, desde consola.

<br>

```
cd mbdds_fc20
git pull
cd Python
```

<br>

##### Environment de Anaconda

<br>

En local puedes utilizar el mismo environment que has preparado en el **README DE PYTHON**. No obstante, es necesario que lo actualices.

<br>

```
# Activar entorno
conda activate mbdds_rpy20
# Actualizar paquetes des de la carepta Python
python -m pip install -r requirements.txt  
# publicar el kernel
python -m ipykernel install --user --name mbdds_rpy20 --display-name "mbdds_rpy20"
# Abrir los notebooks
jupyter notebook
```
