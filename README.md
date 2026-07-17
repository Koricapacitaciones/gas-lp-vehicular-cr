# 🇨🇷 Análisis de Adopción del Gas LP Vehicular (AutoGLP) en Costa Rica

## Enlace de Demostración
*   **Repositorio GitHub:** [https://github.com/karinagarro/gas-lp-vehicular-cr](https://github.com/karinagarro/gas-lp-vehicular-cr)
*   **Tablero de Control Activo:** [Enlace al Dashboard de visualización del mercado energético]

---

## Índice (opcional)
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
Este proyecto analiza el mercado del **Gas Licuado de Petróleo (GLP) de uso vehicular (AutoGLP) en Costa Rica**, evaluando el impacto económico de la brecha de precios frente a los combustibles tradicionales (Gasolina Súper y Regular) y cómo este factor determina el ritmo de consumo nacional. En el marco del Plan Nacional de Descarbonización, comprender la transición hacia combustibles de menor impacto económico y ambiental es clave para el sector energético, talleres de conversión y consumidores particulares.

### Objetivos del Proyecto
*   **Identificar** el comportamiento histórico (mensual/anual) de los precios de las gasolinas frente al Gas LP en el mercado costarricense.
*   **Determinar** si existe una correlación directa entre el aumento de la brecha de precios (ahorro en colones por litro) y el incremento en el volumen de ventas de AutoGLP.
*   **Estructurar** un repositorio de datos limpio y unificado que sirva como base para futuros modelos de análisis predictivo de demanda energética.

### Pregunta de Investigación (Fase 1)
> **¿En qué medida la brecha de precios (ahorro económico por litro) frente a las gasolinas tradicionales influye en el ritmo de adopción y volumen de consumo de Gas LP vehicular en Costa Rica durante los últimos años?**

### Beneficios del Análisis
1.  **Para Consumidores y Flotillas:** Permite proyectar con base en datos reales el tiempo de retorno de inversión tras realizar la conversión del vehículo ($1.000 USD aprox.).
2.  **Para Estaciones de Servicio:** Ayuda a los empresarios del sector a predecir la rentabilidad de instalar dispensadores de AutoGLP según las tendencias geográficas y de consumo.
3.  **Para el Estado (RECOPE / MINAE):** Aporta métricas para planificar las cuotas de importación y almacenamiento del gas ante un crecimiento acelerado de la demanda.

---

## Comprensión de los Datos

Para resolver la pregunta de investigación, el proyecto recopila y procesa las siguientes variables extraídas de fuentes oficiales de datos abiertos de Costa Rica:

### 1. Variables Clave y Métricas Analizadas
*   **Precios Históricos (ARESEP):** Serie temporal de precios mensuales en colones (🇨🇷 ¢) de Gasolina Súper, Regular y Gas LP (Estaciones de servicio / Tanques fijos).
*   **Volumen de Ventas (RECOPE):** Consumo mensual en metros cúbicos ($m^3$) y millones de litros de GLP destinado al sector transporte (Estaciones de servicio autorizadas).
*   **Estadísticas de Flotilla (MINAE / MOPT):** Estimaciones de conversión vehicular y tasas de incidentes estables reportadas por el Cuerpo de Bomberos.

### 2. Contexto Estadístico del Mercado Nacional
Según reportes del sector energético de Costa Rica:
*   RECOPE distribuye alrededor de **360 millones de litros de GLP al año** a nivel global.
*   El sector de **AutoGLP (vehicular) representa cerca de 40 millones de litros** del consumo total del país.
*   La demanda de Gas LP en vehículos muestra tasas de crecimiento anuales sostenidas de entre el **30% y el 35%**, posicionándolo como el combustible de mayor dinamismo porcentual debido al factor precio.

---

## Capturas de Pantalla de Visualizaciones/Resultados

### 📈 Gráfico 1: Tendencia Histórica de Precios de Combustibles vs. Gas LP
Muestra la evolución del precio por litro en Costa Rica (Súper, Regular y Gas LP) evidenciando el margen constante de ahorro para el usuario de AutoGLP. *(Imagen del gráfico analítico e histórico adjunta en el reporte técnico).*

### 📊 Gráfico 2: Correlación entre Brecha Económica y Volumen de Ventas en Litros
Visualización cruzada que contrasta el aumento del ahorro por litro frente al pico en las ventas anuales reportadas por los planteles de RECOPE. *(Matriz de correlación de variables disponible en la documentación del tablero).*

---

## Tecnologías
*   **Markdown:** Documentación técnica del entorno de desarrollo.
*   **Python (Pandas & NumPy):** Procesamiento de datos, limpieza de nulos y unificación de archivos `.csv` de ARESEP y RECOPE.
*   **Matplotlib / Seaborn:** Generación de gráficos estadísticos y matrices de correlación.
*   **Git / GitHub:** Control de versiones del portafolio.

---

## Configuración

### Estructura de Archivos del Repositorio
*   **datos/** (Bases de datos unificadas)
    *   historico_precios_aresep.csv
    *   ventas_combustibles_recope.csv
*   **scripts/** (Código fuente analítico)
    *   01_limpieza_y_extraccion.py
*   **visualizaciones/** (Reportes gráficos exportados)
*   **README.md** (Presentación del proyecto)

### Requisitos del Enfoque
Para replicar el análisis de datos, se recomienda trabajar en un entorno de Python e instalar las librerías base mediante la consola con los comandos tradicionales de pip de Pandas, NumPy, Matplotlib y Seaborn.

---

## Enfoque

### Reflexión del Proceso Analítico
1.  **¿Por qué es importante identificar la pregunta antes de comenzar el análisis?**  
    La pregunta actúa como una brújula analítica. En el contexto de Big Data la cantidad de información disponible es masiva y abrumadora. Sin una pregunta clara, es muy fácil perderse en el ruido de los datos, procesar variables innecesarias y malgastar recursos. La pregunta delimita con precisión qué datos recolectar, cómo limpiarlos y qué respuestas visuales presentar.

2.  **Tipo de Análisis Aplicado:**  
    Se aplica un **Análisis Descriptivo** para modelar y entender el comportamiento histórico de los datos reales de consumo del país. Adicionalmente, el enfoque evoluciona hacia un **Análisis Predictivo** mediante modelos de regresión lineal para pronosticar la demanda de AutoGLP basada en los escenarios de fluctuación del precio internacional del petróleo y su impacto en las tarifas locales.

---

## Estado
 **Completado (Fase de Análisis Estadístico y Documentación)** - Toda la estructura metodológica, recopilación de variables de fuentes oficiales de Costa Rica (ARESEP/RECOPE) y diseño del enfoque analítico han sido satisfactoriamente implementados en el portafolio.

---

## Créditos
**Autor:** Karina Garro Granados  
*Estudiante de Big Data y Analítica de Datos*  
📍 San José, Costa Rica
