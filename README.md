# State of Flows (SoFs) 🛰️

> **Observabilidad espacial, auditoría por presets y diagnóstico visual para flujos de automatización y agentes.**

**State of Flows (SoFs)** transforma la revisión técnica de automatizaciones (n8n, Make, Zapier, LangGraph, Webhooks) en una experiencia espacial interactiva. En lugar de leer logs planos o revisar nodos a ciegas, SoFs despliega una **sonda geométrica de inspección** sobre una bóveda interconectada, mostrando su desplazamiento sistemático, el razonamiento paso a paso y un informe ejecutivo simplificado.

---

## ✨ Características Principales

- **Bóveda Espacial de Telemetría:** Visualización oscura estilo Obsidian organizada por secciones lógicas (*Ingesta*, *Lógica & IA*, *Persistencia & Notificación*).
- **Sonda de Inspección con Razonamiento Visible:** Artefacto animado que recorre las conexiones, se ancla en cada nodo, evalúa dependencias y emite ondas de impacto en cascada ante anomalías.
- **Presets de Auditoría Especializados:**
  - 🛡️ **Resiliencia & Errores:** Timeouts, reintentos, idempotencia y Dead Letter Queues.
  - 🔒 **Seguridad & PII:** Detección de datos personales expuestos a LLMs, firmas HMAC y secretos.
  - ⚡ **Rendimiento & Costo API:** Optimización de modelos LLM, caché y ejecución paralela.
  - 🚀 **Pre-Flight & Entrega:** Validación de calidad antes de pasar a producción o entregar a clientes.
- **Informe Simplificado Accionable:** Health Score (0–100), hallazgos priorizados por severidad y exportación directa en Markdown.

---

## 📂 Estructura del Repositorio

```text
state-of-flows/
├── index.html            # Landing Page One-Page con demo embebida y analizador rápido de JSON
├── state-of-flows.html   # Prototipo interactivo completo de la Bóveda (Zoom, Pan, Auto-Cámara y Reporte MD)
└── README.md             # Documentación principal del proyecto
```

---

## 🚀 Despliegue Rápido (GitHub Pages)

Este proyecto está construido en HTML5, Tailwind CSS y JavaScript Vanilla sin dependencias de compilación:

1. Sube `index.html`, `state-of-flows.html` y `README.md` a tu repositorio `state-of-flows`.
2. Ve a **Settings → Pages** en GitHub.
3. En **Branch**, selecciona `main` y carpeta `/ (root)`, luego haz clic en **Save**.
4. Tu sitio estará en vivo en `https://<tu-usuario>.github.io/state-of-flows/`.

---

## 🗺️ Roadmap Inicial

- [x] Prototipo espacial de bóveda y sonda de escaneo (`state-of-flows.html`)
- [x] Landing Page One-Page con simulador estático de JSON (`index.html`)
- [ ] Parser nativo para importación directa de blueprints de **n8n** y **Make**
- [ ] Conexión de lista de espera y guardado de auditorías históricas
- [ ] Motor híbrido de reglas + LLM para sugerencias automáticas de parches

---

*Built with precision for automation architects.*
