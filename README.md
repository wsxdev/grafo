# Visualizador de Grafos Direccionales

Sistema de visualización de estructuras de datos tipo grafo utilizando JavaFX. La aplicación permite la gestión dinámica de nodos y aristas mediante un motor de simulación física basado en fuerzas.

## Características Principales

*   **Gestión de Estructuras**: Adición y eliminación en tiempo real de nodos y aristas direccionales.
*   **Layout Dinámico**: Implementación de un algoritmo Force-Directed que optimiza la distribución espacial de los elementos.
*   **Evasión de Superposiciones**: Sistema de repulsión Nodo-Arista que previene la obstrucción visual de los elementos del grafo.
*   **Interfaz Interactiva**: Soporte para zoom dinámico y ajuste automático del área de visualización.

## Requisitos Técnicos

*   Java Development Kit (JDK) 17 o superior.
*   Maven 3.6 o superior.
*   Biblioteca JavaFX compatible.

## Ejecución del Proyecto

Para iniciar la aplicación, utilice el siguiente comando desde la raíz del proyecto:

```bash
mvn javafx:run
```

## Detalles de Implementación

El núcleo del sistema utiliza un modelo de simulación física donde:
1.  Los nodos ejercen fuerzas de repulsión mutua para evitar solapamientos.
2.  Las aristas actúan como resortes que mantienen la cohesión estructural.
3.  Se aplica una gravedad central para mantener la estabilidad del grafo.
4.  Se implementa una fuerza de repulsión específica entre nodos y segmentos de arista para garantizar la legibilidad.
