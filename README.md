# 🇨🇷 Análisis de Adopción del Gas LP Vehicular (AutoGLP) en Costa Rica

## 📊 Descripción del Proyecto
Este proyecto forma parte de mi **Portafolio de Análisis de Big Data**. Consiste en un estudio analítico sobre el mercado del **Gas Licuado de Petróleo (GLP) de uso vehicular en Costa Rica**, evaluando el impacto económico de la brecha de precios frente a los combustibles tradicionales (Gasolina Súper y Regular) y cómo este factor determina el ritmo de consumo nacional.

Costa Rica se encuentra bajo un Plan Nacional de Descarbonización; comprender la transición hacia combustibles de menor impacto económico y ambiental es clave para el sector energético, talleres de conversión y consumidores particulares.

---

## 🎯 Objetivos del Proyecto

*   **Identificar** el comportamiento histórico (mensual/anual) de los precios de las gasolinas frente al Gas LP en el mercado costarricense.
*   **Determinar** si existe una correlación directa entre el aumento de la brecha de precios (ahorro en colones por litro) y el incremento en el volumen de ventas de AutoGLP.
*   **Estructurar** un repositorio de datos limpio y unificado que sirva como base para futuros modelos de análisis predictivo de demanda energética.

---

## ❓ Pregunta de Investigación (Fase 1: Hacer la Pregunta)
> **¿En qué medida la brecha de precios (ahorro económico por litro) frente a las gasolinas tradicionales influye en el ritmo de adopción y volumen de consumo de Gas LP vehicular en Costa Rica durante los últimos años?**

### 💡 Beneficios del Análisis:
1.  **Para Consumidores y Flotillas:** Permite proyectar con base en datos reales el tiempo de retorno de inversión tras realizar la conversión del vehículo ($1.000 USD aprox.).
2.  **Para Estaciones de Servicio:** Ayuda a los empresarios del sector a predecir la rentabilidad de instalar dispensadores de AutoGLP según las tendencias geográficas y de consumo.
3.  **Para el Estado (RECOPE / MINAE):** Aporta métricas para planificar las cuotas de importación y almacenamiento del gas ante un crecimiento acelerado de la demanda.

---

## 🛠️ Datos Necesarios y Fuentes Identificadas

Para resolver la pregunta de investigación, el proyecto recopila y procesa las siguientes variables extraídas de fuentes oficiales de datos abiertos de Costa Rica:

| Elemento de Datos | Variable Clave | Fuente Oficial |
| :--- | :--- | :--- |
| **Precios Históricos** | Precios mensuales en colones (🇨🇷 ¢) de Gasolina Súper, Regular y Gas LP. | **ARESEP** (Autoridad Reguladora de los Servicios Públicos) |
| **Volumen de Ventas** | Consumo mensual en metros cúbicos ($m^3$) de GLP destinado al sector transporte. | **RECOPE** (Refinadora Costarricense de Petróleo) |
| **Parque Automotor** | Estimaciones de vehículos convertidos a gas y tasas de inspección vehicular. | **MINAE** (Dirección Sectorial de Energía) / Estadísticas del MOPT |

---

## 📂 Estructura del Repositorio

El proyecto se organiza bajo las mejores prácticas de la industria para el análisis de datos:

```text
├── datos/                  # Datos crudos (Raw Data) y datos procesados (Clean Data)
│   ├── historico_precios_aresep.csv
│   └── ventas_combustibles_recope.csv
├── scripts/                # Notebooks de Jupyter o Scripts de Python/SQL para ETL
│   └── 01_limpieza_y_extraccion.py
├── visualizaciones/        # Gráficos generados, reportes en PDF o enlaces a Dashboards
└── README.md               # Presentación del proyecto (Este archivo)
---

## 🧠 Reflexión del Proceso Analítico

### 1. ¿Por qué es importante identificar la pregunta antes de comenzar el análisis?
La pregunta actúa como una brújula analítica. En el contexto de Big Data la cantidad de información disponible es masiva y abrumadora. Sin una pregunta clara, es muy fácil perderse en el ruido de los datos, procesar variables innecesarias y malgastar recursos. La pregunta delimita con precisión qué datos recolectar, cómo limpiarlos y qué respuestas visuales presentar.

### 2. Tipo de Análisis Aplicado
Inicialmente se aplica un **Análisis Descriptivo** para modelar y entender el comportamiento histórico de los datos reales. Conforme avance el proyecto, se evaluará la implementación de un **Análisis Predictivo** mediante modelos de regresión para pronosticar la demanda de AutoGLP basada en los escenarios de fluctuación del precio internacional del petróleo.

---
**Autor:** Karina Garro Granados  
*Estudiante de Big Data y Analítica de Datos*  
📍 San José, Costa Rica
