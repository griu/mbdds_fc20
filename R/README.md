
# ANEXO: README DE R

### CLONAR EL PROYETO GITHUB EN LOCAL

Abrimos una línea de comandos (`cmd` o `anaconda` en Windows, `terminal` en Linux).

```
git clone https://github.com/griu/mbdds_fc20.git
```

### PREPARACIÓN ENTORNO RSTUDIO

#### CREAR EL PROYECTO

Crea un nuevo proyecto de RStudio sobre tu directorio local. 

`File > New Project > Existing Directory > mbdds_fc20 > OK`

El nuevo proyecto ya está conectado a Git.

#### INSTALAR PACKAGES DES DE R

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
