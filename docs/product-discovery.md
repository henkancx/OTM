# OTManager - Product Discovery v1.0

Julio 2026 | HenkanCX | Confidencial

---

## Vision

Plataforma SaaS modular que gestiona el ciclo de vida completo del proceso postventa
de cualquier producto, desde la primera garantia hasta el fin de su vida util.

> "OTManager no solo gestiona tus ordenes de trabajo. Las entiende."

---

## Problema que resuelve

- Procesos manuales y repetitivos en equipos operativos
- Fragmentacion entre ERP, CRM, taller y contact center (silos)
- Imposibilidad de autogestion sin depender del proveedor
- Nula analitica predictiva
- Experiencia deficiente para el cliente final
- Redes de talleres dificiles de administrar y auditar

---

## Mercado

B2B y B2B2C latinoamericano: fabricantes, importadores, talleres autorizados,
retailers con departamento de postventa.

**Caso demo:** Mystic Latinoamerica

---

## Usuarios (6 roles)

| Rol | Descripcion |
|-----|-------------|
| Super Admin | Equipo HenkanCX - gestion de tenants |
| Admin Cliente | Dueno / Gerente General / Gerente Postventa |
| Contact Center | Agentes de atencion al cliente |
| Taller | Responsable de taller autorizado |
| Tecnico | Tecnico en campo (PWA mobile) |
| Usuario Final | Consumidor - portal self-service publico |

---

## Modulos (12)

- M1 - Gestion de OT: ciclo completo apertura -> cierre, estados, auditorias, firma digital
- M2 - CRM: ficha cliente, productos, historial completo
- M3 - Garantias y Reemplazos: validacion automatica, garantia extendida, cambio de producto
- M4 - Red de Talleres y Tecnicos: mapa, KM, stock por taller, LGR
- M5 - Contact Center: protocolos, Pre-OS, clasificaciones, providencias con SLA
- M6 - Inventario y Repuestos: catalogo, lista basica, tablas de precios, extracto MO
- M7 - Integraciones: API REST, SFTP, carga de archivos, webhooks, conector ERP
- M8 - Portal Usuario Final: consulta OT, mapa talleres, PWA instalable
- M9 - Reporteria, Dashboards y Analitica IA: KPIs, ML, scoring de red
- M10 - Motor de Notificaciones: WhatsApp, SMS, Email, push, fallback automatico
- M11 - AI Core Layer: agente siempre presente, agentes autonomos por dominio
- M12 - Brand Configurator: logo, colores, libro de marca, multi-tenant

---

## Plataforma

- Web responsive + mobile responsive
- PWA para tecnico en campo (offline-capable)
- Portal self-service publico para usuario final
- Multi-tenant con branding configurable por cliente
- Idiomas: ES / EN / PT

---

## Modelo de negocio

SaaS similar a Salesforce / HubSpot:
- Setup fee unico por implementacion
- Fee mensual por: usuarios + volumen de OTs + modulos + soporte

| Plan | OTs/mes | Precio referencial |
|------|---------|-------------------|
| Starter | < 500 | desde $499/mes |
| Professional | 500-5,000 | desde $1,499/mes |
| Enterprise | > 5,000 | desde $3,999/mes |

---

## Roadmap

**Fase 1 - MVP (Meses 1-5):** M1+M2+M3+M4+M5+M6+M7+M8+M9 basico+M10+M11 basico+M12
**Fase 2 - Expansion (Meses 6-12):** ML avanzado, agentes autonomos, app movil nativa, facturacion
**Fase 3 - Plataforma (Meses 13-24):** Modulo ventas, IoT, marketplace integraciones

---

## Demo

- Caso: Mystic Latinoamerica
- Archivo: demo/index.html
- Credenciales: admin / soyPana2026
- Duracion storytelling: 17-20 minutos + sandbox 2 semanas

---

## Stack demo actual

HTML + CSS + JS vanilla + Tabler Icons (single file, sin dependencias)

## Stack produccion (por definir)

React 18 + Vite + Tailwind / Node.js o FastAPI / PostgreSQL / LangGraph + Gemini / GCP
