### Dataset utilizado: "Effects of Alcohol on Student Performance"
Espín Acevedo Luis Antonio

El objetivo de este dataset es predecir el promedio de un estudiante alcanzado en 2023 mediante distintas técnicas de predicción.
Posee las siguientes variables:
- Variable a predecir
    - Study_year_avg: promedio alcanzado en el año 2023 por el estudiante
        - 0 - 100
- Independientes
    - Sex: sexo del estudiante
        - [0, 1] : [femenino, masculino]
    - Matric_avg: promedio matricial del estudiante
        - 0 - 100
    - Study_year: año o grado actual (2023) que cursa el estudiante
        - [0, 1, ..., 4] : [1° año, 2° año, 3° año, 4° año, postgrado]
    - Faculty: facultad del grado del estudiante en la universidad.
        - [0, 1, ..., 7] : [AgriSciences, Arts & social science, Economics & management sciences, Education, Law, Medicine & Health sciences, Military science, Science, Theology]
    - Accom_status: cuenta con alojamiento privado o con alojamiento en la universidad de Stellenbosh
        - [0, 1] : [Privado, no privado]
    - Monthly_allowance: Prestaciones mensuales que recibe el estudiante
        - [0, 1, ..., 4] : [4001 - 5000, 5001 - 6000, 6001 - 7000, 7001 - 8000, >8000]
    - Scholarship: el estudiante se encuentra en un programa de financiación
        - [0, 1] : [Sí, no]
    - Wkly_stdy_hrs: horas semanales de estudio
        - [0, 1, ..., 4] : [0, 1-3, 3-5, 5-8, >8]
    - Drinks_per_night: cuántas bebidas alcohólicas consume el estudiante cuando sale de fiesta
        - [0, 1, ..., 4] : [0, 1-3, 3-5, 5-8, >8]
    - Missed_classes: cuántas clases ha faltado el estudiante por problemas causados por el alcohol (resaca, cansancio, otras)
        - [0, 1, ..., 4] : [0, 1, 2, 3, >4]
    - Failed_modules: cuántos módulos ha reprobado el estudiante en lo que lleva de sus estudios
        - [0, 1, ..., 4] : [0, 1, 2, 3, >4]
    - Approval: los padres del estudiante aprueban que el estudiante consuma bebidas alcohólicas
        - [0, 1] : [sí, no]
    - Parent_strength: qué tan cercana es la relación del estudiante con sus padres
        - [0, 1, 2, 3] : [Muy cercana, Cercana, poco cercana, distante]
