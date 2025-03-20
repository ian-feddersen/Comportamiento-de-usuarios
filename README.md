# Comportamiento-de-usuarios
Analisis de comportamiento de usuarios para una aplicación.
# 📊Análisis de Comportamiento de Usuarios y Test A/A/B para una Aplicación de Alimentos
#### User Behavior Analysis


# 📌Descripción del Proyecto
Este proyecto se centra en el análisis del comportamiento del usuario en una aplicación de venta de productos alimenticios y la evaluación de los resultados de un test A/A/B. El objetivo es entender cómo los usuarios interactúan con la aplicación, identificar cuellos de botella en el embudo de ventas y determinar si un cambio en las fuentes de la aplicación afecta el comportamiento del usuario.

### Parte 1: Análisis del Embudo de Ventas
Se identificaron los eventos clave en el embudo de ventas y se calculó la tasa de conversión entre cada etapa.

Se determinó en qué etapas se pierden más usuarios y qué porcentaje de usuarios completa todo el viaje desde el primer evento hasta el pago.

### Parte 2: Test A/A/B
Se realizó un test A/A/B para evaluar el impacto de un cambio en las fuentes de la aplicación.

Los usuarios se dividieron en tres grupos: dos grupos de control (con las fuentes antiguas) y un grupo de prueba (con las fuentes nuevas).

Se compararon los resultados entre los grupos para determinar si el cambio en las fuentes tuvo un efecto significativo en el comportamiento del usuario.

## 🛠Tecnologías Utilizadas
Lenguajes de programación: Python

Librerías principales: Pandas, Matplotlib, Seaborn, Scipy

Herramientas: Jupyter Notebook

Métricas clave: Tasa de Conversión, Test de Hipótesis, Corrección de Bonferroni

## 📊Estructura del Proyecto
### 1. Preparación de Datos
Carga de datos: Se cargaron los datos desde el archivo logs_exp_us.csv.

Limpieza y transformación: Se verificaron los tipos de datos, se corrigieron valores ausentes y se agregaron columnas de fecha y hora.

### 2. Exploración de Datos
Periodo de tiempo: Los datos cubren desde el 25 de julio de 2019 hasta el 7 de agosto de 2019.

Usuarios únicos: Se identificaron 7,551 usuarios únicos.

Promedio de eventos por usuario: 32.33 eventos por usuario.

### 3. Análisis del Embudo de Ventas
Eventos clave: MainScreenAppear, OffersScreenAppear, CartScreenAppear, PaymentScreenSuccessful.

#### Tasas de conversión:

#### MainScreenAppear a CartScreenAppear: 49.65%

#### CartScreenAppear a PaymentScreenSuccessful: 46.97%

### 4. Test A/A/B
Comparación entre grupos de control: No se encontraron diferencias significativas entre los grupos 246 y 247.

Comparación entre grupo experimental y grupo de control: No se encontraron diferencias significativas entre el grupo 248 y los grupos de control.

### 5. Ajuste del Nivel de Significancia
Corrección de Bonferroni: Se ajustó el nivel de significancia a 0.01 para controlar la tasa de falsos positivos.

# 📈Resultados Clave
Embudo de Ventas
## Pérdida de usuarios: La mayor pérdida de usuarios ocurre entre MainScreenAppear y CartScreenAppear, con una tasa de conversión del 49.65%.

## Conversión final: Solo el 46.97% de los usuarios que llegan al carrito completan el pago.

# Test A/A/B
#### No hay diferencias significativas: No se encontraron diferencias estadísticamente significativas entre los grupos de control y el grupo experimental en cuanto a la interacción con los eventos clave.

# Conclusión: El cambio en las fuentes no tuvo un impacto significativo en el comportamiento del usuario.

## Conclusiones y Recomendaciones
Embudo de Ventas
Optimización de etapas clave: Se recomienda investigar y optimizar las etapas donde se pierden más usuarios, especialmente entre MainScreenAppear y CartScreenAppear.

Mejora del proceso de pago: Se sugiere revisar y mejorar la experiencia del usuario en la etapa de pago para aumentar la tasa de conversión final.

Test A/A/B
Continuar monitoreando: Aunque el cambio en las fuentes no mostró un impacto significativo, se recomienda continuar monitoreando el comportamiento del usuario y realizar más pruebas en otras áreas de la aplicación.

Explorar otros cambios: Se pueden explorar otros cambios en el diseño y la funcionalidad de la aplicación para identificar oportunidades de mejora.
