# Análisis comparativo de series de tiempo: mercado financiero vs. inmobiliario

Reporte de investigación (agosto 2022) que compara el **mercado financiero estadounidense (S&P 500)** y el **mercado inmobiliario (índice Case-Shiller)** como instrumentos de inversión, mediante pronósticos de series de tiempo con modelos estadísticos univariables y multivariables.

📄 **Documento completo (48 pp.):** [`Reporte_de_Investigación.pdf`](./Reporte_de_Investigaci%C3%B3n.pdf)

**Autores:** Julia Domínguez, Oscar Tiznado, Antonio Juan, Lidia Zepeda

## Metodología

Análisis implementado en **RStudio** sobre ambas series:

| Método | Uso |
|---|---|
| **Descomposición** (aditiva y multiplicativa) | Separar tendencia, estacionalidad y residuos; detectar choques |
| **Suavización exponencial** | Pronóstico univariable con ponderación decreciente de observaciones |
| **ARIMA** | Modelado autorregresivo integrado de media móvil, selección por AIC/BIC |
| **ARDL** | Modelo multivariable de rezagos distribuidos para capturar la relación entre ambos mercados |

## Contenido del reporte

1. Marco teórico: oferta/demanda, volatilidad, rentabilidad y eficiencia de ambos mercados
2. Fundamentos de series de tiempo: estacionariedad, autocorrelación, criterios de información
3. Desarrollo: pronósticos por método para cada mercado, con diagnósticos
4. Comparación de resultados y conclusiones sobre cada mercado como instrumento de inversión
