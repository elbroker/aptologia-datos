---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Vivienda en Quito: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- quito
- rent
- price-per-square-metre
configs:
- config_name: vivienda_quito_por_sector_2026_datos
  data_files: data/vivienda_quito_por_sector_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-quito-por-sector-2026

# Vivienda en Quito: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)

El sector con el metro cuadrado más caro de Quito es Cumbayá, con USD 1.578 en la mediana de departamentos en venta; el más barato de la muestra es Carcelén, con USD 642. Un departamento de 2 habitaciones se arrienda por USD 900 al mes en la mediana y se vende por USD 139.000. La rentabilidad bruta implícita del arriendo es 8,7 % anual.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-quito-por-sector-2026
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Housing in Quito (apartments, Oct 2026): sale USD 1000/m²; 2-bedroom rent USD 900/month; gross yield 8.7%. Source: Aptología, 2026-10-18.

## Archivos

- `vivienda-quito-por-sector-2026.md`: estudio completo (markdown).
- `data/vivienda_quito_por_sector_2026_datos.csv`
- `charts/m2-venta-sectores.png`
- `charts/m2-venta-sectores.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Vivienda en Quito: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-quito-por-sector-2026
