# Proyecto 10 | Estrategia comercial de Andes Capital Real Estate (versión Tableau)

## Descripción del proyecto
Este proyecto presenta una versión desarrollada en **Tableau Public** del análisis comercial de **Andes Capital Real Estate**, orientada a fortalecer la lectura ejecutiva y el análisis estratégico del negocio inmobiliario entre **2023 y 2024**.

El trabajo se enfocó en construir una solución visual robusta para explorar el desempeño comercial desde múltiples dimensiones: evolución temporal, concentración de ingresos, segmentación por tipo de propiedad y canal de venta, estacionalidad y recurrencia de clientes. Esta versión profundiza el enfoque analítico del proyecto y consolida una presentación más sólida para portafolio profesional.

## Objetivo
Diseñar un dashboard ejecutivo y analítico que permita evaluar el desempeño comercial de **Andes Capital Real Estate** entre **2023 y 2024**, identificando patrones de ingreso, concentración comercial, crecimiento interanual y comportamiento de recompra de clientes.

## Preguntas del negocio
El dashboard fue diseñado para responder las siguientes preguntas:

- ¿Cuál es el ingreso total generado por las ventas de propiedades?
- ¿Qué tipo de propiedad genera más ingresos?
- ¿Qué segmentos de clientes compran más?
- ¿Cómo evolucionan las ventas en el tiempo?
- ¿El negocio está creciendo año contra año?
- ¿Los clientes vuelven a comprar después de su primera compra?

## KPIs analizados
- Ingreso Total
- Cantidad de Ventas
- Ticket Promedio
- Comisión Total
- Margen de Comisión
- Clientes Únicos
- Propiedades Vendidas
- Crecimiento interanual (YoY)

## Valor analítico del proyecto
Esta versión en Tableau permitió ampliar la profundidad del análisis comercial mediante:

- Una lectura ejecutiva del desempeño general del negocio
- Sgmentación por **tipo de propiedad**, **canal de venta** y **segmento comprador**
- Incorporación de la dimensión **estacional** para enriquecer el análisis temporal
- Análisis de **cohortes** para evaluar recurrencia y recompra de clientes
- Uso de métricas de **participación de ingresos** para identificar concentración comercial
- Construcción de una tabla de detalle con segmentación por **nivel de venta**, útil para profundizar combinaciones de ciudad, tipo de propiedad y valor de operación

## Nota metodológica
Dado que el dataset no incluía información de costos, no se construyó una métrica de ganancia en sentido contable. En su lugar, se trabajó con:

- **Comisión Total** como ingreso capturado por la inmobiliaria
- **Margen de Comisión** como indicador relativo sobre el valor total vendido

## Criterios de segmentación
La variable **Nivel de Venta** fue construida para clasificar las operaciones en **Bajo, Medio y Alto** según el valor de `Precio Venta`. Los rangos se definieron con base en la distribución del dataset, utilizando percentiles como referencia para establecer puntos de corte representativos y luego ajustándolos a valores redondeados para facilitar su interpretación en el dashboard.

## Dashboard interactivo

Puedes explorar la versión interactiva del dashboard en Tableau Public aquí: https://public.tableau.com/app/profile/dayana.rodriguez3078/viz/Poyecto10_Dayana_Rodriguez/Overview
> Nota: Si las vistas previas no se visualizan correctamente en GitHub, puedes acceder directamente al dashboard interactivo desde el enlace anterior.

El proyecto fue estructurado en tres vistas principales:

### 1. Overview Ejecutivo
Resume el desempeño general del negocio a través de KPIs, evolución mensual de ingresos, crecimiento interanual y concentración geográfica del ingreso.

### 2. Análisis Comercial
Profundiza en la composición del negocio mediante segmentación por tipo de propiedad, canal de venta, segmento comprador, estacionalidad y nivel de venta.

### 3. Análisis de Cohorte
Evalúa la recurrencia de clientes mediante una matriz de cohortes, permitiendo identificar el comportamiento de recompra posterior a la primera adquisición.

## Principales insights
- **Ciudad de México** lidera la generación de ingresos por ventas de propiedades, evidenciando concentración del negocio en este mercado.
- El canal **Corredor** concentra la mayor parte del ingreso, especialmente en el segmento **Primera vez**.
- Las propiedades tipo **Casa** generan los mayores ingresos, con mejor desempeño en **Primavera** y **Otoño**.
- La evolución mensual de ingresos presenta fluctuaciones, aunque con una tendencia general creciente.
- El negocio muestra un **crecimiento interanual positivo**, aunque con concentración en ciudades, segmentos y canales específicos.
- La recompra se concentra en el **mes inicial**, con una disminución sostenida en los meses posteriores, lo que evidencia oportunidades claras de retención.

## Herramientas utilizadas
- Tableau Public
- Cálculos LOD (`FIXED`)
- Cálculos de tabla
- Segmentación por percentiles
- Análisis de cohortes
- Storytelling ejecutivo


