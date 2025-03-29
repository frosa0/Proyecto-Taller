---
creation date: 2024-24-02 15:02 
---



**[[HOME| Home]]** | [[Facu| Facu]] | [[Proyectos/Proyectos | Proyectos]] | [[Resources/Resources |Resources]]  | [[Facu/Taller de Sistemas Digitales/Taller de Sistemas Digitales.md|Taller de Sistemas Digitales]]


# Proyecto de Taller de Sistemas Digitales

### Acta de constitución de Proyecto

*Visión general del proyecto*: Desarrollar un sistema de seguimiento solar que optimice la captacion de energia, controlando la orientacion del panel solar segun la posicion del sol y transmitiendo la informacion generada a traves de una interfaz accesible.

*Objetivos*: 
* General: sistema de control de panel solar. Se propone como proyecto la creación de un sistema que rote siguiendo la trayectoria del sol, con el fin de obtener la mayor potencia instantánea posible. Este sistema busca mejorar la eficiencia en comparacion con los paneles solares estáticos. Las medidas de potencia, y su horario de medición, van a ser almacenadas y transmitidas para luego ser visualizadas en una interfaz gráfica que incluirá gráficos adicionales y datos históricos de la eficiencia del panel.

* Particular: se desarrollaran los siguientes apartados
    * Sistema de rotacion 
    * Manejo de energia del micro
    * Circuito de medidion de potencia
    * Desarrollo de Comunicacion entre dispositivos
    * Creacion de Interfaz grafica para movil
    * Programacion de sistema de control 

*Especificaciones y Alcance*:
* Requisito funcional: El sistema debe ser capaz de ajustar su posición adaptándose a los cambios de incidencia solar para obtener la máxima potencia posible. Deberá ser capaz de medir correctamente la potencia para luego transmitir esos datos via bluetooth una interfaz grafica accesible desde una aplicacion de celular.
* No funcional:  el sistema debe ser eficiente energeticamente a comparacion de un tipico panel solar estatico, donde la potencia adicional obtenida con este proyecto sea apreciable  (rendimiento).  El sistema debe ser robusto y capaz de operar durante largos periodos de tiempo sin fallas (seguridad y fiabilidad). La interfaz grafica intuitiva para operarios tipo hmi (? (Usabilidad). Sentara una base confiable para posibles proyectos a futuro de mayores dimensiones, con paneles de mayor potencia y motores mas grandes; o escalando la producción del proyecto mantiendo las dimensiones originales. Ambos casos resguardando los criterios originales preservando una buena eficiencia energetica y el manejo de datos. (escalabilidad)
* Alcance: El proyecto abarcará desde el diseño y fabricación del hardware (panel solar, sensores, microcontrolador, motores, etc.) hasta el desarrollo de un software que permita controlar y monitorizar el sistema. El proyecto no incluirá la producción en masa del sistema, solo un prototipo funcional y operativo.


*Entregables*: 
Prototipo final ensamblado, codigo fuente del microcontrolador, interfaz grafica, breve documentacion de uso y resultados de pruebas obtenidos. Bitacora de desarrollo.

*Calendario General*:

| Fase                               | Duración Estimada | 
|------------------------------------|-------------------|
| Planificación y Diseño Inicial     | 2 semanas         | 
| Desarrollo de Hardware             | 2 semanas         | 
| Desarrollo de Software             | 2 semanas         | 
| Fabricación de Prototipo           | 2 semanas         | 
| Pruebas y Acondicionamiento        | 2 semanas         | 
| Implementación de Interfaz Gráfica | 2 semanas         | 
| Puesta a punto y entrega final     | 2 semana          | 

*Presupuesto estimado:*

| Concepto                   | Costo Estimado |
| -------------------------- | -------------- |
| Sensor de potencia         |                |
| Panel solar                |                |
| Servo o motor paso a paso  |                |
| Soporte pivote             |                |
| Microcontrolador Atmega328 |                |
| ESP32                      |                |
| Foto diodos                |                |
| RTC (reloj de tiempo real) |                |
|  Bateria                   |                |
| **Total Estimado**         |                | 

### Planificado Nación y gestión de Proyecto

*Ciclo de vida*: ciclo de vida híbrido. Semi-flexible. Implementación clara y particular. Los alcances del proyecto son especificados al inicio del mismo. No se espera hacer grandes ajustes, pero se espera adaptabilidad a los plazos.

*Organización del equipo de trabajo*: implementación de tareas rotativas.

*Desglose de actividades*:

* Primera etapa de planificación: propósito, materiales, costos, cronograma, recopilación de información, división de tareas. (qué vas a hacer, cuánto vas a tardar en hacerlo).
* Segunda etapa de planificación (qué necesitas, ej materiales cronogramas, recopilación de información). Realización de planos y esquemas.
* Obtención de insumos.
* Desarrollo de software de etapa temprana.
* Realización de maquetas y protototipos
* Acondicionamiento y etapa de pruebas.
* Etapa alfa.
* Puesta a punto y modificaciones fina.
* Entrega del proyecto final.

*Adquisiciones*: 

* Sensor de potencia
* Panel solar.
* Servo o motores paso a paso.
* Soporte pivote.
* Microcontrolador Atmega.
* ESP32 (transmisor de datos).
* Foto diodos.
* RTC