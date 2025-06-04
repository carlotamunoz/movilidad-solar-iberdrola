☀️ Movilidad Solar para Cooltra e Iberdrola

Este proyecto plantea una propuesta innovadora y sostenible para recargar la flota de motos eléctricas de **Cooltra** mediante **energía solar**, con el respaldo de **Iberdrola** como proveedor energético.

El objetivo es analizar si es **técnicamente viable y económicamente rentable** implementar un sistema de carga solar distribuido en las estaciones de motos compartidas.

---

## 🗂 Estructura del proyecto

### 📁 `creacion_dataset/`

Contiene los notebooks y scripts que:

- Analizan datos abiertos de **BiciMAD** (EDA).
- Simulan una red de motos a partir del comportamiento real de bicicletas en Madrid.
- Ajustan datos a la flota de Cooltra (2000 motos, 2.8kWh de batería).
- Generan un dataset sintético de más de **300.000 viajes**.
- Simulan los **slots óptimos por estación** para aparcamiento y recarga.

### 📁 `consumo_produccion/`

Incluye el análisis energético:

- Precios reales por hora del **mercado eléctrico español (OMIE)**.
- Consumo energético por trayecto usando distancias y altitud (via API).
- Producción solar estimada por hora y estación usando datos de **PVWatts**.
- Cálculo de excedentes solares.
- Comparación entre consumo y producción **hora a hora**.
- Evaluación del porcentaje cargado con red vs. solar.
- Estrategia óptima de carga para maximizar beneficios.

---

## 💡 Conclusiones destacadas

- **Producción solar media mensual:** 53.703 kWh  
- **Consumo mensual total de la red:** 4.015 kWh  
- **Energía excedente vendible:** ~49.000 kWh/mes  
- **Ingresos anuales (alquiler + venta de excedente):** +888.000 €  
- **Inversión inicial (paneles + slots):** ~5,1 millones €  
- **Período de retorno estimado:** 5,7 años ✅

---

## 📊 Recursos visuales

El proyecto incluye:

- Gráficos comparativos por hora y estación.
- Simulaciones visuales de carga, consumo y producción.
- Elementos gráficos originales (ilustraciones, iconos y esquemas) para presentación.

---

## 🤖 Tecnologías utilizadas

- `Python` (Pandas, NumPy, Matplotlib)
- `Jupyter Notebooks`
- `PVWatts API`
- `OpenRouteService` (para distancias y altitud)
- `Git` / `GitHub`

---

## 🧠 Autora

**Carlota Muñoz de Luna Eusebio**  
Estudiante de Ingeniería y Sistemas de Datos  

---
## Bibliografía

 Generador de Precios (s.f.), "IEB005: Estación de recarga de bicicletas", Generador de Precios,
 [https://generadordeprecios.info/obra_nueva/Instalaciones/Electricas/Recarga_de_vehiculos_electricos/IEB005
 _Estacion_de_recarga_de_bicicletas___0_1_0_0_0_0_0_0_0.html.]
  Idealista
 (2021),
 "¿Cuánto cuesta poner paneles solares en casa?",
 Idealista, [https://www.idealista.com/news/inmobiliario/vivienda/2021/02/22/789196-cuanto-cuesta-poner-paneles-solares-en-casa.]
 Open-Meteo (s.f.), "Open-Meteo", Open-Meteo, [https://open-meteo.com/].
 OSRM (2023), "OSRM API Documentation", Project OSRM, `[https://project-osrm.org/docs/v5.24.0/api/].
 NREL(s.f.), "PVWatts Calculator", PVWatts, [https://pvwatts.nrel.gov/].
  Selectra
 (2023),
 "Precio de excedentes en [https://selectra.es/autoconsumo/info/tarifas#precio-excedentes-autoconsumo]
  Elizondo, M. (2021, 10 mayo). Iberdrola, Cooltra e Inetum cierran una alianza para la recarga de vehículos eléctricos. El
 Español.
 BiciMAD. Datos de los itinerarios de las bicicletas eléctricas - Portal de datos abiertos del Ayuntamiento de Madrid. (s. f.)
 

