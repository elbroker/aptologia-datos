---
license: cc-by-4.0
language:
- es
- en
pretty_name: "¿Vale más un apartamento en piso alto? Precio por m² según el piso en Colombia (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- colombia
- floor-level
- apartments
- price-per-square-metre
configs:
- config_name: precio_m2_segun_piso_apartamentos_colombia_2026_datos
  data_files: data/precio_m2_segun_piso_apartamentos_colombia_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-m2-segun-piso-apartamentos-colombia-2026

# ¿Vale más un apartamento en piso alto? Precio por m² según el piso en Colombia (octubre 2026)

Un apartamento del piso 11 en adelante se pide en Colombia un 20,8 % más caro por metro cuadrado que uno en pisos 1 y 2 de la misma ciudad y estrato. La comparación usa 56 combinaciones de ciudad y estrato con 30 avisos o más en cada grupo.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-m2-segun-piso-apartamentos-colombia-2026
- **Datos y avisos en Aptología:** [Aptología: arriendo y venta de vivienda](https://www.aptologia.com/)
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Apartments on floor 11+ in Colombia ask +20.8% per m² vs floors 1–2 in the same city and stratum (Aptología, 2026-10-18).

## Archivos

- `precio-m2-segun-piso-apartamentos-colombia-2026.md`: estudio completo (markdown).
- `data/precio_m2_segun_piso_apartamentos_colombia_2026_datos.csv`
- `charts/m2-por-piso.png`
- `charts/m2-por-piso.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *¿Vale más un apartamento en piso alto? Precio por m² según el piso en Colombia (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/precio-m2-segun-piso-apartamentos-colombia-2026
