# Proyecto de AB Testing: Optimización de Conversiones 📊

📖 Descripción

Este proyecto tiene como objetivo analizar si un cambio en el diseño de un Call To Action (CTA) en una página web impacta en la tasa de conversión de los usuarios. Se ha llevado a cabo un experimento de AB Testing comparando dos versiones:

Grupo A (Control): CTA en color azul (versión actual).

Grupo B (Test): CTA en color naranja (nueva versión).

El análisis se basa en pruebas estadísticas para determinar si la nueva versión mejora significativamente la conversión.

🗂️ **Estructura del Proyecto**

        /Proyecto_AB_Testing
        
        │
        
        ├── ab_testing.csv                  # Datos utilizados para la realización del trabajo.
        
        │
        
        ├── AAR_Proyecto AB Testing         # Jupyter Notebook con la realización y resolución del trabajo.
        
        │
        
        ├── /src/                           # Scripts para la manipulación de datos y pruebas estadísticas.
        
        │   ├── soporte_abtesting.py        # Funciones auxiliares para la ejecución del AB Testing.
        
        │   ├── soporte_visualizacion.py    # Funciones para generar visualizaciones de los resultados.
        
        │   ├── soporte_estadistico.py      # Implementación de pruebas estadísticas.
        
        │   └── config.py                   # Configuración del proyecto.


🛠️ **Instalación y Requisitos**

Este proyecto utiliza Python y requiere las siguientes librerías:

        pip install pandas numpy seaborn matplotlib statsmodels scipy

🔬 **Metodología**

Carga y limpieza de datos: Preparación del dataset para análisis.

Exploración y análisis de tasas de conversión: Comparación visual entre los grupos A y B.

Aplicación del Z-Test: Evaluación estadística de la diferencia entre las conversiones.

Evaluación del p-valor: Toma de decisiones basada en la significancia estadística.

📊 **Resultados y Conclusiones**

El test estadístico determinará si el cambio de color del CTA impacta significativamente la conversión. Los resultados pueden consultarse en los notebooks y visualizaciones generadas.

🔄 **Próximos Pasos**

Ampliar el experimento a otros elementos del diseño.

Implementar pruebas A/B en diferentes segmentos de usuarios.

Automatizar el proceso de análisis y generación de informes.

🤝 **Contribuciones**

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto, por favor abre un pull request o una issue en el repositorio. 🚀
