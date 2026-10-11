# Plan Almadraba

## 1. Las fuentes de evidencia
### En la mesa de Marta (acceso directo):

|  | Evidencia | Qué puede contener |
| :--- | :--- | :--- |
| 1 | **RAM del Dell** (encendido, pantalla bloqueada) | Procesos activos, conexiones de red, credenciales en memoria, archivos abiertos, posible actividad reciente |
| 2 | **Disco interno del Dell** (BitLocker) | Archivos del proyecto, historial de navegación, registro de eventos, archivos borrados, OneDrive local |
| 3 | **Disco externo negro de 2 TB** (conectado al dock) | Copias locales, exportaciones de proyectos, posible exfiltración |
| 4 | **iPhone de empresa** | WhatsApp con clientes, correo, contactos, posible uso personal indebido |
| 5 | **Móvil personal en el bolso** | Elena dice que no hay nada del trabajo, pero podría contener comunicaciones con Lucía |
| 6 | **Dock USB-C** | Registros de conexión, posible almacenamiento temporal |
| 7 | **Sesión abierta de Outlook web** en el sobremesa de entrada | Sesión de otra compañera, posible acceso cruzado, historial de impresión/escaneo |
| 8 | **Pendrive devuelto a Javier** (en su cajón) | Archivos copiados por Marta el día 14, posible evidencia de exfiltración |
| 9 | **Impresora multifunción** | Historial de trabajos, escaneos directos a correo, posible registro de documentos impresos |

### En el cuartito de informática:

| # | Evidencia | Qué puede contener |
| :--- | :--- | :--- |
| 10 | **Servidor de ficheros** | Documentos de proyectos, registros de acceso, permisos, fechas de modificación |
| 11 | **NAS de copias de seguridad** (últimas 14 noches) | Versiones anteriores de archivos, posible recuperación de datos borrados o modificados |
| 12 | **Cortafuegos** | Registro de conexiones (aproximadamente una semana), posible tráfico hacia servicios cloud o IPs externas |

### En la nube y en terceros:

| # | Evidencia | Qué puede contener |
| :--- | :--- | :--- |
| 13 | **OneDrive** (sincronización de documentos) | Historial de versiones, registros de acceso, posible descarga masiva |
| 14 | **Portal de Microsoft** (claves de recuperación BitLocker) | Acceso al disco si se apaga el portátil |
| 15 | **VPN de Bahía Sistemas** | Registros de conexión remota, posible acceso desde casa |
| 16 | **Proveedor de correo** | Correos enviados/recibidos, posibles reenvíos |
| 17 | **WhatsApp / operador móvil** | Comunicaciones entre Marta y Lucía, si hay autorización judicial |
| 18 | **Cámara domo del pasillo** (gestionada por la comunidad) | Grabación de acceso al edificio, posible identificación de personas |
| 19 | **Registros del edificio / conserjería** | Control de acceso, visitantes, posibles grabaciones |

### En manos de terceros:

| # | Fuente | Qué puede contener |
| :--- | :--- | :--- |
| 20 | **Javier** (compañero) | Testimonio sobre la noche del 14, el pendrive, la relación con Lucía |
| 21 | **Elena Ruiz** (gerente) | Testimonio sobre la exclusiva, la relación comercial, la autorización |
| 22 | **Bahía Sistemas** (consultora) | Registros de mantenimiento, configuración de red, posibles accesos remotos |
| 23 | **Lucía Navarro / estudio de Sevilla** | Propuesta con el render, posible origen de la filtración |
| 24 | **Cadena hotelera** | Render presentado en exclusiva, posible fecha de recepción |

---

## 2. La prioridad

### Prioridad 1 — Se pierde en minutos u horas:

