---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Cuánto varía el arriendo de un apartamento de 2 habitaciones dentro de cada ciudad de Colombia: rango normal en 21 ciudades (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- colombia
- rent-dispersion
- 2-bedroom-rent
- percentiles
configs:
- config_name: rango_de_precios_del_arriendo_2_habitaciones_ciudades_colombia_2026_datos
  data_files: data/rango_de_precios_del_arriendo_2_habitaciones_ciudades_colombia_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/rango-de-precios-del-arriendo-2-habitaciones-ciudades-colombia-2026

# Cuánto varía el arriendo de un apartamento de 2 habitaciones dentro de cada ciudad de Colombia: rango normal en 21 ciudades (octubre 2026)

En Bogotá el arriendo de un apartamento de 2 habitaciones caro típico (percentil 75) es 3,19 veces el barato típico (percentil 25), la mayor dispersión de 21 ciudades; en Sabaneta, solo 1,32 veces. En Bogotá la mitad central de la oferta de 2 habitaciones va de 1,60 millones de pesos a 5,09 millones de pesos al mes, y el 10 % más barato está por debajo de 1,25 millones de pesos.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/rango-de-precios-del-arriendo-2-habitaciones-ciudades-colombia-2026
- **Datos y avisos en Aptología:** [Aptología: arriendo y venta de vivienda](https://www.aptologia.com/)
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Dispersion of 2-bedroom rents in 21 Colombian cities: P75/P25 highest Bogotá (3.19x), lowest Sabaneta (1.32x); Bogotá IQR COP 1,596,000–5,095,000 (Aptología, 2026-10-18).

## Archivos

- `rango-de-precios-del-arriendo-2-habitaciones-ciudades-colombia-2026.md`: estudio completo (markdown).
- `data/rango_de_precios_del_arriendo_2_habitaciones_ciudades_colombia_2026_datos.csv`
- `charts/rango-arriendo-ciudades.png`
- `charts/rango-arriendo-ciudades.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Cuánto varía el arriendo de un apartamento de 2 habitaciones dentro de cada ciudad de Colombia: rango normal en 21 ciudades (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/rango-de-precios-del-arriendo-2-habitaciones-ciudades-colombia-2026
