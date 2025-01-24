# Does_Money_Buy_Happiness

### Descripción del proyecto:
El proyecto **"Does_Money_Buy_Happiness"** tiene como objetivo analizar si existe una relación entre el dinero (medido por el Producto Interno Bruto, GDP) y la felicidad de los países. Para ello, se compararon los datos de felicidad, que provienen del _World Happiness Report 2022_, con los datos del GDP de _The World Bank 2020_. Se utilizó un modelo de regresión lineal simple para intentar encontrar esa conexión.

### Variables en la base de datos:
- **Pais**: El nombre del país.
- **Felicidad**: Nivel de felicidad medido en una escala de 0 a 10, según el World Happiness Report 2022.
- **GDP**: Producto Interno Bruto (en términos monetarios) de cada país, correspondiente al año 2020.

### Metodología:
Primero, se cargaron los datos de felicidad y GDP de diversos países. Después, se realizó una visualización gráfica de estos datos para identificar patrones y observar cómo se relacionan. Dado que los valores del GDP son considerablemente altos, se aplicó una **transformación logarítmica (base 10)** para facilitar la interpretación. Luego, se calcularon métricas clave como el **Error Estándar y el Intervalo de Confianza**, que proporcionan información sobre la precisión de las estimaciones. Por último, se evaluó la significancia de la relación entre el GDP y la felicidad mediante pruebas estadísticas.

### Documentos incluídos en el proyecto:
- [Reporte en formato ipynb](./Does_Money_Buy_Happiness.ipynb)
- [Reporte en formato html](./Does_Money_Buy_Happiness.html)
- [Base de datos](./Felicidad_vs_GDP.csv)
