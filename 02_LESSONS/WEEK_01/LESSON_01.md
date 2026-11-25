# Semana 1 — Lección 1: Cómo funciona realmente la IA

**Estado: EN CURSO**

## Objetivos
- Explicar qué es un LLM y cómo genera texto.
- Diferenciar tokens, atención, embeddings, contexto y pesos.
- Distinguir entrenamiento, inferencia y RAG.
- Explicar por qué un LLM no es automáticamente un agente.
- Proponer componentes de un agente para un caso de ingeniería.

## Contenido ya introducido
Un LLM estima distribuciones de probabilidad sobre tokens siguientes condicionadas por el contexto. Los Transformers usan mecanismos de atención para procesar relaciones contextuales. Los embeddings son representaciones vectoriales. La ventana de contexto delimita la información procesada en una ejecución; no equivale a memoria persistente. Los pesos son parámetros aprendidos durante entrenamiento.

Entrenamiento ajusta parámetros; inferencia usa el modelo entrenado; RAG recupera información externa y la incorpora al contexto.

Un agente añade a un modelo un objetivo, ciclo de ejecución, herramientas, estado/memoria y mecanismos de observación/verificación. La arquitectura concreta varía.

## Evaluación Feynman pendiente
1. ¿Qué es un LLM? Explícalo a alguien de 12 años.
2. ¿Por qué un LLM no es automáticamente un agente?
3. ¿Qué componentes necesita un agente que lea planos y genere un Excel?

## Laboratorio comparativo pendiente
Usar el mismo prompt en Claude y ChatGPT:

“Actúa como arquitecto de sistemas de inteligencia artificial. Diseña una solución para una empresa manufacturera que necesita procesar planos técnicos, extraer componentes y generar listas de materiales en Excel. Separa la solución en: modelo de IA, herramientas externas, procesamiento de archivos, memoria, validaciones, automatizaciones y seguridad. Explica qué componentes requieren programación y cuáles pueden implementarse mediante herramientas existentes. Identifica riesgos y limitaciones. Construye una arquitectura modular.”

Comparar: calidad de arquitectura, profundidad técnica, viabilidad, riesgos y componentes faltantes.

## Criterio de aprobación
Rúbrica sobre 100: comprensión LLM (20), tokens/atención/embeddings (20), entrenamiento/inferencia/RAG (20), modelo vs agente (20), arquitectura (20). Umbral: 80/100, sujeto a evidencia.
