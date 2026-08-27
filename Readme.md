Trabajo Práctico 1: Programación Orientada a Objetos en Java
Materia: Sistema operativo Alumno: [Oscar] Comisión: 2K7

Resumen o descripción del trabajo

Este proyecto consiste en el desarrollo de un sistema informático orientado a objetos para la gestión y administración de eventos universitarios. A través de este sistema, es posible registrar eventos (como jornadas o hackathones), asignarles espacios físicos (Salas) y estructurar una agenda de actividades específicas (Charlas y Talleres). Además, el sistema gestiona la matriculación de alumnos a dichas actividades. El desarrollo aplica progresivamente los pilares fundamentales de la Programación Orientada a Objetos (POO): encapsulamiento, composición, agregación, herencia y polimorfismo.

Consignas del Trabajo Práctico (Diseño Estilizado)

🔹 Ejercicio 1: Fundamentos de la POO

Misión: Construir el cimiento del sistema modelando la clase EventoUniversitario.
Requisitos: Aplicar correctos niveles de encapsulamiento, desarrollar constructores (incluyendo un constructor de copia para clonar eventos), manejar un contador estático para las métricas de clase y crear métodos para calcular costos estimados.

🔹 Ejercicio 2: Escalabilidad y Relaciones

Misión: Integrar el evento en un ecosistema de objetos que interactúan entre sí.
Requisitos: Implementar las clases Sala, Actividad, Estudiante e Inscripcion. Materializar las relaciones: el Evento agrega una Sala y compone múltiples Actividades. A su vez, las actividades inscriben a diferentes Estudiantes.

🔹 Ejercicio 3: Herencia y Polimorfismo

Misión: Especializar las actividades garantizando un diseño escalable y la reutilización de código.
Requisitos: Transformar Actividad en una clase abstracta madre. Derivar de ella las clases concretas Charla (gratuitas) y Taller (con costos variables si usan notebook). Refactorizar el cálculo de presupuestos utilizando comportamiento polimórfico y asegurar identificadores de actividad inmutables mediante métodos final.

🔹 Ejercicio 4: Mapa de Memoria de Ejecución

Misión: Comprender la arquitectura interna y la gestión de memoria de la JVM.
Requisitos: Diseñar un mapa gráfico que demuestre cómo interactúan el Stack (variables locales del método main) y el Heap (objetos instanciados). Debe reflejar claramente las diferencias estructurales entre una agregación (Sala-Evento), una composición (Actividad-Evento) y las jerarquías de herencia.

Pautas y Forma de Entrega

Repositorio: Crear un repositorio público en GitHub nombrado PP_TP1_legajo.
Contenido Requerido:
Código fuente del proyecto (idealmente estructurado en IntelliJ IDEA), listo para ser clonado.
Este archivo README.md documentando el software.
Imagen gráfica del mapa de memoria (Ejercicio 4).
Captura de pantalla evidenciando la correcta ejecución del código en consola.
Entrega Final: Subir la URL (HTTPS) de clonación del repositorio en el apartado correspondiente del aula virtual. Aviso: Modificaciones posteriores a la fecha de cierre invalidan la entrega.