# Chatbot impulsado por IA para la programación de citas

Este proyecto es un chatbot impulsado por IA diseñado para la programación de citas, desarrollado con Node.js y el marco BuilderBot. Se integra con varios servicios, incluyendo los modelos GPT de OpenAI, Google Calendar y ChatPDF, para ofrecer una funcionalidad mejorada.

## Características

- Procesamiento de lenguaje natural para entender las intenciones del usuario.
- Gestión y programación de citas.
- Integración con Google Calendar para verificar disponibilidad en tiempo real.
- Transcripción y procesamiento de notas de voz.
- Consulta de información en documentos PDF.
- Soporte multilingüe.

## Comenzando

### Requisitos previos

- Node.js 21 o superior.
- Administrador de paquetes pnpm.
- Clave de API de OpenAI.
- Credenciales de API de Google Calendar.
- Clave de API de ChatPDF.

### Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/leifermendez/bot-google-n8n-calendar
   cd builderbot-chatbot
   ```

2. Intala las dependencias:

   ```
   pnpm install
   ```

3. Configura las variables de entorno:
   Crea un archivo .env en el directorio raíz y añade las siguientes variables:

   ```
   OPEN_API_KEY=your_openai_api_key
   N8N_ADD_TO_CALENDAR=your_n8n_add_calendar_webhook
   N8N_GET_FROM_CALENDAR=your_n8n_get_calendar_webhook
   CHATPDF_API=your_chatpdf_api_endpoint
   CHATPDF_KEY=your_chatpdf_api_key
   CHATPDF_SRC=your_chatpdf_source_id
   DURATION_MEET=45
   TZ=your_timezone
   ```

4. Construye el proyecto:

   ```
   pnpm build
   ```

5. Inicia la aplicación:
   ```
   pnpm start
   ```

# EVIDENCIA 3
# Propuesta del Proyecto y Análisis de Factibilidad 

## Datos de Identificación

**Nombre del Proyecto:** TacoPlan  
**Periodo de Desarrollo:**  
- **Fecha Inicio:** 26/08/2024  
- **Fecha Fin:** 30/11/2024  

---

## Propuesta del Proyecto

### Justificación del Proyecto
La taquería enfrenta un problema con la gestión de eventos, utilizando métodos obsoletos que provocan ineficiencia y errores en la logística. La modernización de procesos permitirá optimizar la operación, reducir errores humanos y mejorar la experiencia del cliente, posicionando a la taquería como un negocio innovador y orientado al cliente.

### Objetivos

#### Generales
Desarrollar e implementar un sistema digital accesible mediante una página web, que permita a los clientes agendar eventos y al personal recibir recordatorios automáticos.

#### Específicos
1. Analizar las necesidades y requerimientos de la taquería.
2. Diseñar y desarrollar una página web intuitiva.
3. Implementar un sistema de notificaciones automáticas.
4. Capacitar al personal para asegurar la adopción del sistema.
5. Lanzar el sistema y realizar un seguimiento.

### Beneficiarios
1. **Personal de la taquería:** Mejorarán su eficiencia y reducirán el estrés asociado a la coordinación manual.
2. **Propietario de la taquería:** Incrementarán la satisfacción del cliente y la fidelización, potencialmente aumentando las reservas.

### Resultados Esperados
- Reducción del 70% en errores de manejo de información.
- Aumento del 40% en la eficiencia de los procesos de la taquería.

### Descripción de las Actividades
1. Recolección de requerimientos mediante entrevistas con el personal.
2. Diseño del sistema: creación de wireframes y mockups.
3. Desarrollo del sistema usando React y un backend para automatización.
4. Pruebas y optimización a través de simulaciones.
5. Capacitación del personal y seguimiento tras el lanzamiento.

---

## Análisis de Factibilidad

### Riesgos Potenciales
| Descripción                      | Probabilidad | Impacto |
|----------------------------------|--------------|---------|
| Falta de capacitación del personal | Media        | Alto    |
| Falta de publicidad               | Alta         | Alto    |
| Mal SEO de la página              | Baja         | Media   |

### Situación Actual y Tendencias
#### Situación Actual
La gestión de eventos se realiza mediante métodos manuales, lo que resulta en errores y una experiencia inconsistente para los clientes.

#### Tendencias
La industria alimentaria está adoptando herramientas digitales como sistemas de reservas en línea, aplicaciones y servicios automatizados para mejorar la experiencia del cliente.

### Comparativa de Alternativas
| Producto/Servicio      | Alternativa 1: Manual | Alternativa 2: Software Genérico | Alternativa 3: Sistema Personalizado |
|------------------------|-----------------------|----------------------------------|-------------------------------------|
| Facilidad de Uso       | Baja                 | Media                            | Alta                               |
| Costo                 | Muy bajo             | Medio                            | Alto                               |
| Eficiencia            | Baja                 | Media                            | Alta                               |
| Personalización       | Limitada             | Media                            | Alta                               |
| Escalabilidad         | Muy limitada         | Media                            | Alta                               |
| Integración Tecnológica | Ninguna             | Media                            | Alta                               |

### Impacto del Proyecto
1. **Mercado/Sector:** Posicionará a la taquería como un negocio moderno y orientado al cliente, atrayendo nuevos clientes y fidelizando a los actuales.
2. **Financiero:** Reducirá costos operativos y permitirá un mejor manejo de las reservas, aumentando los ingresos potenciales.
3. **Tecnológico:** Digitalizará las operaciones de la taquería, integrando tecnología en su día a día.

---

## Costos y Beneficios

### Costos Operativos
Incluyen servidores, suscripciones a herramientas específicas y soporte técnico para actualizaciones menores.

### Beneficios Esperados
- **Reducción de costos operativos:** Automatización que disminuye errores y ahorra tiempo.
- **Incremento en satisfacción del cliente:** Mejora la experiencia con un sistema ágil y personalizado.
- **Ventaja competitiva:** Posiciona a la taquería como un negocio moderno y atractivo.

---

Fecha de Elaboración: **2 de diciembre de 2024**  
**Autores:**  
- Luis Esteban Rojas González  
- Luis Alonso García Barrón  
- Ángel Rodrigo Pinto Sánchez  

**Profesor:** Adalberto Emmanuel Rojas Perea  
**Matrícula:** 3077103, 3107051, 3112737  