| Orden | Evidencia | Por qué |
| :--- | :--- | :--- |
| 1 | **RAM del Dell** | Si se apaga o se bloquea más tiempo, se pierde. Contiene procesos, conexiones y posible actividad reciente |
| 2 | **Sesión de Outlook web** en el sobremesa | Puede cerrarse sola, caducar o ser cerrada por la compañera. Es una ventana a otra cuenta |
| 3 | **Cortafuegos** | Se va pisando; aguanta aproximadamente una semana. Ya han pasado seis días desde el jueves 14 |
| 4 | **Cámara domo del pasillo** | Grabación en conserjería, posible retención corta, gestionada por terceros |
| 5 | **Disco externo de 2 TB** | Conectado y accesible; si se desconecta o se cifra, cambia el escenario |

### Prioridad 2 — Se pierde en días:

| Orden | Evidencia | Por qué |
| :--- | :--- | :--- |
| 6 | **Historial de la impresora** | No sé cuánto guarda; puede borrarse por ciclos automáticos |
| 7 | **OneDrive** | Historial de versiones y registros de acceso; puede tener retención limitada |
| 8 | **NAS de copias** | Conserva 14 noches; si pasa una noche más, se pierde la copia más antigua |
| 9 | **Servidor de ficheros** | Registros de acceso y fechas de modificación; pueden rotar |
| 10 | **VPN de Bahía** | Registros de conexión remota; pueden rotar o sobrescribirse |
| 11 | **Pendrive de Javier** | Está en su cajón; puede usarse, borrarse o perderse |
| 12 | **Móvil personal de Marta** | Ella puede borrar mensajes o restaurar el teléfono |
| 13 | **iPhone de empresa** | Puede recibir órdenes de borrado remoto o perder datos por sincronización |

### Prioridad 3 — Se pierde en semanas o requiere autorización:

| Orden | Evidencia | Por qué |
| :--- | :--- | :--- |
| 14 | **Disco interno del Dell (BitLocker)** | Si se apaga, necesita clave de recuperación; si no, se puede adquirir en vivo |
| 15 | **Portal de Microsoft** | Claves de recuperación; acceso controlado por Bahía |
| 16 | **Proveedor de correo** | Requiere solicitud formal; retención variable |
| 17 | **WhatsApp / operador** | Requiere autorización judicial; retención limitada |
| 18 | **Lucía Navarro / estudio de Sevilla** | Tercero; requiere requerimiento formal |
| 19 | **Cadena hotelera** | Tercero; requiere solicitud formal |
| 20 | **Testimonios** | Se pueden recoger cuando sea, pero la memoria se degrada |

---

## 3. Las medidas inmediatas

Para cada fuente, qué haría ahora mismo para que no se pierda ni se altere.

### En la mesa de Marta:

| Evidencia | Medida inmediata |
| :--- | :--- |
| **RAM del Dell** | No apagar. Aislar la red (desconectar cable/WiFi si es seguro). Capturar memoria con herramienta forense desde medio externo. Fotografiar pantalla y estado antes. |
| **Disco interno del Dell** | No apagar. Si se puede, adquirir imagen en vivo. Si hay que apagar, obtener antes la clave de recuperación BitLocker del portal de Microsoft. |
| **Disco externo de 2 TB** | No desconectar sin antes documentar. Adquirir imagen antes de cualquier otra operación. |
| **iPhone de empresa** | Aislar de la red (modo avión). No borrar. Documentar estado. Solicitar preservación de datos a Microsoft/Apple si es necesario. |
| **Móvil personal** | No tocar sin autorización. Documentar que existe. Si hay autorización, aislar y preservar. |
| **Dock USB-C** | Fotografiar conexiones. No desconectar hasta documentar. |
| **Sesión de Outlook web** | Fotografiar pantalla. No cerrar sesión. Documentar la sesión abierta. |
| **Pendrive de Javier** | Solicitar a Javier que lo entregue. Documentar cadena de custodia. No usarlo. |
| **Impresora multifunción** | Acceder al historial de trabajos. Exportar registros. Fotografiar pantalla. |

### En el cuartito de informática:

| Evidencia | Medida inmediata |
| :--- | :--- |
| **Servidor de ficheros** | Solicitar a Bahía que preserve registros de acceso. No modificar. Documentar configuración. |
| **NAS de copias** | Solicitar a Bahía que no sobrescriba. Preservar las 14 copias actuales. Documentar. |
| **Cortafuegos** | Solicitar a Bahía que exporte los registros YA. Es lo más urgente del cuartito. Documentar. |

