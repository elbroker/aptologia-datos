---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Cuánto varía el precio del metro cuadrado dentro de cada ciudad de Colombia: dispersión en 37 ciudades (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- colombia
- price-dispersion
- price-per-square-metre
- housing-market
configs:
- config_name: dispersion_del_precio_m2_ciudades_colombia_2026_datos
  data_files: data/dispersion_del_precio_m2_ciudades_colombia_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/dispersion-del-precio-m2-ciudades-colombia-2026

# Cuánto varía el precio del metro cuadrado dentro de cada ciudad de Colombia: dispersión en 37 ciudades (octubre 2026)

En Santa Marta el metro cuadrado del apartamento caro típico (percentil 75) cuesta 1,93 veces el del barato típico (percentil 25), la mayor dispersión de 37 ciudades colombianas; en Tocancipá la relación es de solo 1,18. En Bogotá el rango va de 5,81 millones de pesos a 9,19 millones de pesos por m² (1,58 veces). Una dispersión alta indica que el barrio y el estrato pesan más en el precio.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/dispersion-del-precio-m2-ciudades-colombia-2026
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Dispersion of apartment asking price per m² in 37 Colombian cities: P75/P25 highest in Santa Marta (1.93x), lowest in Tocancipá (1.18x) (Aptología, 2026-10-18).

## Archivos

- `dispersion-del-precio-m2-ciudades-colombia-2026.md`: estudio completo (markdown).
- `data/dispersion_del_precio_m2_ciudades_colombia_2026_datos.csv`
- `charts/dispersion-m2-ciudades.png`
- `charts/dispersion-m2-ciudades.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Cuánto varía el precio del metro cuadrado dentro de cada ciudad de Colombia: dispersión en 37 ciudades (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/dispersion-del-precio-m2-ciudades-colombia-2026
