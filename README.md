# Modelos-AI
Ejercicio sobre busqueda bilbiográfica en huggingface

### Conversación Completa

**Usuario:** Necesito comparar los siguientes artículos: EHRmonize: A Framework for Medical Concept Abstraction from Electronic Health Records using Large Language Models, EHRMamba: Towards Generalizable and Scalable Foundation Models for Electronic Health Records, EHRCon: Dataset for Checking Consistency between Unstructured Notes and Structured Tables in Electronic Health Records, EHRXQA: A Multi-Modal Question Answering Dataset for Electronic Health Records with Chest X-ray Images

**Asistente:** ¡Claro! Aquí tienes una comparación de los artículos que mencionaste:

### **EHRmonize: A Framework for Medical Concept Abstraction from Electronic Health Records using Large Language Models**
- **Objetivo**: Abstraer conceptos médicos de los registros electrónicos de salud (EHR) utilizando modelos de lenguaje grande (LLM).
- **Metodología**: Evaluación de cinco LLMs en tareas de extracción de texto libre y clasificación binaria usando datos de medicación de dos bases de datos EHR[^1^].
- **Resultados**: GPT-4o logró un 97% de precisión en la identificación de nombres genéricos de rutas y un 100% en la clasificación binaria de antibióticos[^1^].
- **Contribución**: Reducción del tiempo de anotación en un 60%, aunque se enfatiza la necesidad de supervisión clínica[^1^].

### **EHRMamba: Towards Generalizable and Scalable Foundation Models for Electronic Health Records**
- **Objetivo**: Desarrollar modelos fundacionales generalizables y escalables para EHR.
- **Metodología**: Uso de la arquitectura Mamba y un enfoque de finetuning multitarea (MPF) para procesar secuencias largas y aprender múltiples tareas clínicas simultáneamente[^7^].
- **Resultados**: EHRMamba puede procesar secuencias hasta un 300% más largas que los modelos anteriores y mostró un rendimiento superior en seis tareas clínicas principales[^7^].
- **Contribución**: Mejora en la integración de sistemas hospitalarios mediante el estándar de datos HL7 FHIR y la herramienta Odyssey para el desarrollo y despliegue de modelos EHR[^7^].

### **EHRCon: Dataset for Checking Consistency between Unstructured Notes and Structured Tables in Electronic Health Records**
- **Objetivo**: Asegurar la consistencia de datos entre notas no estructuradas y tablas estructuradas en EHR.
- **Metodología**: Creación de un dataset con anotaciones manuales de 3,943 entidades en 105 notas clínicas, verificadas contra entradas de bases de datos[^4^].
- **Resultados**: Introducción de CheckEHR, un marco para verificar la consistencia entre notas clínicas y tablas de bases de datos, mostrando resultados prometedores en configuraciones de few-shot y zero-shot[^4^].
- **Contribución**: Mejora de la seguridad del paciente al abordar discrepancias en los EHR[^4^].

### **EHRXQA: A Multi-Modal Question Answering Dataset for Electronic Health Records with Chest X-ray Images**
- **Objetivo**: Crear un dataset de preguntas y respuestas multimodal que combine EHR estructurados e imágenes de rayos X de tórax.
- **Metodología**: Integración de dos recursos unimodales: MIMIC-CXR-VQA para preguntas visuales y EHRSQL para preguntas basadas en tablas[^10^].
- **Resultados**: Propuesta de una estrategia basada en NeuralSQL con una API de VQA externa, mejorando el razonamiento multimodal en EHR[^10^].
- **Contribución**: Avances en la toma de decisiones clínicas y la investigación mediante el uso de datos multimodales[^10^].

Espero que esta comparación te sea útil. ¿Hay algún aspecto específico que te gustaría profundizar?

**Usuario:** Necesito una tabla comparativa mostrando el modelo de inteligencia artificial y el dataset utilizado en cada uno de los artículos

**Asistente:** ¡Por supuesto! Aquí tienes una tabla comparativa que muestra el modelo de inteligencia artificial y el dataset utilizado en cada uno de los artículos mencionados:

| Artículo | Modelo de Inteligencia Artificial | Dataset Utilizado |
|----------|-----------------------------------|-------------------|
| **EHRmonize** | GPT-4o y Claude-3.5-Sonnet | Datos de medicación de dos bases de datos EHR[^8^] |
| **EHRMamba** | Arquitectura Mamba con finetuning multitarea (MPF) | Datos de múltiples sistemas hospitalarios integrados con HL7 FHIR[^4^] |
| **EHRCon** | CheckEHR | Dataset con 3,943 entidades anotadas en 105 notas clínicas[^1^] |
| **EHRXQA** | NeuralSQL con API de VQA externa | MIMIC-CXR-VQA y EHRSQL[^7^] |

Espero que esta tabla te sea útil. ¿Hay algo más en lo que pueda ayudarte?

**Usuario:** Necesito toda esta conversación en un documento en formato .md
