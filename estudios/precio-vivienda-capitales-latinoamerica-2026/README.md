---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Precio de la vivienda en las capitales de Latinoamérica (y São Paulo y Lisboa): m² en venta, arriendo y rentabilidad (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- capital-cities
- house-prices
- rent
configs:
- config_name: precio_vivienda_capitales_latinoamerica_2026_datos
  data_files: data/precio_vivienda_capitales_latinoamerica_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-vivienda-capitales-latinoamerica-2026

# Precio de la vivienda en las capitales de Latinoamérica (y São Paulo y Lisboa): m² en venta, arriendo y rentabilidad (octubre 2026)

Entre las capitales de la región, el metro cuadrado en venta más caro es el de Lisboa (USD 8.383/m²) y el más barato el de Quito (USD 1.000/m²). Bogotá marca USD 2.282/m² en venta y USD 831 al mes por un apartamento de 2 habitaciones; la capital donde ese arriendo es más barato es La Paz (USD 506).

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-vivienda-capitales-latinoamerica-2026
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Housing prices in Latin American capitals: most expensive sale price per m² Lisboa (USD 8383), cheapest Quito (USD 1000); Bogotá USD 2282/m² (Aptología, 2026-10-18).

## Archivos

- `precio-vivienda-capitales-latinoamerica-2026.md`: estudio completo (markdown).
- `data/precio_vivienda_capitales_latinoamerica_2026_datos.csv`
- `charts/capitales-arriendo-2hab.png`
- `charts/capitales-venta-m2.png`
- `charts/capitales-arriendo-2hab.svg`
- `charts/capitales-venta-m2.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Precio de la vivienda en las capitales de Latinoamérica (y São Paulo y Lisboa): m² en venta, arriendo y rentabilidad (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-vivienda-capitales-latinoamerica-2026
