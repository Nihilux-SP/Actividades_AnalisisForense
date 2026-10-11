#Lista de comprobación para la escena

###I. Al llegar (evaluación previa y preparación):

1. Averiguar el contexto: conocer el resumen del incidente, el rol del sistema y las posibles restricciones legales; confirmar el alcance de la autorización forense. [ENFSI BPM §9.1]

2. Anticipar datos volátiles: confirmar si hay cifrado, programas maliciosos en memoria o riesgo de borrado remoto. [ENFSI BPM §9.1]

3. Aislar las herramientas: preparar herramientas forenses que arranquen desde medios protegidos. [RFC 3227 §2.1]

4. Coordinar al personal: aclarar los roles de cada parte en la escena y valorar si se necesita al administrador del sistema para extraer datos concretos. [ENFSI BPM §9.2]

###II. Antes de tocar nada (control de la escena y documentación):

5. Controlar el flujo de personas: limitar la entrada y salida para evitar que alguien toque el teclado o el ratón y altere el estado del sistema. [ENFSI BPM §8.2]

6. Registrar el reloj del sistema: anotar de inmediato la hora actual del sistema objetivo y su desviación respecto a la hora estándar. [RFC 3227 §2.1]

7. Fotografiar todo: capturar la pantalla, el estado de los cables y el entorno físico como referencia para el análisis posterior. [ENFSI BPM §9.2]

8. Evaluar el "interruptor de hombre muerto": si hay que desconectar la red, valorar antes si eso dispara un borrado automático por parte del programa malicioso. [RFC 3227 §2.1]

9. Determinar el estado operativo: registrar si el sistema está encendido, si tiene red y si hay volúmenes cifrados montados. [ENFSI BPM §9.2]

###III. Decidir qué se adquiere y en qué orden (fase de ejecución):

10. Seguir el orden de volatilidad: operar en la secuencia registros/caché → memoria → sistemas de archivos temporales → disco. [RFC 3227 §2.1]

11. Capturar el estado de red: registrar primero tablas de rutas, caché ARP, conexiones activas y puertos a la escucha. [RFC 3227 §2.1]

12. Fijar la imagen de memoria: obtener la imagen de memoria física con herramientas validadas antes de adquirir el disco. [RFC 3227 §2.1]

13. Ampliar el rastreo de fuentes: no mirar solo el equipo principal; revisar dispositivos periféricos, servidores de logs remotos y rastros en servicios cloud. [NIST SP 800-86 §3.1.1]

14. Evaluar el cifrado de disco: si el volumen ya está desbloqueado, priorizar la obtención de una imagen lógica o del volumen descifrado. [ENFSI BPM §9.2]

15. Evitar escrituras: no ejecutar programas que modifiquen la fecha de acceso a los archivos (como tar o xcopy). [RFC 3227 §2.1]

16. Documentar cada paso: registrar de forma sincronizada cada operación y su efecto sobre el sistema. [NIST SP 800-86 §3.1]

17. Establecer prioridades: si coexisten varios dispositivos, ordenar la recogida según el valor del dato y su velocidad de desaparición. [ENFSI BPM §9.2]

###IV. Durante la adquisición (normas de actuación):

18. Arranque desde almacenamiento externo: ejecutar todas las herramientas desde medios de solo lectura para no contaminar el sistema objetivo. [RFC 3227 §2.1]

19. Verificación por hash: calcular y registrar el hash de cada imagen obtenida inmediatamente después de su adquisición. [NIST SP 800-86 §3.1]

20. Mantener la cadena de custodia: asegurar que cada traslado de la evidencia, desde la recogida hasta el almacenamiento, quede firmado y registrado. [NIST SP 800-86 §3.1]

21. Embalaje y etiquetado: proteger contra escritura el medio original tras la adquisición e indicar claramente su procedencia. [ENFSI BPM §9.2]

###V. Antes de abandonar la escena (confirmación final):

22. Confirmar la exhaustividad: repasar la lista y verificar que se han cubierto todas las fuentes de datos volátiles previstas. [RFC 3227 §2.1]

23. Evaluar si quedan sistemas asociados: comprobar si hay otros dispositivos en línea (móviles, discos externos) que deban procesarse también. [NIST SP 800-86 §3.1.1]

24. Registrar el estado final de la escena: fotografiar el estado físico final antes de mover o apagar el sistema. [ENFSI BPM §8.2]
