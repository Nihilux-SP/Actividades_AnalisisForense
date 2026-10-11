# Tabla Comparativa Normas

| Dimensión | RFC 3227 | NIST SP 800-86 | ENFSI BPM |
| :--- | :--- | :--- | :--- |
| **Qué entiende por identificar** | Determinar qué datos son más volátiles y capturarlos en orden antes de que la interferencia externa los destruya | Identificar es el punto de partida de un proceso estructurado: hay que rastrear sistemáticamente todas las "posibles fuentes de datos" | Identificar es la evaluación sistemática del escenario, los dispositivos y la configuración de red para preparar la recogida y el tratamiento posterior |
| **Fuentes de evidencia que menciona** | Registros/caché, tablas de rutas/caché ARP/tabla de procesos/estadísticas del kernel/memoria, sistemas de archivos temporales, disco, logs remotos, configuración física/topología de red, medios de archivo | Archivos, datos del sistema operativo, tráfico de red, datos de aplicaciones y otras fuentes posibles como dispositivos celulares | Configuración de dispositivos y red, datos de estado activo (memoria) |
| **Criterio para decidir qué se protege primero** | La volatilidad como lo principal, de lo más volátil a lo menos volátil | Evaluación combinada: valor del dato para el caso, velocidad de pérdida y grado de intrusión que supone la recogida | La decisión se basada en el contexto del caso, la capacidad del laboratorio y el estado operativo del sistema |
