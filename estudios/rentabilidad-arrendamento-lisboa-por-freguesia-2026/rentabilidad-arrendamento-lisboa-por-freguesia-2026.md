# Rentabilidad del arriendo en Lisboa por freguesia: dónde rinde más comprar para arrendar (octubre 2026)

**En Lisboa, comprar un apartamento para arrendarlo rinde en la freguesia típica 3,3 % bruto al año: el precio pedido equivale a 30,0 años de arriendo. La freguesia con mayor rentabilidad bruta es Arroios (4,1 %) y la de menor, Lumiar (3,2 %).** Para toda la ciudad, con las medianas por m², la rentabilidad bruta implícita es 3,7 %.

*Resumen: comparamos el precio por m² de 485 apartamentos en venta con el canon por m² de 204 en arriendo en 5 freguesias de Lisboa.*

**Actualizado:** 18 de octubre de 2026 (datos del 18 de octubre de 2026) · **Próxima actualización:** mensual.

![Rentabilidad bruta por freguesia en Lisboa](charts/rentabilidad-freguesias.png)

## Resumen

| Indicador | Valor |
|---|---|
| Mayor rentabilidad | Arroios: 4,1 % |
| Menor rentabilidad | Lumiar: 3,2 % |
| Freguesia típica (mediana) | 3,3 % |
| Ciudad (medianas por m²) | 3,7 % |
| Freguesias comparadas | 5 |

## Rentabilidad bruta por freguesia

| Freguesia | Venta por m² (euros) | Arriendo por m² al mes (euros) | Rentabilidad bruta | Años de arriendo | Avisos (venta / arriendo) |
|---|---|---|---|---|---|
| Arroios | 6.939 | 23,65 | 4,1 % | 24,5 | 121 / 45 |
| Avenidas Novas | 8.950 | 26,52 | 3,6 % | 28,1 | 116 / 55 |
| São Domingos de Benfica | 7.177 | 19,94 | 3,3 % | 30,0 | 37 / 30 |
| Alvalade | 7.547 | 20,84 | 3,3 % | 30,2 | 54 / 38 |
| Lumiar | 7.136 | 18,86 | 3,2 % | 31,5 | 157 / 36 |

Ordenado de mayor a menor rentabilidad. Antes de administración, impuestos, vacancia y financiación.

## Preguntas frecuentes

**¿En qué freguesia de Lisboa rinde más comprar para arrendar?**
En Arroios, con 4,1 % bruto anual (24,5 años de arriendo), según avisos de octubre de 2026.

**¿Dónde rinde menos?**
En Lumiar: 3,2 % bruto anual (31,5 años de arriendo).

**¿Cuánto renta un apartamento en Lisboa?**
En la freguesia típica, 3,3 % bruto al año.

## Metodología

- **Fuente:** exportes nocturnos de la base de datos de Aptología (aptologia.com) del 18 de octubre de 2026: avisos vigentes de vivienda en portales inmobiliarios de 13 países, recogidos por Aptología y vistos en línea entre el 11 y el 18 de octubre de 2026. Corte: 18 de octubre de 2026.
- **Depuración:** se eliminan duplicados exactos (misma ciudad, zona, tipo, precio, moneda, área, habitaciones y baños) y los precios fuera del percentil 1–99 de cada país, operación, moneda y tipo; el precio por m² usa solo avisos con área declarada entre 12 y 2.000 m² y también se recorta al P1–P99.
- **Qué se mide:** precios pedidos (publicados), no precios de cierre. En arriendo, el canon mensual sin administración, gastos comunes ni condominio.
- **Muestra mínima:** cada cifra publicada se apoya en al menos 30 avisos; las celdas con menos se omiten.
- **Monedas:** nunca se mezclan avisos de monedas distintas sin convertirlos. Conversión a dólares con la tasa de mercado de ExchangeRate-API (open.er-api.com, actualización del 18 Oct 2026): 1 USD = 3.182,80 COP, 1 USD = 18,47 M.N, 1 USD = 5,09 BRL, 1 USD = 3,44 PEN, 1 USD = 982,44 CLP, 1 USD = 1.514,57 ARS, 1 USD = 40,20 UYU, 1 USD = 5.705,37 PYG, 1 USD = 61,27 DOP, 1 USD = 0,89 EUR, 1 USD = 11,72 BOB; la UF chilena a 41.178,64 CLP (mindicador,cl. 18-oct-2026). Los avisos publicados en dólares se usan tal cual.
- **Monedas:** en cada ciudad y operación se usa solo la moneda mayoritaria de los avisos (los avisos en otra moneda se excluyen) y la mediana se convierte a dólares con la tasa citada; nunca se promedian avisos de monedas distintas.
- **Años de arriendo para pagar la vivienda:** precio de venta mediano ÷ (canon mensual mediano × 12), entre avisos del mismo tipo y celda; es la relación precio/arriendo (price-to-rent ratio) y equivale a 100 ÷ rentabilidad bruta. No incluye administración, impuestos, vacancia, financiación ni valorización: es una referencia para comparar comprar con arrendar, no una recomendación de inversión.
- **Rentabilidad por freguesia:** canon mediano por m² × 12 ÷ precio de venta mediano por m² de apartamentos del mismo freguesia; solo freguesias con 30 avisos o más de venta y 30 o más de arriendo con área declarada. Usar el m² y no el precio total evita que el tamaño típico de cada freguesia sesgue la comparación.
- **Limitaciones:** la cobertura depende de los portales que recorre Aptología en cada país y es mayor en las ciudades grandes y en los segmentos medio-alto y alto; el área es la que declara el aviso, sin verificar; los nombres de zona vienen de los portales.
- **Privacidad:** solo se publican agregados; no se publica ningún dato personal, enlace a avisos ni nombre de anunciante.
- **Datos abiertos:** [datos.csv](datos.csv), licencia CC BY 4.0.

## Cómo citar

Pinzón Pineda, D. M. (2026). *Rentabilidad del arriendo en Lisboa por freguesia: dónde rinde más comprar para arrendar (octubre 2026)*. Aptología (aptologia.com). https://github.com/elbroker/aptologia-datos/tree/main/estudios/rentabilidad-arrendamento-lisboa-por-freguesia-2026. Datos: datos.csv, licencia CC BY 4.0.
