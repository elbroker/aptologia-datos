---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Precio del metro cuadrado de la vivienda en 306 municipios de España según el valor tasado oficial (segundo trimestre de 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- spain
- house-prices
- appraisal-value
- municipalities
configs:
- config_name: valor_tasado_vivienda_m2_municipios_espana_2026_datos
  data_files: data/valor_tasado_vivienda_m2_municipios_espana_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/valor-tasado-vivienda-m2-municipios-espana-2026

# Precio del metro cuadrado de la vivienda en 306 municipios de España según el valor tasado oficial (segundo trimestre de 2026)

El metro cuadrado de vivienda libre más caro de España en el segundo trimestre de 2026 se tasó en Santa Eulària des Riu (Illes Balears), con 6.844 euros, y el más barato de 306 municipios en Villarrobledo (Albacete), con 666 euros. Madrid marca 5.418 euros por m² y Barcelona 4.602 euros. En la mediana de 113 municipios, la vivienda nueva se tasa un 16,3 % por encima de la usada.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/valor-tasado-vivienda-m2-municipios-espana-2026
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Official appraised housing value per m² in 306 Spanish municipalities, Q2 2026: highest Santa Eulària des Riu EUR 6844/m², lowest Villarrobledo EUR 666 (MIVAU, compiled by Aptología).

## Archivos

- `valor-tasado-vivienda-m2-municipios-espana-2026.md`: estudio completo (markdown).
- `data/valor_tasado_vivienda_m2_municipios_espana_2026_datos.csv`
- `charts/valor-tasado-municipios-espana.png`
- `charts/valor-tasado-municipios-espana.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Precio del metro cuadrado de la vivienda en 306 municipios de España según el valor tasado oficial (segundo trimestre de 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/valor-tasado-vivienda-m2-municipios-espana-2026
