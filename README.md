# CEIA-FIUBA_LLM
Trabajo práctico de la materia LLM de la Especialización en IA de FIUBA

# Modelo T5

T5 es un modelo encoder-decoder que convierte todas las tareas de procesamiento del lenguaje natural (NLP), como la creación de resumenes, traducción, interacciones pregunta-respuesta, generación de texto, etc., en una tarea de secuencia a secuencia, es decir, convierte una secuencia de texto (texto de origen) en otra secuencia de texto (texto objetivo).

Los modelos T5 están previamente entrenados en Colossal Clean Crawled Corpus (C4), que contiene texto y código extraídos de Internet. Este proceso de preentrenamiento permite a los modelos aprender habilidades generales de generación y comprensión del lenguaje. Luego, los modelos T5 se pueden ajustar posteriormente para tareas más específicas.

![enter image description here](https://production-media.paperswithcode.com/methods/new_text_to_text.jpg)

En este trabajo se entrenara este modelo para la obtención e inferencia de patologías médicas. Para esta tarea se utilizara el dataset MedQuAD que incluye 47,457 pares de preguntas y respuestas médicas creados a partir de 12 sitios web de los NIH (por ejemplo, cancer.gov, niddk.nih.gov, GARD, MedlinePlus Health Topics). La colección cubre 37 tipos de preguntas (por ejemplo, Tratamiento, Diagnóstico, Efectos secundarios) asociadas con enfermedades, medicamentos y otras entidades médicas como pruebas.

