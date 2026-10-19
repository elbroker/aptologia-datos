# Vivienda en Caracas: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)

**La zona con el metro cuadrado más caro de Caracas es Chacao, con USD 2.472 en la mediana de apartamentos en venta; la más barata de la muestra es Sucre, con USD 1.000.** Un apartamento de 2 habitaciones se arrienda por USD 950 al mes en la mediana y se vende por USD 160.000. La rentabilidad bruta implícita del arriendo es 10,4 % anual.

*Resumen: analizamos 1.837 avisos de apartamentos en Caracas (1.503 en venta y 334 en arriendo).*

**Actualizado:** 18 de octubre de 2026 (datos del 18 de octubre de 2026) · **Próxima actualización:** mensual.

![Precio por m² por zona en Caracas](charts/m2-venta-zonas.png)

## Resumen

| Indicador | Valor |
|---|---|
| Más cara (venta por m²) | Chacao: USD 2.472 |
| Más barata (venta por m²) | Sucre: USD 1.000 |
| Venta por m² (mediana) | USD 1.400 |
| Arriendo 2 habitaciones | USD 950 |
| Rentabilidad bruta implícita | 10,4 % |
| Avisos | 1.837 |

## Zonas (30 avisos o más)

| Zona | Venta por m² (dólares) | Arriendo mensual (dólares) | Avisos (venta / arriendo) |
|---|---|---|---|
| Chacao | 2.472 | 1.475 | 238 / 82 |
| Baruta | 1.500 | 1.400 | 370 / 88 |
| El Hatillo | 1.341 | — | 184 / — |
| Libertador | 1.005 | — | 154 / — |
| Sucre | 1.000 | 900 | 126 / 39 |

Medianas de apartamentos; — indica menos de 30 avisos. El canon es mensual, sin administración ni gastos comunes.

## Precio por número de habitaciones

| Habitaciones | Precio de venta (mediana) | Arriendo mensual (mediana) | Avisos (venta / arriendo) |
|---|---|---|---|
| 1 | USD 240.260 | USD 1.000 | 103 / 65 |
| 2 | USD 160.000 | USD 950 | 300 / 80 |
| 3 o más | USD 250.000 | USD 1.875 | 1.094 / 184 |

## Preguntas frecuentes

**¿Cuál es la zona más cara de Caracas?**
Chacao, con USD 2.472 por m² en apartamentos en venta (octubre de 2026).

**¿Dónde es más barato comprar apartamento en Caracas?**
Entre las zonas con 30 avisos o más, en Sucre: USD 1.000 por m².

**¿Cuánto renta un apartamento en Caracas?**
La rentabilidad bruta implícita es 10,4 % anual (arriendo por m² × 12 ÷ precio de venta por m²), antes de gastos.

**¿Cuánto cuesta arrendar un apartamento de 2 habitaciones en Caracas?**
USD 950 al mes en la mediana (octubre de 2026).

## Metodología

- **Fuente:** exportes nocturnos de la base de datos de Aptología (aptologia.com) del 18 de octubre de 2026: avisos vigentes de vivienda en portales inmobiliarios de 13 países, recogidos por Aptología y vistos en línea entre el 11 y el 18 de octubre de 2026. Corte: 18 de octubre de 2026.
- **Depuración:** se eliminan duplicados exactos (misma ciudad, zona, tipo, precio, moneda, área, habitaciones y baños) y los precios fuera del percentil 1–99 de cada país, operación, moneda y tipo; el precio por m² usa solo avisos con área declarada entre 12 y 2.000 m² y también se recorta al P1–P99.
- **Qué se mide:** precios pedidos (publicados), no precios de cierre. En arriendo, el canon mensual sin administración, gastos comunes ni condominio.
- **Muestra mínima:** cada cifra publicada se apoya en al menos 30 avisos; las celdas con menos se omiten.
- **Monedas:** nunca se mezclan avisos de monedas distintas sin convertirlos. Conversión a dólares con la tasa de mercado de ExchangeRate-API (open.er-api.com, actualización del 18 Oct 2026): 1 USD = 3.182,80 COP, 1 USD = 18,47 M.N, 1 USD = 5,09 BRL, 1 USD = 3,44 PEN, 1 USD = 982,44 CLP, 1 USD = 1.514,57 ARS, 1 USD = 40,20 UYU, 1 USD = 5.705,37 PYG, 1 USD = 61,27 DOP, 1 USD = 0,89 EUR, 1 USD = 11,72 BOB; la UF chilena a 41.178,64 CLP (mindicador,cl. 18-oct-2026). Los avisos publicados en dólares se usan tal cual.
- **Monedas:** venta en dólares y arriendo en dólares, la moneda mayoritaria de cada operación; los avisos en otra moneda se excluyen. Equivalencias en dólares con la tasa citada.
- **Limitaciones:** la cobertura depende de los portales que recorre Aptología en cada país y es mayor en las ciudades grandes y en los segmentos medio-alto y alto; el área es la que declara el aviso, sin verificar; los nombres de zona vienen de los portales.
- **Privacidad:** solo se publican agregados; no se publica ningún dato personal, enlace a avisos ni nombre de anunciante.
- **Datos abiertos:** [datos.csv](datos.csv), licencia CC BY 4.0.

## Cómo citar

Pinzón Pineda, D. M. (2026). *Vivienda en Caracas: precio por m², arriendo, habitaciones y rentabilidad (octubre 2026)*. Aptología (aptologia.com). https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-caracas-por-zona-2026. Datos: datos.csv, licencia CC BY 4.0.
