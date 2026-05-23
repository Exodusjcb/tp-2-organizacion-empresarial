# TP 2: Organización Empresarial - Simulación de Entorno de Desarrollo

Este proyecto consiste en una simulación práctica de un flujo de trabajo profesional utilizando Git, GitHub, Google Colab y Jira, emulando los roles y procesos típicos de un equipo de desarrollo de software.

## 👥 Integrantes y Roles
* Hugo (Líder / Tech Lead): Coordinación del proyecto, revisión de código y aprobación del Pull Request final.
* Paco (Desarrollador): Creación de la estructura de directorios, desarrollo del script de análisis de ventas y preparación del entorno.
* Luis (QA / Aseguramiento de Calidad): Verificación de la estabilidad del entorno, pruebas de integración del script y mejoras de documentación.

## 📁 Estructura del Proyecto
* `/datos`: Contiene las bases de datos de origen (`ventas.csv`).
* `/scripts`: Aloja el código fuente principal de procesamiento (`analisis_ventas.py`).
* `/resultados`: Almacena los reportes y visualizaciones generadas (`grafico_ventas.png`, `resumen.txt`).
* `.gitignore`: Archivo de configuración para omitir archivos temporales en el repositorio.

## 🔄 Flujo de Trabajo Simulado
1. **Inicialización:** Clonación del repositorio base en el entorno de Google Colab.
2. **Desarrollo:** Creación de la rama secundaria `feature/desarrollo-analisis` para el aislamiento del código del script.
3. **Control de Calidad:** Revisión integral por el rol de QA, aplicando mejoras de documentación técnica directamente sobre la rama de características.
4. **Integración:** Apertura de un Pull Request (PR) en GitHub, debate técnico del equipo mediante hilos de discusión y merge final controlado hacia la rama principal `main`.

