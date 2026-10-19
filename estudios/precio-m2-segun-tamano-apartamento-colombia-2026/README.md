---
license: cc-by-4.0
language:
- es
- en
pretty_name: "¿Sale más barato el metro cuadrado de un apartamento grande? Precio por m² según el tamaño en Colombia (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- colombia
- apartment-size
- price-per-square-metre
configs:
- config_name: precio_m2_segun_tamano_apartamento_colombia_2026_datos
  data_files: data/precio_m2_segun_tamano_apartamento_colombia_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-m2-segun-tamano-apartamento-colombia-2026

# ¿Sale más barato el metro cuadrado de un apartamento grande? Precio por m² según el tamaño en Colombia (octubre 2026)

En Colombia el metro cuadrado de un apartamento en venta de menos de 50 m² se pide en 6,43 millones de pesos en la mediana y el de uno de 200 m² o más en 6,96 millones de pesos; el tramo más caro por m² es el de 200 m² o más (6,96 millones de pesos). El precio por m² no baja de forma pareja con el tamaño: los apartamentos grandes se concentran en barrios y estratos altos, lo que compensa el descuento por tamaño.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-m2-segun-tamano-apartamento-colombia-2026
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Asking price per m² by apartment size in Colombia: <50 m² COP 6428571/m², 200+ m² COP 6956522/m²; most expensive band 200 m² o más (Aptología, 2026-10-18).

## Archivos

- `precio-m2-segun-tamano-apartamento-colombia-2026.md`: estudio completo (markdown).
- `data/precio_m2_segun_tamano_apartamento_colombia_2026_datos.csv`
- `charts/m2-segun-tamano-colombia.png`
- `charts/m2-segun-tamano-colombia.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *¿Sale más barato el metro cuadrado de un apartamento grande? Precio por m² según el tamaño en Colombia (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-m2-segun-tamano-apartamento-colombia-2026
