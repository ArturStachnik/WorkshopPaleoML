# Machine learning y paleoclima

Material práctico del taller de la Red Paleonet. Granada, 2 a 4 de diciembre de 2026.

Los cuadernos se abren en Google Colab con el botón «Abrir en Colab» de cada uno. No hace
falta instalar nada ni escribir código.

| Sesión | Cuaderno | |
|---|---|---|
| 1 | [Primeros pasos en Colab](sesion_1/H1_primeros_pasos_colab.ipynb) | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ArturStachnik/WorkshopPaleoML/blob/main/sesion_1/H1_primeros_pasos_colab.ipynb) |
| 2 | [Del dato al modelo](sesion_2/H2_del_dato_al_modelo.ipynb) | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ArturStachnik/WorkshopPaleoML/blob/main/sesion_2/H2_del_dato_al_modelo.ipynb) |
| 3 | [Abrir la caja negra](sesion_3/H3_abrir_la_caja_negra.ipynb) | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ArturStachnik/WorkshopPaleoML/blob/main/sesion_3/H3_abrir_la_caja_negra.ipynb) |
| 4 | [Programar con IA](sesion_4/H4_programar_con_IA.ipynb) | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ArturStachnik/WorkshopPaleoML/blob/main/sesion_4/H4_programar_con_IA.ipynb) |

## Datos

| Fichero | Qué es |
|---|---|
| `datos/demo_colab.csv` | 300 muestras, temperatura del agua y tres especies. Para la sesión 1 |
| `datos/forams_sst.csv.gz` | 4205 sitios de sedimento superficial marino, 50 especies de foraminíferos planctónicos (fracciones que suman 1) y la temperatura media anual en superficie. Para las sesiones 2 y 3 |
| `datos/forams_sst_sucio.csv.gz` | El mismo conjunto con errores plantados a propósito, para la limpieza de la sesión 2 |
| `datos/polen_europa.csv.gz` | 99.774 muestras de polen fósil de 1.446 sondeos europeos, casi todos de lagos y turberas: sitio, edad, profundidad y porcentaje de los 30 taxones principales (el resto, en `otros`). Para la sesión 4, si no se traen datos propios |
| `datos/polen_europa_taxones.csv` | Nombre completo de cada columna de taxón de la tabla anterior |
| `datos/tierra_ne_110m.geojson` | Contorno de los continentes, Natural Earth 1:110m (dominio público) |
| `recursos/fuentes/` | DM Sans y DM Serif Display, la tipografía del taller (licencia OFL) |

Fuentes de `forams_sst.csv.gz`, las dos abiertas:

- Censos: Siccha, M. y Kucera, M. (2017). ForCenS, a curated database of planktonic
  foraminifera census counts in marine surface sediment samples. *Scientific Data* 4,
  170109. https://doi.org/10.1038/sdata.2017.109
- Temperatura: World Ocean Atlas 2023, NOAA NCEI, malla de 1°.

Fuente de `polen_europa.csv.gz`, abierta (CC BY 4.0):

- Li, C., Ni, J., Böhmer, T., Cao, X., Zhou, B., Liao, M., Li, K., Schild, L., Wieczorek, M.,
  Heim, B. y Herzschuh, U. (2025). LegacyPollen2.0: Taxonomically harmonized pollen percentages
  of European samples with revised chronologies. PANGAEA. https://doi.org/10.1594/PANGAEA.971693
- El tipo de archivo de cada sondeo sale de la tabla general de la misma colección:
  https://doi.org/10.1594/PANGAEA.971802
