ADR-001: Adoptar una arquitectura de microservicios
Estado

Aprobado.

Contexto

EduCloud debe soportar hasta 200.000 usuarios concurrentes, procesar simultáneamente clases en vivo, foros y evaluaciones, y permitir el crecimiento de la plataforma.

Opciones consideradas
Arquitectura monolítica.
Arquitectura en capas.
Arquitectura basada en microservicios.
Decisión

Se decide adoptar una arquitectura basada en microservicios, separando funcionalidades como autenticación, streaming, foros, evaluaciones, notificaciones y gestión de cursos.

Consecuencias
Beneficios
Permite escalabilidad horizontal.
Mejora la modularidad y mantenibilidad.
Facilita el desarrollo independiente por equipos.
Permite agregar nuevas funcionalidades.
Riesgos
Mayor complejidad operativa.
Necesidad de monitoreo avanzado.
Mayor complejidad en la comunicación entre servicios.
NFRs relacionados
Escalabilidad.
Disponibilidad.
Mantenibilidad.
