---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Vivienda en Argentina por ciudad: precio por m², arriendo de 2 habitaciones y años de arriendo en 6 ciudades (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- argentina
- cities
- price-per-square-metre
configs:
- config_name: vivienda_argentina_por_ciudad_2026_datos
  data_files: data/vivienda_argentina_por_ciudad_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-argentina-por-ciudad-2026

# Vivienda en Argentina por ciudad: precio por m², arriendo de 2 habitaciones y años de arriendo en 6 ciudades (octubre 2026)

El metro cuadrado de apartamento más caro de Argentina está en Vicente López, con USD 3.600 en la mediana de avisos en venta; el más barato de las 6 ciudades medidas, en Córdoba, con USD 1.813. En Ciudad de Buenos Aires, un apartamento de 2 habitaciones se arrienda por USD 726 al mes y se vende por USD 160.000: 18,4 años de arriendo.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-argentina-por-ciudad-2026
- **Datos y avisos en Aptología:** [vivienda en Argentina en Aptología](https://www.aptologia.com/ar)
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Housing in Argentina by city (apartments, Oct 2026): most expensive Vicente López USD 3,600/m², cheapest Córdoba USD 1,813/m² (Aptología, 2026-10-18).

## Archivos

- `vivienda-argentina-por-ciudad-2026.md`: estudio completo (markdown).
- `data/vivienda_argentina_por_ciudad_2026_datos.csv`
- `charts/m2-ciudades-ar.png`
- `charts/m2-ciudades-ar.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Vivienda en Argentina por ciudad: precio por m², arriendo de 2 habitaciones y años de arriendo en 6 ciudades (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-argentina-por-ciudad-2026