### En la nube y en terceros:

| Evidencia | Medida inmediata |
| :--- | :--- |
| **OneDrive** | Solicitar a Bahía que active retención legal (legal hold) si es posible. Documentar. |
| **Portal de Microsoft** | Solicitar a Bahía las claves de recuperación BitLocker. Documentar. |
| **VPN de Bahía** | Solicitar registros de conexión remota de los últimos 30 días. Documentar. |
| **Proveedor de correo** | Preparar solicitud formal de preservación. Documentar. |
| **WhatsApp / operador** | Preparar solicitud judicial. Documentar. |
| **Cámara domo** | Solicitar a la administración de la comunidad que preserve la grabación del 14 y días posteriores. Documentar. |
| **Conserjería** | Solicitar registros de acceso. Documentar. |

### En manos de terceros:

| Fuente | Medida inmediata |
| :--- | :--- |
| **Javier** | Entrevistar. Documentar testimonio. Solicitar el pendrive. |
| **Elena Ruiz** | Entrevistar. Documentar autorización y contexto. |
| **Bahía Sistemas** | Llamar de nuevo. Solicitar preservación de logs. Documentar. |
| **Lucía Navarro** | No contactar directamente. Preparar requerimiento formal. |
| **Cadena hotelera** | Preparar solicitud formal. Documentar. |

---

## 4. Los límites:

Qué no puedo tocar o no puedo tocar todavía, por qué, y qué haría en su lugar.

| Límite | Por qué | Qué haría en su lugar |
| :--- | :--- | :--- |
| **No puedo apagar el Dell** | BitLocker: si se apaga, necesito la clave de recuperación. Además, la RAM se pierde. | Capturar memoria en vivo. Obtener clave BitLocker antes de cualquier apagado. |
| **No puedo tocar el móvil personal de Marta** | Es personal, no de empresa. Requiere autorización específica o judicial. | Documentar que existe. Solicitar autorización. Si no, no tocarlo. |
| **No puedo acceder al portal de Microsoft** | Es de Bahía. No tengo credenciales. | Solicitar a Bahía las claves de recuperación. Documentar la petición. |
| **No puedo tocar el cortafuegos** | Es de Bahía. No tengo acceso. | Solicitar a Bahía que exporte los logs YA. Documentar. |
| **No puedo tocar el NAS** | Es de Bahía. No tengo acceso. | Solicitar a Bahía que preserve las copias. Documentar. |
| **No puedo tocar el servidor de ficheros** | Es de Bahía. No tengo acceso. | Solicitar a Bahía que preserve registros. Documentar. |
| **No puedo tocar la cámara domo** | Es de la comunidad, no de Almadraba. | Solicitar a la administración que preserve la grabación. Documentar. |
| **No puedo contactar a Lucía Navarro** | Es tercera, posible responsable. Contactarla podría alertarla. | Preparar requerimiento formal. No contactar directamente. |
| **No puedo contactar a la cadena hotelera** | Es tercera, posible afectada. | Preparar solicitud formal. Documentar. |
| **No puedo acceder al correo de la compañera** | Es de otra persona. La sesión abierta es un descuido, no una autorización. | Fotografiar la pantalla. Documentar. No acceder a más. |
| **No puedo usar el pendrive de Javier** | Puede contener evidencia. Usarlo la alteraría. | Solicitar a Javier que lo entregue. Documentar cadena de custodia. |
| **No puedo entrevistar a Marta como sospechosa** | No soy policía. No hay detención. | Documentar su estado. No interrogarla. Derivar a quien corresponda. |
| **No puedo registrar el móvil de empresa sin autorización** | Es de empresa, pero puede contener datos personales. | Documentar. Solicitar autorización. Preservar. |
| **No puedo acceder a WhatsApp sin autorización judicial** | Requiere orden judicial. | Preparar solicitud. Documentar. |
| **No puedo hacer una imagen forense del Dell sin herramienta validada** | Alteraría la evidencia. | Usar herramienta validada desde medio externo. Documentar. |

