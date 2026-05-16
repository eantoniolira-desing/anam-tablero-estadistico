# Tablero Estadístico ANAM 2018–2025

Prueba de diseño — Agencia Nacional de Aduanas de México (ANAM).  
Tablero estadístico interactivo de recaudación aduanera 2018–2025.

## Vistas

| Vista | Descripción |
|-------|-------------|
| [Vista Ejecutiva](Output/Ejercicio2_Vista_Ejecutiva.html) | KPIs, tendencia histórica, top aduanas y distribución por tipo |
| [Vista Operativa](Output/Ejercicio2_Vista_Operativa.html) | Ranking de aduanas, mapa interactivo y análisis por región |
| [Vista Impuestos](Output/Ejercicio2_Vista_Impuestos.html) | Desglose de IVA, IEPS, IGI, DTA y otros — histórico 2018–2025 |
| [Presentación](Output/Ejercicio1_Presentacion.html) | Presentación ejecutiva de 6 diapositivas |

## Stack

- HTML5 + CSS3 + JavaScript (vanilla)
- [Chart.js 4.4.0](https://www.chartjs.org/) — gráficas interactivas
- [Leaflet 1.9.4](https://leafletjs.com/) — mapa de México con marcadores
- Montserrat via Google Fonts
- Sin frameworks ni build steps — archivos estáticos puros

## Características

- Filtros interactivos reactivos (tipo de aduana, año, impuesto, región)
- Mapa interactivo de la República Mexicana con 20 aduanas principales
- Módulo de Accesos simulado (Pedimentos, Com. Exterior, Configuración)
- Toggles de visibilidad persistentes via localStorage
- Datos mensuales 2025 (12 meses) en vista de impuestos
- Paleta institucional ANAM: Guinda · Verde · Arena

## Datos

Fuente: ANAM — Flujo de efectivo · Periodo 2018–2025*  
*Cifras 2025 preliminares sujetas a revisión  
Unidades: Millones de pesos MXN
