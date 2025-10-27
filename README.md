# 🚦 Clustering de Datos de Tráfico en Madrid

Proyecto sobre aprendizaje no supervisado aplicado al análisis de accidentes de tráfico en Madrid, que incluye tareas de preprocesamiento, visualización y aplicación de diferentes algoritmos de clustering.

## 📋 Índice del Proyecto

### Accidentes de Tráfico en Madrid

#### 0. Descripción del dataset (en `1_jerarquico.ipynb`)

#### Tarea 1: Análisis descriptivo del dataset y preproceso
- Visualización de los datos

#### Aplicación de algoritmos de clustering jerárquico (en `1_jerarquico.ipynb`)
- **Tarea 2.1**: Aplicar 2 métodos de clustering jerárquico con distintas distancias
- **Tarea 2.2**: Analiza si la distribución entre los clústers es uniforme con distintas profundidades
- **Tarea 2.3**: Cómo afectan las distintas distancias al dendograma
- **Tarea 2.4**: Emplea 3 índices de calidad y analiza resultados
- **Tarea 2.5**: Cuál es el número óptimo de clústers
- **Tarea 2.6**: Analiza, con clustering, las zonas con mayor índice de siniestralidad para cada tipo de vehículo

#### Aplicación de algoritmos de clustering particional (en `2_particional.ipynb`)
- **Tarea 3.1**: Realiza el pre-procesamiento necesario para poder aplicar algoritmos de clustering particional
- **Tarea 3.2**: Establece el número más adecuado de clusters para el dataset proporcionado. Ayúdate de los métodos vistos (al menos 2) en la asignatura, así como de gráficas para justificar la decisión. Compara los resultados que obtienes con cada método
- **Tarea 3.3**: ¿Cómo varía la calidad del clustering con diferentes valores de 'K'?
- **Tarea 3.4**: Con el número más adecuado de clusters, ayúdate de estadísticas para analizar a los viajeros incluidos en cada cluster
- **Tarea 3.5**: Compara los resultados obtenidos con K-means y el clustering aglomerativo/jerárquico. Discute las ventajas y desventajas de cada método en diferentes tipos de datos

#### Aplicación de algoritmos de clustering de densidad (en `3_densidad.ipynb`)
- **Tarea 4.1**: Realiza el pre-procesamiento necesario para poder aplicar algoritmos de densidad
- **Tarea 4.2**: Establece el radio (eps) y número de puntos mínimo número más adecuado de clusters para el dataset proporcionado
- **Tarea 4.3**: ¿Cómo varía la calidad del clustering con diferentes valores de 'eps' y de minpoints?
- **Tarea 4.4**: Utiliza por lo menos dos índices de calidad de clustering y analiza sus resultados
- **Tarea 4.5**: ¿Cuál es el número óptimo de clusters? ¿por qué?

#### Aplicación de otros algoritmos
- **Tarea 5.1**: Emplea otros algoritmos como HDBScan y compara con otros algoritmos su rendimiento
- **Tarea 5.2**: Emplea otros algoritmos como K-modes y compara con otros algoritmos su rendimiento

## 🐍 Tecnologías utilizadas
- **Lenguaje**: Python
- **Librerías principales**: scikit-learn, NumPy, Pandas, Matplotlib, HDBScan

## ⚖️ Licencia
Este proyecto está licenciado bajo la **Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)**.  
Esto significa que puedes usar, modificar y compartir este trabajo solo con fines no comerciales, siempre que se otorgue crédito a los autores originales.

📄 [Ver licencia completa](https://creativecommons.org/licenses/by-nc/4.0/)

## 👥 Realizado por:
Juan Moreno Segura y Alonso Ruiz Palomo