---

## 5. De dónde sale cada decisión:

| Decisión | Punto de la lista | Norma y apartado |
| :--- | :--- | :--- |
| Capturar RAM antes que disco | 10, 12 | RFC 3227 §2.1 |
| No apagar el Dell | 8, 9 | RFC 3227 §2.1; ENFSI BPM §9.2 |
| Obtener clave BitLocker antes de apagar | 14 | ENFSI BPM §9.2 |
| Aislar red si es seguro | 8 | RFC 3227 §2.1 |
| Fotografiar pantalla y estado | 7, 24 | ENFSI BPM §9.2; §8.2 |
| Documentar cada paso | 16 | NIST SP 800-86 §3.1 |
| Solicitar logs del cortafuegos YA | 13, 17 | NIST SP 800-86 §3.1.1; RFC 3227 §2.1 |
| Solicitar preservación de OneDrive | 13 | NIST SP 800-86 §3.1.1 |
| Solicitar preservación del NAS | 13 | NIST SP 800-86 §3.1.1 |
| Solicitar preservación de VPN | 13 | NIST SP 800-86 §3.1.1 |
| Solicitar grabación de cámara | 13 | NIST SP 800-86 §3.1.1 |
| Entrevistar a Javier | 4 | ENFSI BPM §9.2 |
| No tocar móvil personal | 4 | ENFSI BPM §9.1 |
| No contactar a Lucía | 4 | ENFSI BPM §9.1 |
| Cadena de custodia del pendrive | 20, 21 | NIST SP 800-86 §3.1 |
| Hash de imágenes | 19 | NIST SP 800-86 §3.1 |
| Herramienta desde medio externo | 18 | RFC 3227 §2.1 |
| Evaluar “interruptor de hombre muerto” | 8 | RFC 3227 §2.1 |
| Confirmar exhaustividad antes de salir | 22 | RFC 3227 §2.1 |
| Evaluar sistemas asociados | 23 | NIST SP 800-86 §3.1.1 |
| Registrar estado final | 24 | ENFSI BPM §8.2 |
| No interrogar a Marta | 4 | ENFSI BPM §9.1 |
| Solicitar autorización para móvil personal | 4 | ENFSI BPM §9.1 |
| Preparar solicitud judicial para WhatsApp | 4 | ENFSI BPM §9.1 |
| Documentar sesión de Outlook abierta | 7 | ENFSI BPM §9.2 |
| No usar el pendrive | 20 | NIST SP 800-86 §3.1 |
| Preservar 14 copias del NAS | 13 | NIST SP 800-86 §3.1.1 |
| Exportar historial de impresora | 13 | NIST SP 800-86 §3.1.1 |

## Explicación a Elena:

**¿Qué hay que proteger ahora mismo?**

La memoria del portátil de Marta, porque si se apaga se pierde. El disco externo de 2 TB que tiene conectado. El iPhone de empresa. El pendrive que Javier guarda en su cajón. La sesión de Outlook abierta en el ordenador de entrada. Y el historial de la impresora.

**¿Qué se puede perder si esperamos?**

El cortafuegos se va pisando y aguanta una semana; ya han pasado seis días. La grabación de la cámara del pasillo puede borrarse sola. El NAS conserva catorce noches: una más y se pierde la copia más antigua. OneDrive y los registros de la VPN pueden rotar. El móvil personal de Marta puede borrarse en cualquier momento.

**¿Qué hay que pedir a otros?**

A Bahía: los registros del cortafuegos ya, las claves de recuperación de BitLocker, los registros de la VPN y que preserve el NAS y OneDrive. A la administración de la comunidad: la grabación de la cámara del día 14 y posteriores. Al proveedor de correo y a WhatsApp: preservación formal. A Lucía Navarro y a la cadena hotelera: requerimiento formal, sin contactarlas directamente.

**Qué no voy a tocar**

El móvil personal de Marta sin autorización. El correo de la compañera. El pendrive de Javier, salvo para custodiarlo. A Marta no la voy a interrogar. No apagaré el Dell hasta tener la clave de BitLocker y la memoria capturada.
