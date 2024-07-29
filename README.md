# GenIA_sintesis_dialogo
Fine-tuning de un modelo de IA Generativa para síntesis de diálogos. Se utiliza un modelo FLAT-T5. Se realizan Fine-Tunings Full y Eficiente. 

Dataset: https://huggingface.co/datasets/knkarthick/dialogsum

# 1. Objetivos del proyecto
Este proyecto puede ser útil para la implementación en asistentes virtuales y chatbots, ya que permitirá mejorar la capacidad de los mismos para entender y responder de la manera más natural y precisa las consultas de los usuarios, así también permitirá personalizar las interacciones del chatbot con los usuarios basándose en el contexto e historial de conversaciones previas. 

# 2. Realización del proyecto
- Configuración del Kernel y las Dependencias Requeridas
- Carga del Conjunto de Datos y el LLM
- Prueba del Modelo con Inferencia Zero Shot
- Preproceso del Conjunto de Datos de Diálogo-Resumen
- Afinado del Modelo con el Conjunto de Datos Preprocesado
- Evaluación del Modelo Cualitativamente (Evaluación Humana)
- Evaluación del Cuantitativamente (con la Métrica ROUGE)
- Afinado Eficiente en Parámetros (PEFT)
- Configuración del modelo PEFT/LoRA para el Afinado
- Entrenamiento del Adaptador PEFT
- Evaluación del Modelo Cualitativamente (Evaluación Humana)
- Evaluación del Modelo Cuantitativamente (con la Métrica ROUGE)
