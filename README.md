# 🇨🇷 Análisis de Adopción del Gas LP Vehicular (AutoGLP) en Costa Rica

## Enlace de Demostración
*Actualmente el proyecto se encuentra en su fase inicial de planificación y diseño metodológico, por lo que no cuenta con un enlace de despliegue activo.*

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
Este proyecto forma parte de mi **Portafolio de Análisis de Big Data**. Consiste en un estudio analítico sobre el mercado del **Gas Licuado de Petróleo (GLP) de uso vehicular en Costa Rica**, evaluando el impacto económico de la brecha de precios frente a los combustibles tradicionales (Gasolina Súper y Regular) y cómo este factor determina el ritmo de consumo nacional.

Costa Rica se encuentra bajo un Plan Nacional de Descarbonización; comprender la transición hacia combustibles de menor impacto económico y ambiental es clave para el sector energético, talleres de conversión y consumidores particulares.

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

Para resolver la pregunta de investigación, el proyecto recopilará y procesará las siguientes variables extraídas de fuentes oficiales de datos abiertos de Costa Rica:

*   **Precios Históricos:** Precios mensuales en colones (🇨🇷 ¢) de Gasolina Súper, Regular y Gas LP (Fuente: **ARESEP**).
*   **Volumen de Ventas:** Consumo mensual en metros cúbicos ($m^3$) de GLP destinado al sector transporte (Fuente: **RECOPE**).
*   **Parque Automotor:** Estimaciones de vehículos convertidos a gas y tasas de inspección vehicular (Fuente: **MINAE / MOPT**).

---

## Capturas de Pantalla de Visualizaciones/Resultados
*Al encontrarse el proyecto en la Fase 1 (Planteamiento del problema y diseño de la pregunta), aún no se han generado gráficos o tableros interactivos. Las capturas se integrarán conforme se procesen las bases de datos.*

---

## Tecnologías
Para el desarrollo de las siguientes fases del análisis se tiene previsto utilizar:
*   **Markdown:** Para la documentación del repositorio.
*   *Próximamente:* Python (Pandas/NumPy) para la limpieza de datos y herramientas de visualización.

---

## Configuración
Actualmente, el repositorio no requiere configuraciones de entorno o instalación de librerías, ya que cuenta únicamente con el archivo base de documentación:
*   `README.md`: Documento principal de presentación del proyecto.

---

## Enfoque

### Reflexión del Proceso Analítico
1.  **¿Por qué es importante identificar la pregunta antes de comenzar el análisis?**  
    La pregunta actúa como una brújula analítica. En el contexto de Big Data la cantidad de información disponible es masiva y abrumadora. Sin una pregunta clara, es muy fácil perderse en el ruido de los datos, procesar variables innecesarias y malgastar recursos. La pregunta delimita con precisión qué datos recolectar, cómo limpiarlos y qué respuestas visuales presentar.

2.  **Tipo de Análisis Aplicado:**  
    Inicialmente se aplicará un **Análisis Descriptivo** para modelar y entender el comportamiento histórico de los datos reales. Conforme avance el proyecto, se evaluará la implementación de un **Análisis Predictivo** mediante modelos de regresión para pronosticar la demanda de AutoGLP basada en los escenarios de fluctuación del precio internacional del petróleo.

---

## Estado
 **En progreso (Fase de Planificación)** - Estructura metodológica y pregunta de investigación completadas. El repositorio se actualizará conforme se inicie la extracción de las fuentes de datos identificadas.

---

## Créditos
**Autor:** Karina Garro Granados  
*Estudiante de Big Data y Analítica de Datos*  
📍 San José, Costa Rica
