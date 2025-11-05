# Hyperbolic Tree - Evolución de la Expectativa de Vida Global (1900-2023)

## 📊 Descripción del Proyecto

Este repositorio complementa las visualizaciones principales de expectativa de vida publicadas en **Tableau Public** con un Hyperbolic Tree que no puede ser publicado directamente por ser una extensión de terceros.

### 🔗 Visualizaciones Principales en Tableau Public

Incluye:
- **Diagrama Alluvial** - Evolución por períodos (1900-2023) - https://public.tableau.com/app/profile/fabian.lopez2805/viz/PEC2AlluvialFabianLopez/AlluvialDiagram?publish=yes
- **Diagrama Sankey** - Flujo continuo de regiones - https://public.tableau.com/app/profile/fabian.lopez2805/viz/PEC2FabianLopez/SankeyDiagram?publish=yes


## 🌳 Hyperbolic Tree - Años Ganados por Región y País

Árbol jerárquico que muestra la distribución de años ganados en expectativa de vida organizado en tres niveles:

**Estructura jerárquica:**
- **Centro (Mundo):** Promedio global de años ganados
- **Nivel 2 (Regiones):** 11 regiones mundiales (África, Asia del Sur, Europa del Este, etc.)
- **Nivel 3 (Países):** ~200 países individuales

**Métrica visualizada:** Total de años ganados en expectativa de vida desde 1900 hasta 2023


*Hyperbolic Tree mostrando la jerarquía Mundo → Regiones → Países con años ganados en expectativa de vida*
<img width="1219" height="828" alt="image" src="https://github.com/user-attachments/assets/aa8c1adf-aabb-4d84-b9c2-f53766001429" />



## 📁 Estructura del Repositorio

```
├── README.md                  # Este archivo
├── images/
│   └── hyperbolic_tree.png   # Visualización del Hyperbolic Tree
├── data/
│   └── life-expectancy.csv   # Dataset utilizado
└── tableau/
    └── expectativa_vida.twbx # Archivo Tableau completo (incluye todas las visualizaciones)
```

---

## 📊 Datos Utilizados

**Fuente:** https://ourworldindata.org/grapher/life-expectancy?overlay=download-data

**Dataset:** `life-expectancy.csv`

**Campos principales:**
- `Entity`: País
- `Code`: Código del país
- `Year`: Año
- `Life expectancy`: Expectativa de vida en años
- `Region`: Región geográfica
- `Calculated Life Expectancy`: Expectativa de vida calculada

**Período temporal:** 1900-2023

**Cobertura geográfica:** 
- 11 regiones mundiales
- ~200 países

---

## 🛠️ Herramientas Utilizadas

- **Tableau Public** - Visualizaciones principales (Alluvial, Sankey, Dashboard)
- **Tableau Desktop** - Hyperbolic Tree (extensión LaDataViz Tree Diagram)

---

## 📈 Cálculo de Años Ganados

El tamaño de cada nodo en el Hyperbolic Tree representa el total de años ganados en expectativa de vida:

```
Años Ganados (por país) = Expectativa de vida (2023) - Expectativa de vida (1900)
```

**Para regiones y el nodo mundial:**
- Los valores se agregan sumando los años ganados de todos los países de cada región
- Permite comparar el impacto total entre regiones

---

## 🎓 Contexto Académico

Este proyecto fue desarrollado como parte de [Nombre de la materia/curso] del [Nombre del programa de maestría] en [Universidad].

**Autor:** Fabián López  
**Fecha:** Noviembre 2025  
**Curso:** Visualización de Datos

---

## 📝 Sobre el Hyperbolic Tree

El Hyperbolic Tree no puede publicarse en Tableau Public debido a que utiliza una extensión de terceros (LaDataViz Tree Diagram). Esta visualización complementa el análisis mostrando la distribución jerárquica de años ganados en expectativa de vida.

**¿Por qué usar un Hyperbolic Tree?**
- Permite visualizar grandes cantidades de datos jerárquicos de forma compacta
- Muestra la relación entre regiones y países individuales
- El tamaño de los nodos representa los años ganados en cada entidad

---

## 📧 Contacto

Para preguntas o comentarios sobre este proyecto:
- **Email:** flopezcardozo@uoc.edu
- **GitHub:** flopezcardozo

---

## ⚠️ Nota Importante

**Tableau Public no permite publicar visualizaciones que usan extensiones de terceros.** Por esta razón, el Hyperbolic Tree se incluye aquí como imagen estática.

Para explorar la visualización completa en Tableau Desktop:
1. Descarga el archivo `expectativa_vida.twbx` de la carpeta `tableau/`
2. Ábrelo en Tableau Desktop (versión gratuita disponible)
3. La extensión Tree Diagram se cargará automáticamente

**Las demás visualizaciones (Alluvial, Sankey, etc.) están disponibles de forma interactiva en Tableau Public** 👆

