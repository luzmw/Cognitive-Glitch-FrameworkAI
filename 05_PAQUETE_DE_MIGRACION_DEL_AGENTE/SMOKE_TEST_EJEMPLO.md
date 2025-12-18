# 🔥 SMOKE TEST — EJEMPLO (VERSIÓN PÚBLICA)

## Propósito
Este documento describe un **procedimiento genérico de smoke test**
para validar que un agente de IA cargado mediante el
**Cognitive Glitch Framework** conserva su estructura básica:

- identidad funcional  
- metodología declarada  
- límites operativos  

El smoke test **no evalúa calidad avanzada**.
Evalúa **integridad estructural mínima**.

---

## 🧠 ¿Qué es un smoke test?
Un smoke test es una prueba inicial y rápida que responde a una sola pregunta:

> ¿El agente está correctamente cargado o el modelo está improvisando?

Si el smoke test falla, **no se continúa el trabajo**.
Se revisan las capas antes de avanzar.

---

## 📌 Cuándo ejecutar este test

Este procedimiento debe ejecutarse:

- al iniciar una conversación nueva
- al migrar el agente a otro modelo
- al cambiar parámetros del modelo
- al modificar el prompt maestro
- después de un reset o pérdida de contexto

---

## 🧪 PRUEBA 1 — Identidad y Tono

### Prompt de prueba
