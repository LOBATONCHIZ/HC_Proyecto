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

# Cronograma del Proyecto (18 noviembre – 11 diciembre)

| **Semana / Fechas** | **Actividad del proyecto** | **Qué se realiza en esta sección** | **Temas del curso utilizados** |
|---------------------|----------------------------|------------------------------------|--------------------------------|
| **Semana 1**<br>**18–23 noviembre** | **Inicialización del sistema** | - Elegir N, L, dt y masa<br>- Generar posiciones y velocidades iniciales<br>- Crear estructura del repositorio y Makefile<br>- Documento introducción + objetivos | - Python básico (Semana 1–3)<br>- Numpy 1D y 2D (Semana 2–3)<br>- Git y Makefiles (Semana 5)<br>- Probabilidad básica (Semana 11) |
| | **Configuración de MD (Dinámica Molecular)** | - Funciones para mover partículas<br>- Implementar rebotes en paredes<br>- Detectar colisiones simples<br>- Primer prototipo funcionando | - Ciclos y condicionales (Semana 3)<br>- Arreglos NumPy (Semana 2–3)<br>- Ecuaciones diferenciales simples (Semana 6–7) |
| **Semana 2**<br>**25–30 noviembre** | **Simulación MD completa** | - Implementar intercambios de velocidad<br>- Verificar conservación de energía<br>- Gráfica energía vs tiempo<br>- Primer histograma de velocidades | - Métodos numéricos (Semana 6–7)<br>- Matplotlib (Semana 2–4)<br>- Estadística básica (Semana 11) |
| | **Inicio del módulo MCMC** | - Proponer movimiento<br>- Calcular ΔU<br>- Aplicar regla Metropolis | - Probabilidad y estadística (Semana 11–12)<br>- Monte Carlo (Semana 12)<br>- Números pseudoaleatorios (Semana 11–12) |
| **Semana 3**<br>**2–6 diciembre** | **Finalizar MCMC** | - Estabilizar tasa de aceptación<br>- Medir distribución espacial<br>- Detectar equilibrio |  |
| | **Visualización** | - Histogramas MD vs Maxwell–Boltzmann<br>- Gráfica energía total<br>- Gráfica temperatura <br>- Animación 1D | - Matplotlib (Semana 2–4) |
| | **Comparación entre métodos** | - Comparar MD y MCMC<br>- Evaluar equilibrio<br>- Interpretación de resultados | |
| **Semana 4 (Cierre)**<br>**8–11 diciembre** | **Informe + presentación final** | - Redacción del documento final<br>- Preparación de diapositivas<br>- Pruebas finales del repositorio |  |
| | **Entrega final del proyecto** | - Subir versión final a GitHub<br>- Entregar código + reporte | - Síntesis de todos los temas del curso |
