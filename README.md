<div align="center">

<!-- Hero Banner -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 220" width="100%" max-width="900">
  <defs>
    <linearGradient id="hero-bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a0a0f"/>
      <stop offset="45%" stop-color="#12121a"/>
      <stop offset="100%" stop-color="#1a1a2e"/>
    </linearGradient>
    <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#6366f1"/>
      <stop offset="50%" stop-color="#818cf8"/>
      <stop offset="100%" stop-color="#a5b4fc"/>
    </linearGradient>
    <linearGradient id="glow" x1="50%" y1="0%" x2="50%" y2="100%">
      <stop offset="0%" stop-color="#6366f1" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#6366f1" stop-opacity="0"/>
    </linearGradient>
    <filter id="blur">
      <feGaussianBlur stdDeviation="40"/>
    </filter>
  </defs>
  <rect width="900" height="220" rx="16" fill="url(#hero-bg)"/>
  <ellipse cx="750" cy="40" rx="120" ry="80" fill="#6366f1" opacity="0.12" filter="url(#blur)"/>
  <ellipse cx="150" cy="180" rx="100" ry="60" fill="#818cf8" opacity="0.08" filter="url(#blur)"/>
  <rect x="60" y="100" width="80" height="3" rx="1.5" fill="url(#accent)"/>
  <text x="60" y="78" font-family="system-ui, -apple-system, sans-serif" font-size="38" font-weight="700" fill="#f8fafc" letter-spacing="-0.5">Facundo Esquivel</text>
  <text x="60" y="130" font-family="system-ui, -apple-system, sans-serif" font-size="15" fill="#94a3b8" letter-spacing="2">FULL-STACK · BUSINESS SOFTWARE</text>
  <text x="60" y="168" font-family="system-ui, -apple-system, sans-serif" font-size="13" fill="#64748b">Plataformas · Sistemas de gestión · Automatización operativa</text>
  <rect x="60" y="188" width="780" height="1" fill="#1e293b"/>
  <circle cx="820" cy="110" r="28" fill="none" stroke="url(#accent)" stroke-width="1.5" opacity="0.6"/>
  <circle cx="820" cy="110" r="18" fill="none" stroke="#6366f1" stroke-width="1" opacity="0.3"/>
  <circle cx="820" cy="110" r="6" fill="#6366f1" opacity="0.8"/>
