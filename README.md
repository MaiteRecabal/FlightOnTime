# FlightOnTime

FlightOnTime es un **MVP predictivo** desarrollado para un hackathon, cuyo objetivo es **estimar si un vuelo será puntual o tendrá retraso**, utilizando datos históricos y técnicas básicas de Ciencia de Datos.

El proyecto replica, a escala académica, soluciones reales utilizadas por aerolíneas, aeropuertos y plataformas de transporte aéreo.

---

## Problema que aborda

Los retrasos en vuelos generan:
- insatisfacción en los pasajeros,
- costos operativos para aerolíneas,
- problemas logísticos en aeropuertos (conexiones perdidas, reprogramaciones).

FlightOnTime permite **anticipar el riesgo de retraso** a partir de información básica del vuelo, entregando una predicción clara y una probabilidad asociada.

---

## Alcance del MVP

- Clasificación binaria:
  - `0` → Puntual  
  - `1` → Retrasado
- Predicción basada en:
  - aerolínea
  - aeropuerto de origen y destino
  - fecha y hora de salida
  - distancia del vuelo
- API REST funcional para consumo externo
- Modelo entrenado con datos históricos

---

## Arquitectura General

El sistema está dividido en tres componentes principales:

