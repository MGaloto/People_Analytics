<p align="left">
<img src="https://img2.freepng.es/20190618/yhi/kisspng-logo-movistar-brand-trademark-product-rstudio-icon-free-of-papirus-apps-5d08d887815bb1.5167350915608608075299.jpg" alt="react" width="25" height="25" />
<img src="https://tidyverse.tidyverse.org/logo.png" alt="react" width="25" height="25" />
<img src="https://jkunst.com/highcharter/logo.png" alt="react" width="25" height="25" />
<img src="https://www.anabellelaurent.com/slides/datawrangling_tallerr_ecuador/images/dplyr.png" alt="react" width="25" height="25" />
<img src="https://dtyoc.files.wordpress.com/2015/11/plotly-logo.png" alt="react" width="25" height="25" />
<img src="https://pkgs.rstudio.com/flexdashboard/reference/figures/logo.png" alt="react" width="25" height="25" />
</p>




# People_Analytics

<a href="https://pkgs.rstudio.com/flexdashboard/" rel="nofollow"><img src="https://raw.githubusercontent.com/rstudio/hex-stickers/master/PNG/flexdashboard.png" align="right" width="150" style="max-width: 100%;"></a>

Proyecto Final

Se analizan dos variables: Ausentismo y Horas Extras de una empresa X

Las conclusiones del trabajo se encuentran en el dashboard:

https://rpubs.com/MGaloto/People_Analytics


# Incluye

<ui>
<li>
Estadística Descriptiva
</li>
<li>
Visualizacion
</li>
</ui>


# Paquetes de R

<ui>

<li>
{plotly}
</li>
<li>
{gganimate}
</li>
<li>
{tidyverse}
</li>
</ui>


# Motivación

Como su nombre lo indica, el paquete flexdashboard proporciona un marco flexible para crear tableros. Es parte del ecosistema Rmarkdown y tiene las siguientes características:

- Simple
- Establezca el diseño del tablero con el uso de formato de filas y columnas
- Personalice el tema del tablero usando CSS o el paquete bslib
- Use widgets integrados, como cuadros de valor y medidores
- Cree paneles interactivos (y sin servidor) aprovechando las herramientas de visualización de datos de R (p. ej., Plotly, highcharter, dychart, prospecto, etc.), tablas (gt, reactable, reactablefrm, kable, etc.) y - herramientas htmlwidges como crosstalk.
- Cree tableros dinámicos con Shiny

Mediante un tablero de esta naturaleza se pueden presentar trabajos de agregacion de grandes volumenes de datos y explicar, mediante la visualizacion, gran parte de la informacion oculta que tienen los datos. 

En este trabajo en particular se hace un analisis sobre la relacion de ausentismo y horas extra por departamento en una empresa X. 


```r
---
title: "People Analytics"
output: 
  flexdashboard::flex_dashboard:
    orientation: columns
    vertical_layout: fill
    theme: cosmo
    logo: favicon_48x48.png
    favicon: favicon_48x48.png
---
```


## Dash Final

![.](plot/dash.png)

