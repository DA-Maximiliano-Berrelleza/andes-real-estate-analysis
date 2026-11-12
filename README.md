# Andes Capital Real Estate | Desempeño comercial inmobiliario

Caso de estudio sobre ventas, ingresos y comportamiento de compra durante 2023–2024.

## Contexto y problema

La información transaccional de ventas, clientes y propiedades necesitaba una visión de conjunto para entender la evolución del negocio. Construí un dashboard en Power BI para identificar qué propiedades, canales y segmentos aportaron más ingresos y observar las compras posteriores a la primera compra registrada.

## Mi contribución

- **Validación de datos en Power Query.** Revisé tipos de datos, valores vacíos, errores y unicidad de las claves de clientes y propiedades.
- **Modelado en Power BI.** Organicé una tabla de ventas y tres dimensiones en un esquema estrella con relaciones activas de uno a muchos. Construí un calendario con un rango dinámico basado en las fechas de venta.
- **Cálculos DAX.** Desarrollé indicadores de ingresos, ventas, ticket promedio y comisiones, además de crecimiento interanual, participaciones y columnas calculadas para cohortes. Comprobé las participaciones de ingresos con el filtro de 2024.
- **Comunicación de resultados.** Diseñé tres vistas con navegación y selector de año. El resumen ejecutivo presenta los indicadores generales, el análisis comercial compara propiedades, canales y segmentos, y la matriz de cohortes muestra las transacciones por mes de primera compra y mes de venta.

## Resultados de 2024

| Indicador | Resultado |
| --- | ---: |
| Ingresos totales | 3,164,799,714.00 |
| Cantidad de ventas | 4,455 |
| Ticket promedio | 710,392.75 |
| Comisiones totales | 105,891,941.00 |
| Crecimiento de ingresos frente a 2023 | 11.14 % |

## Hallazgos y decisiones comerciales

- **Casa** aportó el **36.24 %** de los ingresos, la mayor participación entre los tipos de propiedad. El resultado respalda priorizar su comercialización.
- **Corredor** concentró el **72.89 %** de los ingresos. Antes de aumentar la inversión en ese canal, conviene revisar sus costos y su conversión.
- El segmento **Primera vez** aportó el **62.74 %** de los ingresos.
- En 2024 se registraron **482 ventas** entre los clientes de la cohorte de marzo de 2023 y **453** entre los de abril. Las cifras corresponden al número de transacciones. Para evaluar acciones de posventa, conviene comparar cohortes con el mismo tiempo de seguimiento.

## Documentación del proyecto

El notebook reúne las validaciones de datos, las fórmulas DAX, la descripción del modelo y los hallazgos. Los cálculos y las visualizaciones se ejecutan en Power BI.

[Ver el notebook y las fórmulas DAX en GitHub](./Andes_Portafolio.ipynb)

[Ver el dashboard de Power BI en PDF](./Andes_Dashboard.pdf)

[Consultar la copia en Colab](https://colab.research.google.com/drive/1DL2DzEfTRer2mO-rOrhhOSc5oSGnJ-Jr?usp=sharing)
