# 📦 LEEME PRIMERO — PAQUETE DE MIGRACIÓN (EJEMPLO)

Este directorio contiene el **paquete de migración del agente**
del **Cognitive Glitch Framework** en versión demostrativa.

Su función es explicar **cómo reconstruir un agente** en otro modelo de IA
utilizando las definiciones ya existentes en el framework,
**sin duplicar capas ni contenido**.

---

## 🎯 ¿Qué es este paquete?

Este paquete **NO es el framework completo**  
y **NO contiene las capas del agente**.

Es un **kit mínimo de migración** que permite:

- cargar un agente en un modelo nuevo,
- validar que quedó bien cargado,
- entender el procedimiento de migración,
- sin depender de memoria conversacional previa.

---

## 📁 ¿Qué contiene este directorio?

Este paquete incluye únicamente:

- `Prompt_Maestro_EJEMPLO.md`  
  → Punto de entrada del agente (versión genérica).

- `SMOKE_TEST_EJEMPLO.md`  
  → Pruebas mínimas para validar integridad estructural.

- `Documento_Maestro_Migracion_EJEMPLO.md`  
  → Procedimiento completo de migración entre modelos.

---

## 🧩 ¿Dónde están las capas del agente?

Las capas **NO están duplicadas en este paquete**.

Se definen en el framework principal:

- **Capa 1 — Tono**  
  `01_INSTRUCCIONES_Y_TONO/`

- **Capa 2 — Metodología**  
  `02_METODOLOGIAS_Y_PROCESOS/`

- **Capa 3 — Arquitectura del agente**  
  `03_ARQUITECTURA_DE_AGENTES/`

- **Capa 4 — Manual de uso**  
  `03_ARQUITECTURA_DE_AGENTES/`

- **Capa 5 — Índice de memorias**  
  `04_BITACORAS_Y_CASOS/`

Este paquete **referencia esas capas**, no las replica.

---

## 🔁 Flujo de uso recomendado (ejemplo)

1. Leer este archivo (`LEEME_PRIMERO`)
2. Revisar el `Prompt_Maestro_EJEMPLO.md`
3. Cargar el prompt en una conversación nueva
4. Ejecutar el `SMOKE_TEST_EJEMPLO.md`
5. Ajustar o continuar según el resultado

---

## 🔒 Nota pública

Este paquete es **demostrativo y neutralizado**.
No contiene agentes reales, datos sensibles ni configuraciones privadas.

Para implementaciones reales, utilizar versiones privadas separadas.

---

**Framework:** Cognitive Glitch Framework  
**Propósito:** migración, testing y diseño de agentes portables
