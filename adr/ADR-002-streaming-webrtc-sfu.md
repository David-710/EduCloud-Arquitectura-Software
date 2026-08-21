ADR-002: Utilizar WebRTC con un servidor SFU para el streaming en vivo
Estado

Aprobado.

Contexto

EduCloud requiere clases interactivas con video en tiempo real y debe soportar una gran cantidad de conexiones simultáneas con baja latencia.

Opciones consideradas
Streaming tradicional.
Comunicación directa Peer-to-Peer.
WebRTC con servidor SFU.
Decisión

Se decide utilizar WebRTC con una arquitectura SFU para las clases en vivo, permitiendo gestionar y distribuir los flujos de video de manera eficiente.

Consecuencias
Beneficios
Baja latencia.
Mejor soporte para comunicación en tiempo real.
Mayor capacidad para escalar conexiones simultáneas.
Permite distribuir la carga entre servidores.
Riesgos
Mayor complejidad de infraestructura.
Costos más altos de operación.
Necesidad de monitoreo constante.
NFRs relacionados
Desempeño.
Escalabilidad.
Disponibilidad.
Seguridad.
