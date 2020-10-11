
# Ideas clave

<br>

- R cubre todo el espectro de trabajo con datos.
- Es un lenguaje rápido de implementar y de ejecución óptima.
- Aporta una gran facilidad para la visualización de datos.

<br>

# Anexo: Readme de R

<br>

#### CLONAR EL PROYETO GITHUB EN LOCAL

<br>

Abrimos una línea de comandos (`cmd` o `anaconda` en Windows, `terminal` en Linux).

<br>

```
git clone https://github.com/griu/mbdds_fc20.git
```

<br>

#### PREPARACIÓN ENTORNO RSTUDIO

<br>

##### CREAR EL PROYECTO

<br>

Crea un nuevo proyecto de RStudio sobre tu directorio local. 

`File > New Project > Existing Directory > mbdds_fc20 > OK`

El nuevo proyecto ya está conectado a Git.

<br>

##### INSTALAR PACKAGES DES DE R

<br>

En el entorno de Linux, (no Windows) es necesario haber instalado des del terminal los siguientes paquetes: `libxml2-dev`, `libssl-dev`, `libcurl4-openssl-dev` y `libmagick++-dev` .

Instala de uno en uno los siguientes paquetes desde la consola de RStudio.

<br>

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

<br>

# Bibliografía

<br>

- Y. Xie, J. J. Allaire, G. Grolemund. R Markdown: The Definitive Guide. Chapman & Hall/CRC; 2020. Disponible en: https://bookdown.org/yihui/rmarkdown/

<br>

Guía para elaborar con Rmarkdown, documentos que combinan texto, análisis en R o Python con los resultados (tablas o gráficos).

<br>

- W. Chang. R Graphics Cookbook,  O’Reilly Media, Inc. 2nd ed.; 2020. Disponible en: https://r-graphics.org/

<br>

Desarrollo de gráficos con R.

<br>

- G. Grolemund, H. Wickham. R for Data Science.  O’Reilly; 2017. Disponible en: https://es.r4ds.hadley.nz/ (Castellano)

<br>

Aprender a cargar datos en R, escoger la estructura de datos óptima, transformarlos, visualizarlos y modelarlos.

<br>

- G. Grolemund. Hands-On Programming with R. O’Reilly; 2014. Disponible en:
https://rstudio-education.github.io/hopr/

<br>

Aprender a programar en R básico mediante ejemplos prácticos.

<br>

- R. Kabacoff. Data Visualization with R. 2018. Disponible en: https://rkabacoff.github.io/datavis/Models.html#SaratogaHouses

<br>

Visualización de datos con R.

<br>

# Recursos en internet

<br>

- Cheatsheet de R. Disponibles en:

https://rstudio.com/resources/cheatsheets/
