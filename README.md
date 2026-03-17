<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=F97316&height=120&section=header&text=Jonathan%20Terán&fontSize=42&fontColor=ffffff&fontAlignY=65&animation=fadeIn" alt="Header" />

<h3>Laravel Architect · AI Engineer · Infrastructure Coordinator</h3>

**Menos humo, más arquitectura, integración e impacto operativo.**

<br/>

<a href="https://amephia.com">
  <img src="https://img.shields.io/badge/🏢%20AmePhia%20Systems-F97316?style=for-the-badge&logoColor=white"/>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/jonathan-teran3/">
  <img src="https://img.shields.io/badge/LinkedIn-Jonathan%20Terán-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:jo-teran@hotmail.com">
  <img src="https://img.shields.io/badge/Email-Contáctame-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=JonathanTeran&label=Visitas&color=F97316&style=for-the-badge" />

</div>

---

## 🧠 Sobre mí

```yaml
nombre:       Jonathan Terán
ubicación:    Guayaquil, Ecuador 🇪🇨
empresa:      AmePhia Systems — amephia.com
rol:          Laravel Architect · AI Engineer · Infrastructure Coordinator
enfoque:      Software empresarial, automatización e integración de sistemas
especialidad: Laravel · AI Agents · DevOps · Flutter · Facturación SRI
```

Construyo soluciones tecnológicas para **operaciones reales**, no demos de laboratorio.

