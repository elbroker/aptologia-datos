---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Precio de la vivienda por barrio en Montevideo: venta y arriendo en 25 barrios (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- montevideo
- rent
- barrio
configs:
- config_name: precio_vivienda_montevideo_por_barrio_2026_datos
  data_files: data/precio_vivienda_montevideo_por_barrio_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-vivienda-montevideo-por-barrio-2026

# Precio de la vivienda por barrio en Montevideo: venta y arriendo en 25 barrios (octubre 2026)

El barrio con el metro cuadrado más caro de Montevideo es Puerto Buceo, con USD 4.169 en la mediana de apartamentos en venta; el más barato de la muestra es Unión, con USD 1.864. En arriendo, el canon mediano más alto se pide en Punta Carretas (38.500 pesos uruguayos (USD 958) al mes) y el más bajo en Unión (25.000 pesos uruguayos (USD 622)).

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-vivienda-montevideo-por-barrio-2026
- **Datos y avisos en Aptología:** [alquileres en Montevideo en Aptología](https://www.aptologia.com/uy/alquiler/montevideo)
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Median asking price per m² of apartments by barrio in Montevideo: highest Puerto Buceo USD 4169, lowest Unión USD 1864; highest rent Punta Carretas UYU 38500/month (Aptología, 2026-10-18).

## Archivos

- `precio-vivienda-montevideo-por-barrio-2026.md`: estudio completo (markdown).
- `data/precio_vivienda_montevideo_por_barrio_2026_datos.csv`
- `charts/m2-venta-barrios.png`
- `charts/m2-venta-barrios.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Precio de la vivienda por barrio en Montevideo: venta y arriendo en 25 barrios (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-vivienda-montevideo-por-barrio-2026
