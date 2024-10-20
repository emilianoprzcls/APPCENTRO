# Health-care: Cuidado de la Salud - Tu Salud, Nuestra Prioridad

## ¿Quiénes Somos?
Somos un equipo multidisciplinario especializado en el análisis de datos y tecnología. Nuestro equipo incluye:
- **Dos científicos de datos**: Expertos en el desarrollo e implementación de modelos estadísticos y de machine learning.
- **Dos economistas cuantitativos**: Especialistas en métodos cuantitativos y programación.
- **Una abogada**: Experta en protección de datos personales, asegurando que toda la información cumpla con las normativas vigentes y se mantenga segura.

## ¿Por Qué Elegir Nuestra Aplicación?
Nuestra aplicación está diseñada para atender tus necesidades de salud cotidianas. Ya sea que quieras llevar un seguimiento detallado de la salud de tus pacientes o registrar tus consultas médicas, esta herramienta te permite mantenerte informado y generar un resumen de tu historial médico en cualquier momento. Ofrecemos retroalimentación constante para ayudarte a mantener un estilo de vida saludable, y utilizamos algoritmos avanzados de inteligencia artificial para analizar tus datos y ofrecerte una visión más precisa de tu estado de salud.

### Beneficios:
- **Personalización**: Recibe recomendaciones y recordatorios adaptados a tus necesidades.
- **Cuidado preventivo**: Identifica patrones en tu salud para anticipar problemas futuros.
- **Historial médico accesible**: Comparte tu historial médico de manera sencilla en situaciones de emergencia.

## ¿Por Qué Es Importante Tu Historial Médico?
Tu historial médico te ayuda a entender mejor tu cuerpo y a tomar decisiones informadas sobre tu bienestar. Al compartir tu información con nosotros, podrás:
- Personalizar tus recomendaciones de salud.
- Identificar patrones en tu bienestar general.
- Facilitar el acceso a tu historial en situaciones de emergencia.

## ¿Cómo Garantizamos Tu Seguridad?
Utilizamos las últimas tecnologías de encriptación para proteger tu información. Sólo tú y las personas a las que decidas compartir tu información tendrán acceso a tus datos, siempre con tu consentimiento. Cumplimos con las regulaciones más estrictas en cuanto a privacidad y protección de datos.

## Tecnologías Utilizadas
- **Llama 3.1 y 3.2**: Modelos de lenguaje avanzados para procesar, generar y analizar texto.
- **Whisper**: Tecnología de inteligencia artificial que convierte audios en texto para facilitar la interpretación de información médica.

## Estructura de Archivos

La funcionalidad principal de la aplicación está organizada en la carpeta `FOR CARE`, donde cada archivo cumple con una función específica:

- **`chat_llama.py`**: Este archivo permite hacer preguntas sobre temas médicos y del registro médico a Llama 3.2. 
- **`consultation_records.py`**: Aquí puedes realizar registros manuales de consultas médicas, incluyendo imágenes de recetas, resultados médicos, interpretaciones y audios que describen condiciones de salud.
- **`emergency_mode.py`**: Espacio para consultar información sobre familiares y datos relevantes del paciente en caso de emergencia.
- **`portada.py`**: Archivo principal que engloba la funcionalidad total de la aplicación a través de Streamlit, integrando todos los otros archivos.
- **`register_history.py`**: Para realizar un registro general del paciente, recopilando información clave sobre su estado de salud.
- **`requirements.txt`**: Contiene los paquetes necesarios para que la aplicación funcione correctamente.

Además, en la carpeta `BIOS` se encuentran las biografías de los integrantes del equipo. La carpeta `Base de Datos` almacena los datos obtenidos a través de la aplicación, particularmente mediante la carpeta `FOR CARE`. En la carpeta `DATOS` se almacenan las imágenes, audios y otros archivos multimedia utilizados, los cuales son procesados posteriormente a través de Llama 3.2. También incluye un aviso de privacidad muy relevante sobre el manejo de datos personales, titulado `Aviso_Privacidad_Salud_Analitica_Boutique.docx`.

