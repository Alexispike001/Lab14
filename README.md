El sistema combina respuestas locales preprogramadas con respuestas generadas por la API, siguiendo una estructura jerárquica de búsqueda: 
primero busca coincidencias exactas, luego por palabras clave, y finalmente recurre a OpenAI si no se encuentra una respuesta adecuada.

Aunque la API de OpenAI permite mantener conversaciones con memoria contextual, este proyecto no implementa dicha capacidad. 
Sin embargo, se optó por usar un modelo optimizado como gpt-3.5-turbo para mayor eficiencia.

El uso de la API me enseñó a construir solicitudes POST y a manejar estructuras JSON correctamente, cuidando detalles como el escape de caracteres especiales. 
También comprendí mejor los retos del procesamiento de lenguaje natural, como la ambigüedad semántica y la necesidad de soluciones más sofisticadas para el análisis del lenguaje.
