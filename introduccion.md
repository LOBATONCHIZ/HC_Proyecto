# Introducción

Este proyecto busca simular un gas ideal en una dimensión usando dos métodos diferentes: Dinámica Molecular y Monte Carlo tipo Metropolis. La idea es observar cómo evoluciona un grupo de partículas que se mueven y chocan entre sí, y cómo el sistema llega al equilibrio térmico.

En la parte de Dinámica Molecular, las partículas se mueven en línea recta y rebotan entre ellas y con las paredes. Esto permite observar cómo cambian las velocidades con el tiempo y si aparecen distribuciones como la de Maxwell Boltzmann.

En la parte de Monte Carlo, no se usa el tiempo. En su lugar, se generan configuraciones al azar y se aceptan o rechazan según una regla basada en la probabilidad de Boltzmann. Este método sirve para estudiar directamente el equilibrio.

El proyecto se realizará en Python y se llevará control mediante GitHub, usando Makefiles para ejecutar las diferentes partes del código.

Estructura sugerida:
- src/: código principal
- plots/: gráficas generadas
- docs/: documentos del proyecto
- Makefile
- requirements.txt
