# Machine learning y paleoclima

Material práctico del taller de la Red Paleonet. Granada, 2 a 4 de diciembre de 2026.

Los cuadernos se abren en Google Colab con el botón «Abrir en Colab» de cada uno. No hace
falta instalar nada ni escribir código.

| Sesión | Cuaderno | |
|---|---|---|
| 1 | [Primeros pasos en Colab](sesion_1/H1_primeros_pasos_colab.ipynb) | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ArturStachnik/WorkshopPaleoML/blob/main/sesion_1/H1_primeros_pasos_colab.ipynb) |

## Datos

| Fichero | Qué es |
|---|---|
| `datos/demo_colab.csv` | 300 muestras, temperatura del agua y tres especies. Para la sesión 1 |
| `datos/forams_sst.csv.gz` | 4205 sitios de sedimento superficial marino, 50 especies de foraminíferos planctónicos (fracciones que suman 1) y la temperatura media anual en superficie |

Fuentes de `forams_sst.csv.gz`, las dos abiertas:

- Censos: Siccha, M. y Kucera, M. (2017). ForCenS, a curated database of planktonic
  foraminifera census counts in marine surface sediment samples. *Scientific Data* 4,
  170109. https://doi.org/10.1038/sdata.2017.109
- Temperatura: World Ocean Atlas 2023, NOAA NCEI, malla de 1°.
