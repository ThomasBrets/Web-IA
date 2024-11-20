# Web-IA: Diseñador de páginas web con inteligencia artificial

## Autor
**Thomas Bretschneider**  
Curso: *Inteligencia artificial: Generación de Prompts*  
Comisión: 67115  

---

## Presentación del problema

En el proceso de desarrollo de una página web, la comunicación entre el cliente y el programador es crucial. Muchas veces, los clientes no tienen una idea clara de cómo describir sus necesidades o imaginar cómo será el diseño final, lo que puede resultar en malentendidos y revisiones constantes. 

Este problema no solo genera demoras, sino también frustración para ambas partes, aumentando el tiempo y los costos del proyecto. Es relevante desarrollar una solución que permita a los clientes visualizar sus ideas y plasmar sus requerimientos de manera clara y creativa antes de contactar a un programador.

---

## Desarrollo de la propuesta de solución

El proyecto *Web-IA* busca resolver esta problemática mediante el uso de inteligencia artificial para generar propuestas de diseño basadas en las respuestas del cliente. 

El usuario podrá interactuar con un sistema que hará preguntas clave, como:
- "¿Qué colores quieres que tenga la página?"
- "¿Qué secciones deseas incluir?"
- "¿Prefieres un diseño moderno o clásico?"

A partir de estas respuestas, el sistema generará:
1. **Un prompt detallado** que describa la página web deseada. Este prompt puede ser utilizado por el programador como base para el desarrollo.
2. **Una imagen de referencia** generada con herramientas de IA como DALL-E, que ilustre cómo podría verse la página web diseñada según las especificaciones del cliente.

El objetivo es brindar al cliente una experiencia interactiva y visual que facilite la comunicación y permita generar ideas antes de la fase de programación.

---

## Justificación de la viabilidad del proyecto

El proyecto es técnicamente viable, ya que:
1. **Recursos disponibles:** Se utilizarán la API de OpenAI para la generación de texto y DALL-E (u otra herramienta similar) para la creación de imágenes.
2. **Plataforma de desarrollo:** Jupyter Notebook permitirá integrar código, texto e imágenes en un entorno único, adecuado para la presentación del proyecto.
3. **Tiempo disponible:** La implementación se puede completar dentro del marco de tiempo del curso, enfocándose primero en un prototipo funcional.
4. **Alcance claro:** La solución se centra en generar prompts optimizados y visualizaciones básicas, sin abordar directamente la construcción técnica de la página web.

La elección de OpenAI y DALL-E garantiza un alto nivel de calidad en los resultados, mientras que el uso de preguntas guiadas asegura que los usuarios puedan interactuar fácilmente con el sistema.

---

## Próximos pasos

1. Diseñar el flujo de preguntas para guiar al usuario en la descripción de su página web.
2. Implementar y probar la generación de prompts con OpenAI.
3. Integrar la herramienta de generación de imágenes para crear visualizaciones basadas en los prompts.
4. Optimizar los prompts utilizando técnicas de *Fast Prompting* para garantizar la precisión y relevancia de los resultados.

---

