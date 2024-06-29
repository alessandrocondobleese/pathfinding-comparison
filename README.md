# Pathfinding comparison

## Descripción del Proyecto

Este proyecto implementa y compara varios algoritmos de búsqueda de rutas en grafos utilizando datos geográficos de OpenStreetMap. Los algoritmos implementados son Dijkstra, A*, y colonia de hormigas. Los resultados se visualizan mediante gráficos generados con `osmnx` y `matplotlib`.

## Requisitos

Para ejecutar este proyecto, necesitas `conda` para manejar el entorno y las dependencias. Asegúrate de tener `conda` instalado y sigue los siguientes pasos:

### Crear el Entorno

```bash
conda create --name pathfinding-env --file requirements.txt
```

### Activar el Entorno
```bash
conda activate pathfinding-env
```

## Archivos Necesarios

	•	requirements.txt: Contiene todas las dependencias necesarias para ejecutar el proyecto.

## Uso

	1.	Abre el archivo del Jupyter Notebook en VSCode.
	2.	Ejecuta cada celda del notebook para obtener y procesar datos geográficos, crear el grafo y aplicar los algoritmos de búsqueda de rutas.
	3.	Los resultados se guardarán en forma de gráficos y videos que muestran el proceso de búsqueda de rutas.

## Algoritmos Implementados

	•	Dijkstra
	•	A*
	•	Colonia de Hormigas

## Videos

| Algoritmo          | Video                  |
|--------------------|------------------------|
| Dijkstra           | [Dijkstra](dijkstra.mp4) |
| A*                 | [A*](a_star.mp4) |
| Colonia de Hormigas | [Colonia de Hormigas](ant_colony.mp4) |

Los resultados se pueden visualizar mediante gráficos y animaciones generadas con matplotlib. Los graficos en la carpteta frames, mientras que las animaciones se generaran como videos en la raiz del proyecto