---
layout: post
title: S5 Actividad 2 Análisis y abstracción de información
date: 2019-05-10 14:15 +0000
categories: basic
comments: true
---

### Antecedentes

__Generador de horarios usando el algoritmo Tabu Search__

En el 2015 estudiantes de la _Southeast University_  --en Banani, Dhaka-- realizaron una investigación cuya finalidad era ayudar con la creación de horarios para las materias y exámenes de la mencionada universidad. Las bases de esta investigación se centraban en el uso de el algoritmo __Tabu Search__ (Islam et al. 2016) el cual sirve para resolver problemas de optimización.

Este algoritmo parte con la resolución del problema con un resultado subóptimo para después proceder desde ese punto una y otra vez hasta mejorar el resultado.

__Generador de horarios mediante el uso de algoritmos genéticos__

El sistema desarrollado por el departamente de ciencias de la computación de la _Covenant University_ generó una solución viable para resolver el problema de _generación de horarios_ a través del uso de algoritmos genéticos (Colorni, Dorigo, and Maniezzo 1994) pero solo mediante la captura de restricciones y requerimientos dadas por el usuario.

__EAH__

_Elaborador Automático de Horarios_ o EAH (Gervás and San 2019), es un sistema desarrollado por miembros del Departamento de Inteligencia Artificial  de la Universidad Europea de Madrid. La intención de este proyecto es automatizar la generación de horarios de la Escuela Superior de Informática de la Universidad  Europea  de  Madrid.

Este es un _sistema experto_ que aprovecha los datos previos de horarios y parte de estos para encontrar una una solución y así constantemente se nutrirá de datos previos para mejorar.

El proyecto fue un prototipo y su aplicación para un entorno real está sujeto a la aprobación de expertos.

### Bases teóricas

El tema de la _generación de horarios_, desde el punto de vista de la informática, es ya muy conocido y está dentro de la clase de problemas a los que se les denomina _NP-completos_ (_teoría de la complejidad_), lo que quiere decir que no existe un método de resolver el problema en un tiempo razonable.

Por ello efrentar este tipo de problemas requiere limitar las variables y someterlas a una serie de reglas que a su vez también deben de ser las menos posibles.

Sin embargo, y a pesar de que el problema de complejidad es real, la asignación de horarios no requiere una resolución perfecta si no una que sea buena.

También es un hecho documentado que el problema de _generación de horarios_ ya ha sido resuelto --bajo ciertas restricciones-- sin embargo los resultados en cuestión de tiempo de resolución aún deja espacio para mejora.

### Referencias

Colorni, Alberto, Marco Dorigo, and Vittorio Maniezzo. 1994. “A Genetic Algorithm to Solve the TimetableProblem,” July.

Gervás, Pablo, and Beatriz San. 2019. “Un Sistema Experto Basado En Reglas Para La Automatización deLa Elaboración de Horarios Para Un Conjunto de Restricciones Particulares,” May.

Islam, Tanzila, Mohammad Anower Perves, Zunayed Shahriar, and Monirul Hasan. 2016. “UniversityTimetable Generator Using Tabu Search.”Journal of Computer and Communications4 (December): 28–37.https://doi.org/10.4236/jcc.2016.416003.2

[Decargar en PDF](https://res.cloudinary.com/dfhxsuwjv/image/upload/v1557633658/marco-teorico_zr9fsf.pdf)
