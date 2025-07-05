# Análisis de Ventas de Videojuegos – Proyecto Integrado

## Descripción del Proyecto

Este proyecto fue desarrollado como parte del Sprint 6 del bootcamp de análisis de datos de TripleTen. El objetivo es identificar patrones que determinen el éxito comercial de un videojuego, utilizando datos históricos de ventas, reseñas de usuarios y expertos, plataformas, géneros y clasificaciones ESRB. El análisis se centra en datos hasta 2016, con el propósito de planificar campañas publicitarias para 2017.

---

## Etapas del Proyecto

### 1. Preparación de Datos
- Renombrado de columnas a minúsculas.
- Conversión de tipos de datos (fechas, numéricos).
- Tratamiento de valores ausentes y casos especiales como “TBD”.
- Cálculo de ventas globales por juego.

### 2. Análisis Exploratorio
- Distribución de lanzamientos por año.
- Evolución de ventas por plataforma.
- Identificación de plataformas emergentes y en declive.
- Selección de datos relevantes para modelar 2017.

### 3. Análisis de Reseñas y Géneros
- Correlación entre reseñas de usuarios/profesionales y ventas.
- Comparación de ventas de un mismo juego en distintas plataformas.
- Análisis de géneros más rentables y su distribución.

### 4. Perfil de Usuario por Región
- Principales plataformas y géneros en NA, EU y JP.
- Impacto de la clasificación ESRB en cada región.

### 5. Pruebas de Hipótesis
- Comparación de calificaciones de usuarios entre Xbox One y PC.
- Comparación de calificaciones entre géneros Acción y Deportes.
- Formulación de hipótesis nula y alternativa.
- Pruebas estadísticas con valor alfa definido.

---

## Diccionario de Datos

| Columna         | Descripción                                                                 |
|------------------|------------------------------------------------------------------------------|
| `name`           | Nombre del videojuego                                                       |
| `platform`       | Plataforma (ej. PS4, Xbox One, PC)                                          |
| `year_of_release`| Año de lanzamiento                                                          |
| `genre`          | Género del juego (Acción, Deportes, etc.)                                   |
| `na_sales`       | Ventas en Norteamérica (millones USD)                                       |
| `eu_sales`       | Ventas en Europa (millones USD)                                             |
| `jp_sales`       | Ventas en Japón (millones USD)                                              |
| `other_sales`    | Ventas en otras regiones (millones USD)                                     |
| `critic_score`   | Puntuación de críticos (0–100)                                              |
| `user_score`     | Puntuación de usuarios (0–10)                                               |
| `rating`         | Clasificación ESRB (E, T, M, etc.)                                          |

---

## Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- SciPy (pruebas estadísticas)  
- Jupyter Notebook

---

## Resultados

- Se identificaron plataformas líderes y en declive con base en ventas históricas.
- Se encontró una correlación moderada entre reseñas y ventas en ciertas plataformas.
- Los géneros más rentables fueron Acción y Deportes, aunque con diferencias regionales.
- Las pruebas de hipótesis revelaron diferencias significativas entre plataformas y géneros.

---

## 📫 Contacto

Paz Emmanuel Balderas Cerezo  
📧 pazemmanuel24032005@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/paz-emmanuel-balderas-cerezo-dataanalyst)
