# Análisis de Éxito Comercial de Videojuegos para Ice Store

## Objetivo del proyecto

Ice Store, una tienda online de videojuegos, busca optimizar sus estrategias comerciales mediante un análisis exhaustivo de los datos históricos disponibles. El objetivo es identificar los factores que determinan el éxito de un videojuego, con el fin de detectar títulos prometedores y planificar campañas publicitarias más efectivas de cara al año 2017.

Para ello, se estudian aspectos como:
- Reseñas de usuarios y críticos  
- Géneros y plataformas  
- Ventas globales y por región  
- Clasificación ESRB (contenido y edad recomendada)

---

##  Descripción de los datos

Los datos se obtuvieron de fuentes diversas y publicas, estas abarcan hasta diciembre de 2016 e incluyen:
- Nombre del juego  
- Plataforma  
- Año de lanzamiento  
- Género  
- Ventas por región (NA, EU, JP, Otros)  
- Calificaciones de usuarios y críticos  
- Clasificación ESRB  

---

## Librerías utilizadas

`python`
`pandas`
`matplotlib`
`numpy`
`seaborn`
`scipy`

---

## Metodologia

### 1. Preparación de los datos
- Se estandarizan nombres de columnas y formatos de fechas
- Se corrigen y eliminan registros incompletos
- Se convierten variables categóricas a formatos adecuados
- Se crea una columna de ventas globales

### 2. Análisis general

#### 2.1 Juegos por año
- El mercado creció aceleradamente entre 1993 y 2012
- Punto más alto en lanzamientos: años 2008-2009

#### 2.2 Ventas por plataforma
- PlayStation 2 y Xbox 360 dominan el histórico
- PlayStation 4 lidera a partir de 2013

#### 2.3 Conclusiones clave
- La industria sigue ciclos de crecimiento y declive
- PC mantiene relevancia a lo largo del tiempo

### 3. Análisis desde 2013

#### 3.1 Evolución de plataformas líderes
- PS4 se posiciona como la consola más rentable
- Caída en ventas de PS3, Xbox 360 y Nintendo 3DS

#### 3.2 Correlación entre ventas y reseñas
- Las calificaciones de los críticos tienen mayor impacto que las de los usuarios
- Tendencia clara en PS4: más críticas positivas, mayores ventas

#### 3.3 Rentabilidad por género
- Shooter (disparos) es el más rentable por cantidad de títulos
- Acción y deportes destacan por volumen, pero no necesariamente por rentabilidad

#### 3.4 Conclusiones importantes
- Reseñas profesionales = mejor indicador de ventas
- Las campañas deben centrarse en géneros y plataformas de alta conversión

### 4. Análisis por región

#### 4.1 Plataformas
- NA y EU: PS4 domina
- JP: Nintendo 3DS es líder

#### 4.2 Géneros favoritos
- NA y EU: Acción y disparos
- JP: RPGs y acción

#### 4.3 Clasificación ESRB
- M (Mature) y E (Everyone) son las más rentables
- Juegos con clasificación E lideran ventas en JP

#### 4.4 Conclusiones regionales
- Las estrategias deben adaptarse por región
- Nintendo tiene fuerte presencia en Asia; Sony y Microsoft dominan Occidente

### 5. Pruebas de hipótesis

#### 5.1 Xbox One vs. PC (calificaciones de usuarios)
- No hay diferencia significativa entre plataformas
- Varianzas similares → prueba t clásica

#### 5.2 Género acción vs. deportes
- Los juegos de acción reciben mejores calificaciones
- Diferencia estadísticamente significativa

#### 5.3 Conclusiones de pruebas
- Validamos hipótesis sobre la percepción de calidad
- Estas diferencias impactan directamente en la conversión de ventas

### 6. Conclusiones generales
- El análisis identifica patrones claves de éxito comercial
- PS4 es la plataforma líder desde 2013, pero PC mantiene vigencia
- Las críticas profesionales influyen más que las de usuarios
- Las estrategias de marketing deben adaptarse a cada región y tipo de jugador

Este proyecto permite anticipar tendencias y tomar decisiones basadas en datos, lo que representa una ventaja competitiva clara para Ice Store en el mercado de videojuegos.

## Archivos Incluidos

- `ice_analysis_commercial_success_video_games.ipynb` – Notebook principal del análisis
- `requirements.txt` – Dependencias del proyecto
- `README.md` – Descripción general del proyecto

---
