---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Cuánto cuesta comprar un apartamento de 1, 2 o 3 habitaciones en 12 capitales de Latinoamérica y Portugal, y cuánto vale cada habitación extra (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- apartment-prices
- bedrooms
- capital-cities
configs:
- config_name: precio_de_venta_por_habitaciones_capitales_latinoamerica_2026_datos
  data_files: data/precio_de_venta_por_habitaciones_capitales_latinoamerica_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-de-venta-por-habitaciones-capitales-latinoamerica-2026

# Cuánto cuesta comprar un apartamento de 1, 2 o 3 habitaciones en 12 capitales de Latinoamérica y Portugal, y cuánto vale cada habitación extra (octubre 2026)

Un apartamento de 2 habitaciones en venta se pide en USD 110.000 en La Paz (Bolivia), la más barata de 12 capitales, y en USD 685.691 en Lisboa (Portugal). Pasar de 1 a 2 habitaciones encarece la compra hasta USD 166.364 en Lisboa (Portugal); en Caracas (Venezuela) el de 1 habitación mediano es incluso más caro, porque se concentra en zonas de mayor precio.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-de-venta-por-habitaciones-capitales-latinoamerica-2026
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Median asking price of 2-bedroom apartments in 12 capitals: from USD 110,000 (La Paz (Bolivia)) to USD 685,691 (Lisboa (Portugal)) (Aptología, 2026-10-18).

## Archivos

- `precio-de-venta-por-habitaciones-capitales-latinoamerica-2026.md`: estudio completo (markdown).
- `data/precio_de_venta_por_habitaciones_capitales_latinoamerica_2026_datos.csv`
- `charts/venta-2hab-capitales.png`
- `charts/venta-2hab-capitales.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Cuánto cuesta comprar un apartamento de 1, 2 o 3 habitaciones en 12 capitales de Latinoamérica y Portugal, y cuánto vale cada habitación extra (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-de-venta-por-habitaciones-capitales-latinoamerica-2026
