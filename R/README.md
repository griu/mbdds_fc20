
# Ideas clave

- R es un lenguaje orientado al análisis estadístico que se utiliza ampliamente en el campo de la ciencia de datos.
- R es más potente en visualización de información y datos que Python; aunque por otra parte R es un lenguaje más lento que Python en ejecución.
- R es una opción recomendada si necesitamos hacer un análisis estadístico exhaustivo o un análisis independiente a realizar en una máquina.
- El lenguaje de programación R se integra bien con otros lenguajes de programación como C, C++ o Fortran para tareas de análisis de datos computacionalmente intensivas (alto consumo de recursos como CPU y RAM). Además, puede integrarse con distintas bases de datos y existen bibliotecas que facilitan su utilización desde lenguajes de programación interpretados como Perl y Python.
- R es algo más que un lenguaje de programación. El usuario no programa propiamente, sino que utiliza R interactivamente: ensaya, se equivoca y vuelve a probar. Solo cuando termina el ciclo y el resultado es satisfactorio, produce un resultado final que, generalmente, no es un programa, sino un informe o análisis.
- Se utiliza en todas las fases de análisis de datos:
   - Adquisición y preparación de los datos (bases de datos, ficheros planos, etc.).
   - Análisis de los datos: construcción de modelos predictivos, de agrupamiento o clasificación, utilidades gráficas para la visualización de datos, etc.
   - Manejo y almacenamiento efectivo de los datos como son los cálculos con matrices. Y un lenguaje de programación bien desarrollado que incluye saltos condicionales, bucles, funciones recursivas, utilidades para la entrada y salida de datos, etc.
   - Comunicación de los resultados: realización de informes para presentación de los resultados y conclusiones. Tiene un formato de documentación basado en Markdown, que se utiliza para proporcionar documentación completa tanto en formato físico como digital.
   - Aplicación de los resultados obtenidos: por ejemplo, utilización de modelos predictivos desarrollados para en función de una serie de datos históricos (datos de entrenamiento y test del modelo) predecir ciertas salidas.

# Anexo: Readme de R

#### CLONAR EL PROYETO GITHUB EN LOCAL

Abrimos una línea de comandos (`cmd` o `anaconda` en Windows, `terminal` en Linux).

```
git clone https://github.com/griu/mbdds_fc20.git
```

#### PREPARACIÓN ENTORNO RSTUDIO

##### CREAR EL PROYECTO

Crea un nuevo proyecto de RStudio sobre tu directorio local. 

`File > New Project > Existing Directory > mbdds_fc20 > OK`

El nuevo proyecto ya está conectado a Git.

##### INSTALAR PACKAGES DES DE R

En el entorno de Linux, (no Windows) es necesario haber instalado des del terminal los siguientes paquetes: `libxml2-dev`, `libssl-dev`, `libcurl4-openssl-dev` y `libmagick++-dev` .

Instala de uno en uno los siguientes paquetes desde la consola de RStudio.

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

# Bibliografía

- Y. Xie, J. J. Allaire, G. Grolemund. R Markdown: The Definitive Guide. Chapman & Hall/CRC; 2020. Disponible en: https://bookdown.org/yihui/rmarkdown/

Guía para elaborar con Rmarkdown, documentos que combinan texto, análisis en R o Python con los resultados (tablas o gráficos).

- W. Chang. R Graphics Cookbook,  O’Reilly Media, Inc. 2nd ed.; 2020. Disponible en: https://r-graphics.org/

Desarrollo de gráficos con R.

- G. Grolemund, H. Wickham. R for Data Science.  O’Reilly; 2017. Disponible en: https://es.r4ds.hadley.nz/ (Castellano)

Aprender a cargar datos en R, escoger la estructura de datos óptima, transformarlos, visualizarlos y modelarlos.

- G. Grolemund. Hands-On Programming with R. O’Reilly; 2014. Disponible en:
https://rstudio-education.github.io/hopr/

Aprender a programar en R básico mediante ejemplos prácticos.

- R. Kabacoff. Data Visualization with R. 2018. Disponible en: https://rkabacoff.github.io/datavis/Models.html#SaratogaHouses

Visualización de datos con R.


# Recursos en internet

- [Cheatsheet de R](https://rstudio.com/resources/cheatsheets/)
