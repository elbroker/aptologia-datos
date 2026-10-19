---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Vivienda en Caracas: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- caracas
- rent
- price-per-square-metre
configs:
- config_name: vivienda_caracas_por_zona_2026_datos
  data_files: data/vivienda_caracas_por_zona_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-caracas-por-zona-2026

# Vivienda en Caracas: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)

La zona con el metro cuadrado más caro de Caracas es Chacao, con USD 2.472 en la mediana de apartamentos en venta; la más barata de la muestra es Sucre, con USD 1.000. Un apartamento de 2 habitaciones se arrienda por USD 950 al mes en la mediana y se vende por USD 160.000. La rentabilidad bruta implícita del arriendo es 10,4 % anual.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-caracas-por-zona-2026
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Housing in Caracas (apartments, Oct 2026): sale USD 1400/m²; 2-bedroom rent USD 950/month; gross yield 10.4%. Source: Aptología, 2026-10-18.

## Archivos

- `vivienda-caracas-por-zona-2026.md`: estudio completo (markdown).
- `data/vivienda_caracas_por_zona_2026_datos.csv`
- `charts/m2-venta-zonas.png`
- `charts/m2-venta-zonas.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Vivienda en Caracas: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-caracas-por-zona-2026
