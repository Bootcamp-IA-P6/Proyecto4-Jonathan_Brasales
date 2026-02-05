# Proyecto 3 - Jonathan Brasales
# Parte 1

## Fase 0 – Definición del problema analítico
**Enfoque elegido:** Evolución global de la energía renovable.

**Justificación:**
La evolución temporal de la energía renovable permite evaluar el avance real de la transición energética, identificar cambios de ritmo y extraer conclusiones relevantes para la toma de decisiones estratégicas.

**Historia a contar:**
Analizar cómo ha cambiado la producción/consumo de energía renovable a lo largo del tiempo, detectando tendencias, puntos de inflexión y posibles periodos de estancamiento.

**Preguntas clave:**
1. ¿Cómo ha evolucionado la energía renovable a nivel global?
2. ¿Existen periodos de crecimiento acelerado?
3. ¿Se observan cambios de tendencia?


**Dataset elegido:** Share of final energy use that comes from renewable sources — Our World in Data (CSV)

**Fuente:** Our World in Data presenta datos globales de energía, incluyendo métricas de participación de energías renovables en el consumo total de energía.

**URL de descarga propuesta:**
- https://archive.ourworldindata.org/20260130-180113/grapher/share-of-final-energy-consumption-from-renewable-sources.html

## Simplicidad de la base de datos 

```
|    | Year | renewable_share | annual_change | annual_growth_pct |
|----|------|-----------------|---------------|-------------------|
| 0  | 2000 | 15.71           | NaN           | NaN               |
| 1  | 2001 | 15.41           | -0.30         | -1.909612         |
| 2  | 2002 | 15.38           | -0.03         | -0.194679         |
| 3  | 2003 | 15.21           | -0.17         | -1.105332         |
| 4  | 2004 | 14.93           | -0.28         | -1.840894         |
| 5  | 2005 | 14.83           | -0.10         | -0.669792         |
| 6  | 2006 | 14.87           | 0.04          | 0.269724          |
| 7  | 2007 | 14.70           | -0.17         | -1.143241         |
| 8  | 2008 | 14.82           | 0.12          | 0.816327          |
| 9  | 2009 | 15.22           | 0.40          | 2.699055          |
| 10 | 2010 | 14.91           | -0.31         | -2.036794         |
| 11 | 2011 | 14.88           | -0.03         | -0.201207         |
| 12 | 2012 | 15.14           | 0.26          | 1.747312          |
| 13 | 2013 | 15.43           | 0.29          | 1.915456          |
| 14 | 2014 | 15.57           | 0.14          | 0.907323          |
| 15 | 2015 | 15.60           | 0.03          | 0.192678          |
| 16 | 2016 | 15.83           | 0.23          | 1.474359          |
| 17 | 2017 | 16.03           | 0.20          | 1.263424          |
| 18 | 2018 | 16.28           | 0.25          | 1.559576          |
| 19 | 2019 | 16.62           | 0.34          | 2.088452          |
| 20 | 2020 | 17.88           | 1.26          | 7.581227          |
| 21 | 2021 | 17.57           | -0.31         | -1.733781         |
| 22 | 2022 | 17.90           | 0.33          | 1.878201          |

```

## Gráficas

**¿A qué ritmo avanza la transición energética?**
![imagen 1](/assets/image.png)
1. [Barras cerca de 0 → transición lenta] ; [Barras grandes → aceleración] ; [Barras negativas → retrocesos] : La transición energética avanza, pero a un ritmo generalmente moderado, con aceleraciones puntuales
2. Este gráfico no mide volumen, sino velocidad. El pico de 2020 indica un cambio excepcional en el ritmo, no necesariamente estructural.

**¿La energía renovable está creciendo a nivel global?**
![imagen 2](/assets/image-1.png)

**Contexto:** Este gráfico muestra la evolución de la proporción de energía renovable en el consumo final global.
**Tendencia:** A largo plazo se observa una tendencia creciente.
**Matiz importante:** El crecimiento no es lineal y presenta periodos de estancamiento.



## Insights clave

- Existe una tendencia creciente a largo plazo en el uso de energías renovables.
- El ritmo de crecimiento ha sido generalmente lento, con periodos de estancamiento.
- El año 2020 representa un evento atípico que debe interpretarse con cautela.

## Conclusiones ejecutivas

La transición hacia energías renovables está en marcha, pero su ritmo actual sugiere que aún existe un amplio margen de mejora para alcanzar los objetivos energéticos y climáticos a largo plazo.

La participación de energías renovables tiene un avance gradual y moderado con un incremento de ~2.2 puntos porcentuales en 22 años.

El fuerte incremento observado en 2020 parece responder a contexto excepcional como el confinamiento y no a un cambio estructural consolidado.

La energía renovable ha aumentado su participación en el consumo global en las últimas dos décadas, pero lo ha hecho de forma lenta y no lineal. Durante muchos años el crecimiento fue prácticamente plano, con una aceleración clara a partir de la década de 2010. El año 2020 destaca como un evento excepcional, seguido de una corrección, lo que sugiere que la transición energética requiere esfuerzos sostenidos para consolidarse

---
# Parte 2

## Contexto y objetivo --
## Descripción del dataset por tipo de energía
## Evolución temporal individual
## Comparación de tasas de crecimiento
## Cambio en la composición del mix
## Insights estructurales
## Conclusiones estratégicas