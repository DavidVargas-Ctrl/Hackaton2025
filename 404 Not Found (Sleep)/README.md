
# 💧 YAKU

## 🔹 Nombre del proyecto  
**YAKU** – Sistema comunitario de alerta temprana y prevención ante inundaciones rurales.

---

## 🔹 Descripción breve  
**YAKU** es un sistema de **alerta temprana y monitoreo del nivel del agua**, diseñado para comunidades rurales con acceso limitado a internet, como la vereda **La Esmeralda (Tocancipá, Cundinamarca)**.  
El proyecto busca **reducir el riesgo de inundaciones** mediante sensores LoRa de bajo consumo y un modelo de comunicación híbrido (WhatsApp y SMS) que garantiza la notificación incluso sin conexión a internet.  
Su **propuesta de valor** integra una **cola asíncrona** que almacena los mensajes de alerta cuando no hay conectividad y los envía automáticamente cuando esta se restablece.

---

## 🔹 Nivel de desarrollo  
**Etapa:** Prototipo funcional (en simulación).  
Actualmente, el modelo **funciona de manera completa a nivel lógico y digital**, incluyendo:  
- Página web operativa para monitoreo.  
- Componente de procesos y recolector de datos de sensores.  
- Integración con **Twilio** para envío de alertas por **WhatsApp y SMS**.  
- Base de datos activa en **Supabase**.  
- Simulación de lectura de sensores **LoRa** y procesamiento de datos.  

La **estructura física (instalación real de sensores y hub LoRa)** aún no se ha implementado; se encuentra en etapa de diseño.

---

## 🔹 Video de presentación  
🔗 [Pendiente de enlace al video demo o pitch de YAKU](#)

---

## 🔹 Ventajas o fortalezas  
1. **Accesibilidad total:** opera incluso sin conexión a internet gracias a la cola asíncrona y al uso de **mensajes SMS**.  
2. **Tecnología sostenible:** sensores **LoRa** de bajo consumo energético y amplia cobertura sin necesidad de red móvil.  
3. **Enfoque comunitario:** diseñado para comunidades rurales, sin necesidad de conocimientos técnicos.  
4. **Escalabilidad y replicabilidad:** fácilmente adaptable a otras zonas rurales o tipos de riesgo (sequías, deslizamientos, etc.).

---

## 🔹 Desventajas o debilidades  
1. **Dependencia de los sensores físicos:** posibles daños por humedad, golpes o deterioro en ambientes extremos.  
2. **Falta de infraestructura física instalada:** el sistema aún no se ha probado en campo real.  
3. **Mantenimiento técnico eventual:** se requiere revisión periódica del hardware una vez implementado.

---

## 🔹 Detalles técnicos  

### Lenguajes y tecnologías  
- **Framework:** Next.js 13.5.1  
- **Lenguaje:** TypeScript  
- **Estilos:** Tailwind CSS  
- **Componentes UI:** Radix UI  
- **Gráficos:** Recharts  
- **Base de Datos:** Supabase  
- **Automatización de flujos:** n8n  
- **API de mensajería:** Twilio (WhatsApp/SMS)  
- **Comunicación de sensores:** LoRa (SX1276/SX1278)  
- **Controladores:** ESP32  
- **Simulación de datos y pruebas:** Postman  
- **Repositorio de control de versiones:** GitHub  

### Herramientas adicionales  
- **Gestión y versionado:** GitHub  
- **Pruebas de API y mensajería:** Postman  
- **Orquestación de procesos:** n8n  
- **Diseño e interfaz:** Figma  

### Alcance del prototipo  
El sistema actual permite:  
- Simulación completa de detección de niveles de agua.  
- Procesamiento de datos en tiempo real.  
- Generación automática de alertas.  
- Envío de notificaciones a usuarios vía WhatsApp o SMS según la conectividad.  
- Visualización de alertas y datos históricos en la web.

### Presupuesto estimado  
**≈ 20 millones de pesos COP**, incluyendo sensores LoRa, microcontroladores, baterías, caja IP65, sistema solar, y montaje inicial.

---

## 🔹 Repositorio del proyecto  
📁 [https://github.com/00CARLOSECG00/404-Not-Found-Sleep-](#)

---

## 💧 **Resumen conceptual**
YAKU integra **tecnología de comunicación resiliente**, **energía limpia** y **alertas accesibles** para fortalecer la **resiliencia comunitaria** frente a inundaciones, sin depender de infraestructura compleja ni conectividad constante.