</svg>

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=esquivelfacundo&color=6366f1&style=for-the-badge&label=VISITAS)](https://github.com/esquivelfacundo)

</div>

<br/>

### Desarrollo software que resuelve problemas reales de negocio

No construyo sitios web. Diseño y desarrollo **plataformas operativas** — sistemas que centralizan información, automatizan procesos y dan control real a las empresas sobre sus operaciones.

Mi foco actual está en **React** y arquitecturas web modernas. Mi trayectoria incluye PHP, WordPress y WooCommerce, lo que me da una base sólida para integrar sistemas y entender entornos empresariales complejos.

<br/>

---

<br/>

### Qué construyo

```mermaid
---
config:
  theme: base
  themeVariables:
    primaryColor: '#1e1b4b'
    primaryTextColor: '#e2e8f0'
    primaryBorderColor: '#6366f1'
    lineColor: '#475569'
    secondaryColor: '#1e293b'
    tertiaryColor: '#312e81'
    fontFamily: system-ui
---
flowchart TB
    HUB(["Plataforma Operativa<br/><sub>Dashboard · APIs · Datos centralizados</sub>"])

    HUB --- CRM
    HUB --- TURNOS
    HUB --- OPS
    HUB --- INV

    subgraph CRM[" CRM "]
        direction TB
        CRM1["Clientes & historial"]
        CRM2["Pagos & seguimiento comercial"]
        CRM1 ~~~ CRM2
    end

    subgraph TURNOS[" Turnos & Reservas "]
        direction TB
        T1["Reservas online"]
        T2["Profesionales · servicios · pagos"]
        T1 ~~~ T2
    end

    subgraph OPS[" Gestión Operativa "]
        direction TB
        O1["Procesos internos"]
        O2["Control admin · digitalización"]
        O1 ~~~ O2
    end

    subgraph INV[" Inventario & Ventas "]
        direction TB
        I1["Stock & movimientos"]
        I2["Reportes · seguimiento comercial"]
        I1 ~~~ I2
    end

    classDef hub fill:#312e81,stroke:#818cf8,color:#f8fafc,stroke-width:2px
    classDef module fill:#1e1b4b,stroke:#6366f1,color:#e2e8f0
    classDef detail fill:#1e293b,stroke:#475569,color:#cbd5e1

    class HUB hub
    class CRM1,CRM2,T1,T2,O1,O2,I1,I2 detail
```

<sub>Interfaces de administración, paneles de control y herramientas internas — todo conectado a un mismo ecosistema operativo.</sub>

<br/>

---

<br/>

### Stack tecnológico

<div align="center">

<!-- Current Focus -->
<br/>

**Enfoque actual**

<br/><br/>

<img src="https://skillicons.dev/icons?i=react,js,ts,html,css,mysql&theme=dark&perline=6" alt="React, JavaScript, TypeScript, HTML, CSS, MySQL"/>

<br/><br/>

**Trayectoria & experiencia**

<br/><br/>

<img src="https://skillicons.dev/icons?i=php,wordpress&theme=dark&perline=6" alt="PHP, WordPress"/>

<br/><br/>

<img src="https://img.shields.io/badge/APIs-REST-6366f1?style=for-the-badge&logo=fastapi&logoColor=white" alt="REST APIs"/>
<img src="https://img.shields.io/badge/Plugins-WordPress-21759b?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress Plugins"/>
<img src="https://img.shields.io/badge/Integraciones-Personalizadas-0ea5e9?style=for-the-badge&logo=graphql&logoColor=white" alt="Custom Integrations"/>
<img src="https://img.shields.io/badge/WooCommerce-E--commerce-96588a?style=for-the-badge&logo=woo&logoColor=white" alt="WooCommerce"/>

</div>

<br/>

---

<br/>

### Cómo trabajo

```mermaid
---
config:
  theme: base
  themeVariables:
    primaryColor: '#1e1b4b'
    primaryTextColor: '#e2e8f0'
    primaryBorderColor: '#6366f1'
    lineColor: '#6366f1'
    secondaryColor: '#1e293b'
    tertiaryColor: '#312e81'
    fontFamily: system-ui
---
flowchart TB
    START(["Necesidad del negocio"]) ==> P1
    P1["01 · Entender el proceso"] ==> P2
    P2["02 · Diseñar la solución"] ==> P3
    P3["03 · Desarrollo full-stack"] ==> P4
    P4["04 · Integrar sistemas"] ==> P5
    P5["05 · Automatizar operaciones"] ==> END(["Impacto medible"])

    P1 -.-> N1["Flujos actuales · pain points · objetivos"]
    P2 -.-> N2["Arquitectura · UX operativa · alcance"]
    P3 -.-> N3["React · APIs REST · base de datos"]
    P4 -.-> N4["WordPress · WooCommerce · servicios externos"]
    P5 -.-> N5["Menos tareas manuales · más control"]

    classDef trigger fill:#1e293b,stroke:#475569,color:#e2e8f0,stroke-width:2px
    classDef phase fill:#1e1b4b,stroke:#6366f1,color:#e2e8f0,stroke-width:2px
    classDef outcome fill:#312e81,stroke:#818cf8,color:#f8fafc,stroke-width:3px
    classDef context fill:#0f172a,stroke:#334155,color:#94a3b8

    class START trigger
    class P1,P2,P3,P4,P5 phase
    class END outcome
    class N1,N2,N3,N4,N5 context
```

<br/>

### Arquitectura típica

```mermaid
---
config:
  theme: base
  themeVariables:
    primaryColor: '#1e1b4b'
    primaryTextColor: '#e2e8f0'
    primaryBorderColor: '#6366f1'
    lineColor: '#475569'
    secondaryColor: '#1e293b'
    fontFamily: system-ui
---
flowchart LR
    subgraph FRONT[" Capa de presentación "]
        UI["React<br/>Dashboards · CRM · Turnos"]
    end

    subgraph BACK[" Capa de lógica "]
        API["APIs REST<br/>Reglas de negocio · Automatizaciones"]
    end

    subgraph DATA[" Capa de datos "]
        DB[("MySQL<br/>Información centralizada")]
    end

    subgraph EXT[" Integraciones "]
        WP["WordPress / WooCommerce"]
        SVC["Pagos · Email · Servicios externos"]
    end

    UI <-->|"HTTP"| API
    API <-->|"Queries"| DB
    API <-->|"Webhooks · Sync"| WP
    API <-->|"APIs"| SVC

    classDef layer fill:#1e1b4b,stroke:#6366f1,color:#e2e8f0
    classDef storage fill:#312e81,stroke:#818cf8,color:#f8fafc
    classDef external fill:#1e293b,stroke:#475569,color:#cbd5e1

    class UI,API layer
    class DB storage
    class WP,SVC external
```

<br/>

---

<br/>

### Posicionamiento

<table>
<tr>
<td>
<img src="https://img.shields.io/badge/NO-Sitios_web_informativos-ef4444?style=flat-square" alt="No"/>
</td>
<td>
Desarrollador que arma páginas corporativas sin impacto operativo
</td>
</tr>
<tr>
<td>
<img src="https://img.shields.io/badge/SÍ-Software_de_negocio-22c55e?style=flat-square" alt="Sí"/>
</td>
<td>
Desarrollador de plataformas, CRMs, sistemas de gestión y herramientas que optimizan operaciones empresariales
</td>
</tr>
</table>

<br/>

---

<br/>

<div align="center">

### Conectemos

[![GitHub](https://img.shields.io/badge/GitHub-esquivelfacundo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/esquivelfacundo)

<br/>

<sub>Construyendo software con propósito · React · APIs · Sistemas de gestión</sub>

<br/><br/>

<!-- Footer wave -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 60" width="100%" max-width="900">
  <defs>
    <linearGradient id="footer-accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#6366f1" stop-opacity="0"/>
      <stop offset="50%" stop-color="#6366f1" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#6366f1" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <rect width="900" height="1" y="0" fill="url(#footer-accent)"/>
  <text x="450" y="35" text-anchor="middle" font-family="system-ui, sans-serif" font-size="11" fill="#475569" letter-spacing="3">FACUNDO ESQUIVEL</text>
</svg>

</div>
