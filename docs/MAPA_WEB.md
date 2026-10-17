# Mapa y contenidos de la web corporativa — nexaroai.agency

Estado: **borrador para aprobación** (tarea T06 de la Fase 1). Este documento define qué páginas tendrá la web, qué debe conseguir cada una y qué contenido lleva. No cambia todavía la web publicada.

Reglas de contenido (master prompt, secciones 2 y 7):

- Nada de clientes, testimonios, logotipos, cifras, certificaciones ni casos de éxito inventados.
- Ninguna promesa de resultados no demostrados. Se describen problemas y cómo se abordan, no garantías.
- Los precios solo aparecen cuando estén aprobados. Hasta entonces la llamada a la acción es "Solicitar diagnóstico".
- Los textos legales son borradores y necesitan revisión humana o legal antes de publicarse.

## Contenido actual que hay que retirar

| Texto actual (`index.html`) | Problema | Sustitución |
|---|---|---|
| "Empresas como la tuya ya están mejorando su seguridad" | Prueba social no verificada | Eliminar hasta tener clientes reales con permiso |
| "Auditorías limitadas cada semana" | Escasez no demostrada | Eliminar |
| "Te decimos exactamente qué tienes que arreglar en 24h" | Plazo garantizado no demostrado | "Te enviamos un informe claro con prioridades" |
| Plan "Pro 29€/mes — Monitorización continua + alertas" | Servicio y precio no existentes ni aprobados | Eliminar hasta que el servicio exista |
| Formulario "Auditoría gratis" que pide cualquier web | Analizar una web sin autorización del titular es un riesgo legal | Pedir contacto y necesidad; el análisis solo empieza con autorización escrita |
| Formulario a Formspree sin aviso de privacidad | Datos personales enviados a un tercero sin informar (RGPD) | Formulario a la API propia con casilla de consentimiento y enlace a privacidad |

## Páginas

| Ruta | Página | Objetivo | Llamada a la acción |
|---|---|---|---|
| `/` | Inicio | Explicar en 10 segundos qué hace NexaroAI y para quién | Solicitar diagnóstico |
| `/servicios/` | Servicios | Detallar las tres líneas y el mantenimiento | Solicitar diagnóstico |
| `/sectores/` | Soluciones por sector | Conectar problemas concretos de cada sector con un servicio | Contar mi caso |
| `/como-trabajamos/` | Cómo trabajamos | Mostrar el proceso y los controles de calidad y seguridad | Solicitar diagnóstico |
| `/demostraciones/` | Casos demostrativos | Pruebas de concepto propias, marcadas como demostración | Ver la demo / Contactar |
| `/sobre/` | Sobre NexaroAI | Quién está detrás y cómo trabaja, sin inflar | Contactar |
| `/contacto/` | Contacto | Formulario validado con consentimiento | Enviar |
| `/privacidad/` | Política de privacidad | Cumplir RGPD y LOPDGDD | — |
| `/cookies/` | Política de cookies | Solo si se usan cookies no técnicas o analítica que las requiera | — |
| `/aviso-legal/` | Aviso legal y condiciones | Datos del titular (LSSI) y condiciones de uso | — |
| `/404.html` | Página de error | Volver a inicio o contacto | Ir a inicio |

## Contenido por página

### Inicio

- **Titular:** "Implementamos soluciones de IA y automatización que reducen el trabajo manual, mejoran la atención al cliente y ayudan a las empresas a gestionar sus procesos."
- **Para quién:** pymes, clínicas, gestorías, despachos profesionales, academias, inmobiliarias y empresas de servicios.
- **Tres bloques de problema → servicio:**
  - "Pasáis horas clasificando correos y copiando datos" → IA y automatización.
  - "Vuestra web o vuestras herramientas se han quedado cortas" → Desarrollo web y software.
  - "No sabéis cómo de expuesta está vuestra empresa" → Ciberseguridad para pymes.
- **Cómo trabajamos (resumen en 4 pasos):** diagnóstico → propuesta cerrada → desarrollo con pruebas → mantenimiento.
- **Llamada a la acción final:** "Solicita un diagnóstico" (enlace a contacto).

### Servicios

