# 🧠 PROMPT MAESTRO — EJEMPLO (VERSIÓN PÚBLICA)

## Propósito
Este archivo es una **plantilla genérica** de prompt maestro para agentes de IA
diseñados bajo el **Cognitive Glitch Framework**.

Su función es mostrar **cómo estructurar un agente por capas** de manera portable,
migrable y validable, **sin incluir datos reales ni configuraciones personales**.

Este archivo **NO es un agente funcional por sí mismo**.  
Es un **molde conceptual y técnico**.

---

## 📌 Metadatos del Prompt (Ejemplo)

- **Nombre del agente:** [Nombre genérico del agente]
- **Versión:** vX.Y
- **Rol general:** [Rol abstracto / función principal]
- **Uso previsto:** Ejemplo / Documentación / Formación
- **Estado:** Plantilla demostrativa

---

## 🎭 CAPA 1 — TONO Y ESTILO (EJEMPLO)

Definir aquí el **estilo de respuesta del agente** de forma abstracta.

Ejemplos de variables:
- Nivel de formalidad
- Claridad vs. creatividad
- Grado de directividad
- Estilo explicativo (paso a paso, sintético, narrativo)

> No incluir tono personal ni identidades reales.

---

## 🧠 CAPA 2 — METODOLOGÍA (EJEMPLO)

Describir el **pipeline cognitivo** que el agente debe seguir al responder.

Ejemplo:
- Analizar el problema
- Dividir en pasos
- Priorizar claridad
- Reducir carga cognitiva
- Explicitar decisiones

Esta capa define **cómo piensa**, no **qué piensa**.

---

## 🧩 CAPA 3 — ARQUITECTURA DEL AGENTE (EJEMPLO)

Definir:
- Rol del agente
- Alcance de acción
- Límites explícitos
- Tipos de tareas permitidas
- Tipos de tareas excluidas

Ejemplo:
> El agente no reemplaza decisiones humanas ni realiza diagnósticos clínicos o legales.

---

## 📘 CAPA 4 — MANUAL DE USO (EJEMPLO)

Instrucciones generales de operación:

- Cómo responder solicitudes
- Cómo pedir aclaraciones
- Cómo manejar ambigüedad
- Cómo cerrar respuestas
- Cómo evitar sobrecarga

Esta capa regula **el comportamiento operativo**.

---

## 🗂️ CAPA 5 — MEMORIA (ESTRUCTURAL, EJEMPLO)

Describir **qué tipos de información existen**, no el contenido.

Ejemplo:
- Bitácoras
- Casos
- Índices
- Registros de decisiones

> No incluir memorias reales ni datos sensibles.

---

## 🔁 PROCEDIMIENTO DE CARGA (EJEMPLO)

1. Iniciar conversación nueva en el modelo
2. Cargar este prompt completo
3. Confirmar comprensión del rol
4. Ejecutar pruebas de validación
5. Ajustar si es necesario

---

## 🧪 VALIDACIÓN (REFERENCIA)

Este prompt debe validarse mediante un procedimiento de smoke test genérico:

Archivo relacionado:
`SMOKE_TEST_EJEMPLO.md`

Si el agente no reconoce su rol, método o límites,
el prompt debe ajustarse antes de su uso.

---

## 🔒 Nota pública

Este archivo es parte del **framework demostrativo**.  
No contiene ni debe contener información privada, sensible o identificable.

Para implementaciones reales, utilizar una versión privada separada.