Dirijo el desarrollo en **[AmePhia Systems](https://amephia.com)**, empresa de software con base en Guayaquil, Ecuador, especializada en plataformas empresariales, automatización con IA e integraciones con servicios críticos. También trabajo como **Coordinador de Tecnología en la Federación Ecuatoriana de Fútbol (FEF)**, gestionando un portafolio de más de 30 proyectos tecnológicos activos.

Trabajo principalmente en:
- 🏗️ Sistemas empresariales con **Laravel** para entornos corporativos de misión crítica
- 🤖 Automatización de procesos con **IA y agentes** (RAG, orquestación, flujos autónomos)
- 🔌 Integraciones con APIs gubernamentales y servicios externos (SRI, DIGERCIC, COMET, SOAP)
- 🧾 **Facturación electrónica** y cumplimiento tributario en Ecuador
- ☁️ Infraestructura productiva: Docker, Cloudflare, Linux, Windows Server

---

## 🎯 En qué aporto más valor

| Área | Qué hago |
|------|----------|
| 🏛️ **Plataformas SaaS** | Arquitecturas multi-tenant con Laravel, roles, planes y facturación |
| 🔗 **Integraciones críticas** | APIs gubernamentales (SRI, DIGERCIC), SOAP, REST, webhooks empresariales |
| 🤖 **IA aplicada** | Agentes RAG, automatización con n8n, flujos conversacionales con Claude/OpenAI |
| 🧱 **Infraestructura productiva** | Docker, Nginx, PHP-FPM, Cloudflare Tunnels, CI/CD, monitoreo |
| 📱 **Mobile empresarial** | Apps Flutter conectadas a backends Laravel con auth y sync |
| 🧾 **Cumplimiento tributario** | Emisión RIDE, claves de acceso, firma XAdES, multi-tenant SRI Ecuador |

---

## 🚀 Proyectos destacados

### 🏟️ SIFEF — Sistema Integrado Federación Ecuatoriana de Fútbol
**Problema:** La FEF necesitaba unificar la gestión de clubes, jugadores, árbitros, competiciones, viajes e indumentaria en un solo sistema.  
**Solución:** ERP institucional con múltiples módulos operativos, integraciones con COMET y DIGERCIC, trazabilidad completa por entidad.  
**Stack:** `Laravel` `SQL Server` `Docker` `Redis` `IIS/Windows Server` `Cloudflare Tunnels`  
**Escala:** +30 proyectos tecnológicos activos derivados del ecosistema SIFEF en 2026.

---

### 🧾 Facturación Electrónica SRI — Plataforma Multi-tenant
**Problema:** Las empresas ecuatorianas necesitan emitir comprobantes electrónicos cumpliendo normativa SRI, con firma digital XAdES y envío automatizado.  
**Solución:** SaaS multi-tenant con generación de XML, firma, envío al SRI y descarga de RIDE. Construido sobre el package [`amephia/sri-ec`](https://packagist.org/packages/amephia/sri-ec) — del que soy autor.  
**Stack:** `Laravel 12` `MySQL` `Filament 3` `SOAP` `amephia/sri-ec`  
**Resultado:** Arquitectura reutilizable para múltiples empresas con aislamiento total de datos por tenant.

---

### 🤖 Agente Conversacional con RAG — IA aplicada al negocio
**Problema:** Cliente corporativo necesitaba reemplazar flujos ManyChat por respuestas inteligentes con contexto de su propia información.  
**Solución:** Sistema RAG con embeddings vectoriales, recuperación semántica y respuesta generativa conectado a base de conocimiento actualizable.  
**Stack:** `Claude API` `PostgreSQL + pgvector` `Redis` `n8n` `Laravel`  
**Resultado:** Agente conversacional con contexto real de negocio, sin dependencia de plataformas de terceros.

---

### 📡 SRI Automation — Descarga automática de comprobantes
**Problema:** Las empresas acumulan decenas de comprobantes electrónicos en el portal SRI que deben descargarse manualmente.  
**Solución:** Sistema RPA en la nube que automatiza el acceso al portal SRI, resuelve CAPTCHAs vía CapSolver y descarga comprobantes multi-empresa.  
**Stack:** `n8n` `Supabase` `CapSolver` `Python` `Playwright` `PostgreSQL` `Celery`  
**Resultado:** Eliminación del proceso manual de descarga para múltiples empresas desde un único sistema.

---

### 🏅 Enterprise Access — Acreditación para Eventos Masivos
**Problema:** Los eventos deportivos necesitan control de acceso trazable, credenciales digitales y validación biométrica en tiempo real.  
**Solución:** Plataforma SaaS B2B con módulos de acreditación por zonas, integración biométrica ZKTeco y panel de control multirol.  
**Stack:** `Laravel 12` `MySQL` `Flutter` `ZKTeco SDK` `Filament 3`  
**Resultado:** Arquitectura multirol con acceso por QR, biometría y auditoría completa de ingresos. Target: mercado deportivo latinoamericano.

---

### 📊 PixelTrack — Sistema de Pixel Tracking y Bridge Pages
**Problema:** Cliente de marketing digital necesitaba trazabilidad completa de conversiones con bridge pages personalizadas y gestión de píxeles.  
**Solución:** Sistema full-stack de tracking con bridge pages dinámicas, gestión de píxeles por campaña y dashboard de analítica.  
**Stack:** `Laravel 12` `Filament 3` `MySQL` `Cloudflare Workers`  

---

### 🎟️ GoTicket — Plataforma de gestión y venta de entradas
**Problema:** El cliente necesitaba digitalizar venta, control de aforo y analítica de eventos sin depender de soluciones externas.  
**Solución:** Plataforma propia con dashboard operativo, reportes en tiempo real y arquitectura modular para múltiples tipos de evento.  
**Stack:** `Laravel` `Livewire` `MySQL` `Chart.js` `Docker`  


---

### 🛡️ AmePhia Broker Seguro — Sistema de Corretaje con IA
**Problema:** Las brokers de seguros gestionan cotizaciones, pólizas y clientes de forma manual y dispersa, sin inteligencia sobre el portafolio.  
**Solución:** Plataforma integral para gestión de pólizas, cotizaciones automatizadas y asistente IA que analiza coberturas, sugiere productos y responde consultas del cliente.  
**Stack:** `Laravel` `Filament 3` `MySQL` `Claude API` `n8n` `Flutter`  
**Resultado:** Digitalización completa del ciclo de vida de una póliza con IA integrada como capa de inteligencia operativa.

---

### 🛒 E-commerce de Productos Generales — AmePhia Systems
**Problema:** Cliente necesitaba una tienda online propia, sin depender de marketplaces, con control total del catálogo, pagos y logística.  
**Solución:** E-commerce completo con gestión de inventario, carrito, pasarelas de pago locales y panel administrativo para operación autónoma.  
**Stack:** `Laravel` `Filament 3` `Livewire` `MySQL` `PayPhone` `Datafast`  

---

## ⚙️ Stack con el que trabajo

### Backend & Mobile
<p>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
</p>

### IA & Orquestación
<p>
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white"/>
</p>

### Datos & Infraestructura
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
</p>

---

## 🏛️ Especialización técnica

- **Arquitecturas Laravel** monolíticas modulares y SaaS multi-tenant listos para producción
- **Integraciones gubernamentales** — SRI (facturación electrónica, RIDE, XAdES), DIGERCIC (SOAP), COMET
- **Automatización con IA** — agentes RAG, flujos n8n, integración Claude/OpenAI con bases de datos propias
- **Infraestructura productiva** — Docker Compose, Nginx, PHP-FPM, Cloudflare Tunnels, SELinux, Rocky Linux
- **DevOps pragmático** — CI/CD con GitHub Actions, NSSM, monitoreo con PowerShell y workers Laravel Queue
- **Open Source Ecuador** — Autor de [`amephia/sri-ec`](https://packagist.org/packages/amephia/sri-ec), package Laravel para facturación electrónica SRI

---

## 📊 GitHub

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=JonathanTeran&show_icons=true&theme=dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=F97316&icon_color=F97316"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JonathanTeran&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=F97316"/>

</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=JonathanTeran&theme=dark&hide_border=true&background=0D1117&ring=F97316&fire=F97316&currStreakLabel=F97316"/>
</div>

---

## 🌱 Explorando ahora

- 🧩 **Multi-agent systems** para flujos de trabajo empresariales complejos
- ☁️ **Observabilidad y DevOps avanzado** — Kubernetes, Grafana, producción real
- 📱 **Flutter architecture** — Riverpod, clean architecture, apps corporativas

---

<div align="center">
  <br/>
  <strong>¿Tienes un sistema complejo que construir, integrar o escalar?</strong>
  <br/><br/>
  <a href="https://amephia.com">
    <img src="https://img.shields.io/badge/🌐%20amephia.com-F97316?style=for-the-badge&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:jo-teran@hotmail.com">
    <img src="https://img.shields.io/badge/📬%20Hablemos-111111?style=for-the-badge&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/jonathan-teran3/">
    <img src="https://img.shields.io/badge/💼%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <br/><br/>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=F97316&height=80&section=footer" />
</div>