| Línea | Servicios | Problema que resuelve |
|---|---|---|
| IA y automatización | Clasificación de correos, extracción de datos de documentos, asistentes internos sobre vuestra documentación, chatbots de preguntas frecuentes, integraciones con CRM (n8n, Make, APIs) | Trabajo manual repetitivo y respuestas lentas |
| Desarrollo web y software | Webs corporativas, landing pages, tiendas online, aplicaciones web, APIs, software a medida, mantenimiento | Herramientas que no encajan con el proceso real |
| Ciberseguridad para pymes | Revisión de configuración y exposición, inventario de activos y riesgos, evaluaciones autorizadas, planes de remediación, alineación progresiva con NIST CSF 2.0, ISO 27001 y ENS | Riesgo desconocido y falta de documentación |
| Mantenimiento | Actualizaciones, copias de seguridad, monitorización, incidencias | Que lo construido siga funcionando |

Tres modalidades de contratación (sin precio hasta su aprobación): **Diagnóstico y planificación**, **Implantación de una solución** y **Mantenimiento y mejora continua**.

Nota obligatoria en ciberseguridad: "Toda prueba de seguridad se hace con autorización escrita, alcance definido y límites claros."

### Soluciones por sector

Un bloque por sector con un problema típico y una solución posible, redactados como ejemplos, no como casos reales:

| Sector | Problema típico | Solución posible |
|---|---|---|
| Clínicas | Citas y preguntas repetidas por teléfono y WhatsApp | Chatbot de preguntas frecuentes y recordatorios |
| Gestorías | Facturas y documentos que se teclean a mano | Extracción automática de datos de documentos |
| Despachos profesionales | Correo desbordado y expedientes dispersos | Clasificación de correos y asistente sobre la documentación interna |
| Academias | Matrículas y consultas en temporada alta | Formularios conectados al CRM y respuestas automáticas |
| Inmobiliarias | Leads de portales que se pierden | Captación unificada y seguimiento de leads |
| Empresas de servicios | Presupuestos y seguimiento manual | Automatización de presupuestos e integraciones |

### Cómo trabajamos

1. Diagnóstico: entendemos el proceso y el problema.
2. Propuesta: alcance, plazos y precio cerrados por escrito.
3. Diseño y desarrollo con pruebas automáticas.
4. Revisión de calidad y de seguridad independientes.
5. Tu aprobación antes de publicar nada.
6. Entrega con documentación.
7. Mantenimiento e incidencias.

Compromisos: datos mínimos, claves nunca en el navegador, y ninguna comunicación ni despliegue sin aprobación.

### Casos demostrativos

Solo pruebas de concepto construidas por NexaroAI, cada una con la etiqueta **"Demostración — no es un cliente real"**. Candidatas:

- Captación y gestión de leads (el backend de `nexaro-ai`).
- Clasificador de correos con datos de ejemplo.
- Revisión de cabeceras de seguridad de una web propia (`owasp-web-auditor`, pendiente de revisar).

### Sobre NexaroAI

Quién está detrás, en primera persona y sin exagerar: formación (DAM/DAW), áreas de trabajo y principios (transparencia, seguridad, nada de promesas no demostradas). Sin cifras de clientes ni años de experiencia que no se puedan comprobar.

### Contacto

Campos: nombre, email, teléfono (opcional), empresa (opcional), sector (lista), qué necesitáis (texto), casilla de consentimiento obligatoria con enlace a privacidad, campo honeypot oculto. Envío a `POST /api/leads` de `nexaro-ai`. Mensajes de carga, éxito y error.

### Textos legales

Borradores que preparará A08 (Security & Privacy) para revisión humana: titular y NIF (`[REQUIRES_INPUT]`), finalidad, base legal (consentimiento), conservación de los leads, encargados del tratamiento (hosting y backend), transferencias internacionales si las hay y derechos ARSOPOL.

## Requisitos técnicos

- HTML, CSS y JS estáticos servidos por GitHub Pages (dominio `nexaroai.agency`, ya configurado en `CNAME`).
- `<title>` y `<meta name="description">` únicos por página, Open Graph, `lang="es"`.
- `sitemap.xml` y `robots.txt`.
- Accesibilidad WCAG 2.2 AA: contraste, foco visible, etiquetas en formularios, navegación por teclado.
- Diseño adaptable a móvil.
- Sin analítica hasta que se apruebe una opción respetuosa con la privacidad.
- Criterio de aceptación: Lighthouse accesibilidad ≥ 90 y HTML válido en todas las páginas.

## Pendiente de decidir

1. Nombre visible: "NexaroAI", "NEXAROAI AGENCY" o "NEXARO".
2. Datos del titular para el aviso legal (nombre o razón social, NIF y dirección).
3. Si se mantiene `wrangler.jsonc` (Cloudflare Workers) o se retira, ya que la web se sirve desde GitHub Pages.
