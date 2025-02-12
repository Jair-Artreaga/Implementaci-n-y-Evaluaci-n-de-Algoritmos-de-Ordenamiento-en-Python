# Implementación y Evaluación de Algoritmos de Ordenamiento en Python

## Descripción
Este proyecto implementa y evalúa dos métodos de ordenamiento en Python: **Burbuja** y **Quicksort**, utilizando Jupyter Notebook. Se analizan sus rendimientos en conjuntos de datos de diferentes tamaños y se documentan los resultados para comprender la eficiencia de cada algoritmo. Además, se fomenta el uso de GitHub como herramienta para la gestión y documentación de proyectos.

## Objetivos
- Implementar los algoritmos de ordenamiento **Burbuja** y **Quicksort** en Python.
- Comparar el rendimiento de ambos métodos utilizando mediciones de tiempo.
- Analizar la eficiencia de cada algoritmo en función del tamaño de los datos.
- Fomentar el uso de **Jupyter Notebook** y **GitHub** para la documentación y el desarrollo profesional.

## Estructura del Proyecto
```
📂 Ordenamiento-Pytho
│── 📂 data  # Datos generados para las pruebas
│── 📂 results  # Resultados y análisis comparativo
│── 📄 README.md  # Documentación del proyecto
│── 📄 ordenamiento.ipynb  # Implementación en Jupyter Notebook
```

## Instalación y Requisitos
Para ejecutar el proyecto, necesitas tener instalado:
- **Python 3.x**
- **Jupyter Notebook**
- **Librerías necesarias** (se pueden instalar con pip):
  ```bash
  pip install notebook
  ```

## Uso
1. Clona este repositorio:
   ```bash
   git clone https://github.com/Jair-Artreaga/Implementacion-Evaluacion-Algoritmos-Ordenamiento-Python.git
   ```
2. Accede al directorio del proyecto:
   ```bash
   cd Ordenamiento-Python
   ```
3. Ejecuta Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Abre el archivo `ordenamiento.ipynb` y ejecuta las celdas para ver los resultados.

## Pruebas de Rendimiento
Los algoritmos se prueban con conjuntos de datos de diferentes tamaños (100, 1000, 5000, 7500 y 10000 elementos). Se usa el módulo `timeit` para medir los tiempos de ejecución y analizar la eficiencia de cada método.

## Resultados
Los tiempos de ejecución se presentan en una tabla comparativa, mostrando que **Quicksort** es significativamente más rápido que **Burbuja** en grandes volúmenes de datos, lo que lo hace más adecuado para aplicaciones con alta demanda computacional.

## Contribuciones
Si deseas contribuir a este proyecto:
1. Haz un fork del repositorio.
2. Crea una rama con tus cambios: `git checkout -b nueva-funcionalidad`
3. Realiza un commit de los cambios: `git commit -m 'Añadir nueva funcionalidad'`
4. Sube los cambios: `git push origin nueva-funcionalidad`
5. Abre un Pull Request.

## Autor
**[Roberto Jair Arteaga Valenzuela]**
