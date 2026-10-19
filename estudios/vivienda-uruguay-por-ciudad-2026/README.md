---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Vivienda en Uruguay por ciudad: precio por m², arriendo de 2 habitaciones y años de arriendo en 3 ciudades (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- uruguay
- cities
- price-per-square-metre
configs:
- config_name: vivienda_uruguay_por_ciudad_2026_datos
  data_files: data/vivienda_uruguay_por_ciudad_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-uruguay-por-ciudad-2026

# Vivienda en Uruguay por ciudad: precio por m², arriendo de 2 habitaciones y años de arriendo en 3 ciudades (octubre 2026)

El metro cuadrado de apartamento más caro de Uruguay está en Punta del Este, con USD 3.604 en la mediana de avisos en venta; el más barato de las 3 ciudades medidas, en Maldonado, con USD 2.497. En Montevideo, un apartamento de 2 habitaciones se arrienda por USD 826 al mes y se vende por USD 203.500: 20,5 años de arriendo.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-uruguay-por-ciudad-2026
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Housing in Uruguay by city (apartments, Oct 2026): most expensive Punta del Este USD 3,604/m², cheapest Maldonado USD 2,497/m² (Aptología, 2026-10-18).

## Archivos

- `vivienda-uruguay-por-ciudad-2026.md`: estudio completo (markdown).
- `data/vivienda_uruguay_por_ciudad_2026_datos.csv`
- `charts/m2-ciudades-uy.png`
- `charts/m2-ciudades-uy.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Vivienda en Uruguay por ciudad: precio por m², arriendo de 2 habitaciones y años de arriendo en 3 ciudades (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-uruguay-por-ciudad-2026
