# Manifiesto de Uso de Inteligencia Artificial — State of Flows (SoFs) 🤖🧭

Este documento establece de forma transparente el rol, alcance y principios bajo los cuales se utilizan herramientas de Inteligencia Artificial en la conceptualización, diseño y desarrollo de **State of Flows (SoFs)** desde su origen.

---

## 1. Principio Rector: Dirección Humana, Aceleración con IA

**State of Flows (SoFs)** nace de una visión y necesidad humana real: transformar la auditoría técnica de flujos de automatización en una experiencia visual, espacial y comprensible. 

La Inteligencia Artificial actúa en este proyecto como **copiloto de arquitectura, diseño y prototipado**, nunca como sustituto del criterio del creador. Todas las decisiones de producto, estética, experiencia de usuario (UX), prioridades y validación final son dirigidas y aprobadas por el autor del proyecto (**René Garza**).

---

## 2. Ecosistema de Modelos Utilizados

Para construir SoFs se emplea un flujo de trabajo colaborativo apoyado principalmente en dos modelos de lenguaje:

* **Gemini (Google):** Utilizado como compañero principal de ideación espacial, definición de dirección estética y comportamiento de la sonda de escaneo, prototipado interactivo rápido (HTML/SVG/JS), redacción de documentación inicial y despliegue.
* **Claude (Anthropic):** Utilizado como socio de razonamiento técnico, estructuración de lógica compleja, refinamiento de código, revisión de arquitectura y análisis de casos límite.

---

## 3. Áreas de Aplicación vs. Responsabilidad Humana

| Dimensión del Proyecto | Rol de la IA (Gemini & Claude) | Responsabilidad Humana (Creador) |
| :--- | :--- | :--- |
| **Visión y Concepto** | Estructuración y aterrizaje técnico de ideas. | Idea original, propósito del producto y definición del problema. |
| **Diseño UI / UX** | Generación de propuestas visuales, animaciones SVG y estilos Tailwind. | Dirección estética ("bóveda oscura"), aprobación visual y pruebas de usabilidad. |
| **Código y Prototipos** | Escritura de código base, simuladores y lógica de recorrido de grafos. | Integración, pruebas reales, control de versiones y despliegue en producción. |
| **Auditoría y Presets** | Borradores de reglas heurísticas y mensajes de diagnóstico. | Validación de utilidad práctica en flujos reales de automatización. |

---

## 4. Compromisos de Transparencia y Calidad

1. **Sin cajas negras:** Todo código generado con apoyo de Gemini o Claude es revisado, comprendido y probado antes de integrarse al repositorio principal.
2. **Privacidad de datos:** Durante el desarrollo y pruebas de SoFs, no se comparten credenciales reales, llaves de API privadas ni datos personales de terceros con los modelos de IA.
3. **Evolución abierta:** Este manifiesto se actualizará conforme el proyecto evolucione hacia versiones más avanzadas (parsers nativos, motor híbrido de análisis o integraciones con terceros).

---

*Última actualización: Inicio del proyecto — Repositorio `stateofflows`.*