# Precio de casas en venta en Montevideo por número de dormitorios: cuánto cuesta cada tamaño (octubre 2026)

**En Montevideo, una casa de 1 dormitorio cuesta USD 115.000 en la mediana, una de 2 dormitorios USD 140.000 (+21,7 %) y una de 3 o más USD 350.000 (+150,0 %).**

*Resumen: analizamos 3.257 avisos de casas en venta en Montevideo con número de dormitorios declarado.*

**Actualizado:** 18 de octubre de 2026 (datos del 18 de octubre de 2026) · **Próxima actualización:** mensual.

![Precio por número de dormitorios en Montevideo](charts/precio-por-habitaciones.png)

## Resumen

| Indicador | Valor |
|---|---|
| 1 dormitorio | USD 115.000 |
| 2 dormitorios | USD 140.000 |
| 3 o más dormitorios | USD 350.000 |
| Avisos | 3.257 |

## Precio por número de dormitorios

| Tipo | Precio (mediana) | Rango típico (P25–P75) | Área mediana (m²) | Por m² (mediana) | Avisos |
|---|---|---|---|---|---|
| 1 dormitorio | USD 115.000 | USD 88.000 – USD 161.000 | 58 | USD 1.992 | 67 |
| 2 dormitorios | USD 140.000 | USD 99.000 – USD 215.000 | 93 | USD 1.566 | 669 |
| 3 o más dormitorios | USD 350.000 | USD 190.000 – USD 650.000 | 226 | USD 1.630 | 2.521 |

Medianas del precio pedido; el rango típico va del percentil 25 al 75.

## Preguntas frecuentes

**¿Cuánto cuesta comprar una casa de 2 dormitorios en Montevideo?**
USD 140.000 en la mediana (octubre de 2026); la mitad central de la oferta está entre USD 99.000 y USD 215.000.

**¿Y una de 3 o más dormitorios?**
USD 350.000 en la mediana.

## Metodología

- **Fuente:** exportes nocturnos de la base de datos de Aptología (aptologia.com) del 18 de octubre de 2026: avisos vigentes de vivienda en portales inmobiliarios de 13 países, recogidos por Aptología y vistos en línea entre el 11 y el 18 de octubre de 2026. Corte: 18 de octubre de 2026.
- **Depuración:** se eliminan duplicados exactos (misma ciudad, zona, tipo, precio, moneda, área, habitaciones y baños) y los precios fuera del percentil 1–99 de cada país, operación, moneda y tipo; el precio por m² usa solo avisos con área declarada entre 12 y 2.000 m² y también se recorta al P1–P99.
- **Qué se mide:** precios pedidos (publicados), no precios de cierre. En arriendo, el canon mensual sin administración, gastos comunes ni condominio.
- **Muestra mínima:** cada cifra publicada se apoya en al menos 30 avisos; las celdas con menos se omiten.
- **Monedas:** nunca se mezclan avisos de monedas distintas sin convertirlos. Conversión a dólares con la tasa de mercado de ExchangeRate-API (open.er-api.com, actualización del 18 Oct 2026): 1 USD = 3.182,80 COP, 1 USD = 18,47 M.N, 1 USD = 5,09 BRL, 1 USD = 3,44 PEN, 1 USD = 982,44 CLP, 1 USD = 1.514,57 ARS, 1 USD = 40,20 UYU, 1 USD = 5.705,37 PYG, 1 USD = 61,27 DOP, 1 USD = 0,89 EUR, 1 USD = 11,72 BOB; la UF chilena a 41.178,64 CLP (mindicador,cl. 18-oct-2026). Los avisos publicados en dólares se usan tal cual.
- **Monedas:** en cada ciudad y operación se usa solo la moneda mayoritaria de los avisos (los avisos en otra moneda se excluyen) y la mediana se convierte a dólares con la tasa citada; nunca se promedian avisos de monedas distintas.
- **Cordura:** solo se publica si la mediana crece de 1 a 2 y de 2 a 3 o más dormitorios.
- **Limitaciones:** la cobertura depende de los portales que recorre Aptología en cada país y es mayor en las ciudades grandes y en los segmentos medio-alto y alto; el área es la que declara el aviso, sin verificar; los nombres de zona vienen de los portales.
- **Privacidad:** solo se publican agregados; no se publica ningún dato personal, enlace a avisos ni nombre de anunciante.
- **Datos abiertos:** [datos.csv](datos.csv), licencia CC BY 4.0.

## Cómo citar

Pinzón Pineda, D. M. (2026). *Precio de casas en venta en Montevideo por número de dormitorios: cuánto cuesta cada tamaño (octubre 2026)*. Aptología (aptologia.com). https://github.com/elbroker/aptologia-datos/tree/main/estudios/casas-en-venta-por-numero-de-dormitorios-montevideo-2026. Datos: datos.csv, licencia CC BY 4.0.
