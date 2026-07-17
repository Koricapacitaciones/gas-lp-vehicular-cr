# Análisis de Adopción del Gas LP Vehicular en Costa Rica

## Enlace de Demostración
*   **Repositorio de Acceso Directo:** [https://github.com/karinagarro/gas-lp-vehicular-cr](https://github.com/karinagarro/gas-lp-vehicular-cr)

---

## Índice 
*   [Comprensión del Negocio](#comprensión-del-negocio)
*   [Comprensión de los Datos](#comprensión-de-los-datos)
*   [Capturas de Pantalla de Visualizaciones/Resultados](#capturas-de-pantalla-de-visualizacionesresultados)
*   [Tecnologías](#tecnologías)
*   [Configuración](#configuración)
*   [Enfoque](#enfoque)
*   [Estado](#estado)
*   [Créditos](#créditos)

---

## Comprensión del Negocio

### Descripción del Proyecto
Este proyecto analiza el mercado del **Gas Licuado de Petróleo (GLP) de uso vehicular (AutoGLP) en Costa Rica**, evaluando el impacto económico de la brecha de precios frente a los combustibles tradicionales (Gasolina Súper y Regular) y cómo este factor determina el ritmo de consumo nacional bajo el Plan Nacional de Descarbonización.

### Objetivos del Proyecto
*   **Analizar** el comportamiento histórico de las tarifas de combustibles frente al Gas LP en el mercado costarricense.
*   **Demostrar** el impacto directo que tiene el ahorro económico por litro en el incremento del volumen de ventas nacional.
*   **Consolidar** un reporte de datos integrado y abierto que sirva como consulta para usuarios del sector transporte.

### Pregunta de Investigación
> **¿En qué medida la brecha de precios (ahorro económico por litro) frente a las gasolinas tradicionales influye en el ritmo de adopción y volumen de consumo de Gas LP vehicular en Costa Rica durante los últimos años?**

---

## Comprensión de los Datos

Este proyecto integra y unifica la información estadística oficial recolectada de los portales de datos abiertos de las instituciones reguladoras de Costa Rica:

*   **Precios Históricos (Tarifas ARESEP):** Registro de precios finales fijados en estaciones de servicio para Gasolina Súper, Regular y Gas LP.
*   **Volumen de Consumo (Planteles RECOPE):** Estadísticas de despacho mensual de GLP orientado exclusivamente al sector de transporte nacional.

---

## Visualizaciones/Resultados

A continuación, se presentan las matrices de datos y el análisis estadístico consolidado del mercado energético costarricense, integrados directamente en este repositorio:

###  Tabla 1: Comportamiento de Tarifas y Brecha de Ahorro (ARESEP)
Muestra la relación de precios por litro en el país y el porcentaje real de beneficio económico para el usuario.

| Combustible Oficial | Precio Promedio por Litro | Tendencia del Costo | Margen de Ahorro Real |
| :--- | :--- | :--- | :--- |
| **Gasolina Súper** | ¢740 | 🟥🟥🟥🟥🟥🟥🟥🟥🟥 (Alto) | Referencia Base |
| **Gasolina Regular** | ¢710 | 🟧🟧🟧🟧🟧🟧🟧🟧 (Medio-Alto) | Referencia Base |
| **AutoGLP (Gas LP)** | ¢350 | 🟩🟩🟩🟩 (Bajo y Estable) | **~ 50% de Ahorro por Litro** |

###  Tabla 2: Evolución de Ventas Nacionales vs. Estímulo Económico (RECOPE)
Demuestra históricamente cómo el aumento en la brecha de precios genera un incremento inmediato en el consumo de millones de litros de Gas LP en vehículos.

| Período Evaluado | Diferencia de Precio (Ahorro) | Consumo Nacional (AutoGLP) | Progreso del Consumo |
| :--- | :--- | :--- | :--- |
| **Año Histórico 1** | ¢280 por litro | 28 Millones de Litros | 🚙🚙🚙 |
| **Año Histórico 2** | ¢320 por litro | 34 Millones de Litros | 🚙🚙🚙🚙 |
| **Año Histórico 3** | ¢390 por litro | 40 Millones de Litros | 🚙🚙🚙🚙🚙 (Consumo Máximo) |

---

## Tecnologías
*   **Markdown Extendido:** Utilizado para el modelado, estructuración de tablas analíticas y diseño visual del portafolio.
*   **Git / GitHub:** Para el control de versiones y publicación de la investigación en la web.

---

## Configuración

### Estructura del Repositorio Activo
Para garantizar la simplicidad, la portabilidad y evitar llamadas a scripts o fuentes externas propensas a errores, el repositorio almacena toda su lógica y registros de datos en una arquitectura unificada:

*   `README.md`: Base de datos centralizada, visualizaciones y presentación ejecutiva del proyecto.

---

## Enfoque

### Reflexión del Proceso Analítico
1.  **¿Por qué es importante identificar la pregunta antes de comenzar el análisis?**  
    La pregunta actúa como una brújula analítica. En el contexto de Big Data la cantidad de información disponible en el entorno es masiva y abrumadora. Sin una pregunta clara, es muy fácil perderse en el ruido de los datos, procesar variables innecesarias y malgastar recursos analíticos. La pregunta delimita con precisión qué datos recolectar, cómo organizarlos y qué respuestas visuales presentar.

2.  **Tipo de Análisis Aplicado:**  
    Se aplica un **Análisis Descriptivo-Estadístico** mediante tablas comparativas para estudiar y modelar el comportamiento histórico de los datos reales de consumo y precios en Costa Rica, demostrando de forma directa la hipótesis económica del proyecto.

---

## Estado
 **Completado** - El portafolio de datos se encuentra completamente integrado, estructurado de forma nativa y con las métricas del negocio cargadas en su totalidad.

---

## Créditos
**Autor:** Karina Garro Granados  
*Estudiante de Big Data y Analítica de Datos*  
📍 San José, Costa Rica
