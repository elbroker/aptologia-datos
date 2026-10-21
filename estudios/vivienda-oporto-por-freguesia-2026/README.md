---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Vivienda en Oporto: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- porto
- rent
- price-per-square-metre
configs:
- config_name: vivienda_oporto_por_freguesia_2026_datos
  data_files: data/vivienda_oporto_por_freguesia_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-oporto-por-freguesia-2026

# Vivienda en Oporto: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)

La freguesia con el metro cuadrado más caro de Oporto es Aldoar, Foz do Douro e Nevogilde, con 7.240 euros (USD 8.138) en la mediana de apartamentos en venta; la más barata de la muestra es Ramalde, con 4.499 euros (USD 5.057). La rentabilidad bruta implícita del arriendo es 3,9 % anual.

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-oporto-por-freguesia-2026
- **Datos y avisos en Aptología:** [Aptología: arriendo y venta de vivienda](https://www.aptologia.com/)
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Housing in Porto (apartments, Oct 2026): sale USD 5820/m²; gross yield 3.9%. Source: Aptología, 2026-10-18.

## Archivos

- `vivienda-oporto-por-freguesia-2026.md`: estudio completo (markdown).
- `data/vivienda_oporto_por_freguesia_2026_datos.csv`
- `charts/m2-venta-freguesias.png`
- `charts/m2-venta-freguesias.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Vivienda en Oporto: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-oporto-por-freguesia-2026
