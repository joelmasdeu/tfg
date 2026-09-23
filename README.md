Análisis Financiero y Econométrico de Activos Alternativos: El Caso de Pokémon TCG


📌 Contexto y Objetivo del Proyecto   

El mercado de activos coleccionables ha experimentado una transformación financiera radical, atrayendo a inversores minoristas y generando un intenso debate sobre su viabilidad frente a las inversiones tradicionales.   

El objetivo de este proyecto es auditar este mercado emergente aplicando rigor estadístico y econométrico, evaluando su rentabilidad, su volatilidad y su potencial como herramienta de diversificación de carteras (frente al S&P 500, el Oro y el Bitcoin). Además, se busca demostrar matemáticamente la existencia de burbujas especulativas en los precios de estos activos tangibles.   


🛠️ Stack Tecnológico y Metodología

Lenguaje y Entorno: R y RStudio.  

Librerías principales: dplyr, ggplot2, lubridate, psymonitor, zoo, tidyquant.  

Extracción de Datos: Construcción de una base de datos propia con más de 20.000 registros de transacciones reales mediante web-scraping de la plataforma de certificación Professional Sports Authenticator (PSA).   

Modelización Financiera: Cálculo de métricas de riesgo y rendimiento (ROI, CAGR, Volatilidad anualizada, Maximum Drawdown) y matrices de correlación de Pearson.   

Modelización Econométrica: Aplicación del test recursivo PSY (Phillips, Shi y Yu, 2015) para la detección y datación en tiempo real de burbujas especulativas explosivas. 


📊 Principales Conclusiones de Negocio

A través del análisis de 20 activos diferenciados por su madurez (Vintage vs. Modernos), se obtuvieron los siguientes insights económicos:   

- Descorrelación del Mercado Tradicional (Vintage): El mercado de cartas clásicas actúa de forma autónoma y endógena, mostrando una correlación prácticamente nula con el S&P 500 (-0.04) y el Oro (0.03). Esto desmiente que funcionen como un "valor refugio" tradicional, pero valida su uso teórico para descorrelacionar carteras.

- Comportamiento de Riesgo (Modernas): Las ediciones recientes presentan una ligera afinidad pro-cíclica con el Bitcoin (0.21) y el S&P 500 (0.18), absorbiendo parte de la inercia y la liquidez de los mercados especulativos.

- Detección Matemática de Burbujas: El modelo PSY confirmó estadísticamente un shock sistémico de exuberancia irracional en el mercado Vintage (2020-2021). Por el contrario, el mercado moderno sufre micro-burbujas asíncronas, fragmentadas y de naturaleza mucho más frágil y especulativa (2024-2025).

- Prima de Riesgo Extrema: Aunque activos como el Charizard Base Set o el Gengar Fossil mostraron retornos anualizados (CAGR) consistentes a largo plazo superiores al 30%, estos rendimientos exigen soportar caídas de valor dramáticas, con Maximum Drawdowns que superan el -80% e incluso el -90% en activos consolidados.
