<h1 align="center">Iván Jonás Fernández Correa</h1>
<h3 align="center">DevOps & Full-Stack Developer — perfil híbrido dev + sistemas</h3>
<p align="center"><i>Gijón, Asturias · Disponible en remoto/nacional e híbrido o presencial en Asturias</i></p>

<p align="center">
  <a href="https://portfolio.ivanjonasfc.dev" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-ff6b00?style=for-the-badge&logo=astro&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/ivanjonasfc/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:ivanjonasfc@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>
  <a href="https://portfolio.ivanjonasfc.dev/cv/CV-Ivan-Jonas-ES.pdf" target="_blank">
    <img src="https://img.shields.io/badge/CV-4b5563?style=for-the-badge&logo=readthedocs&logoColor=white" alt="CV">
  </a>
</p>

---

## Sobre mí

Perfil **híbrido dev + sistemas**: escribo el código y administro la infraestructura donde corre. Titulado en **ASIR** (administración de sistemas en red) y **DAM** (desarrollo multiplataforma). Combino desarrollo full-stack (Java, Python, TypeScript, NestJS, React) con infraestructura como código (Docker, Linux, CI/CD) y uso avanzado de IA (RAG, MCP, agentes).

Proyectos **reales en producción**: dos clientes, un home lab 24/7 y una suite propia con IA. Autodidacta con capacidad demostrada de llevar proyectos de extremo a extremo.

## Proyecto destacado: LifeOS

**Suite familiar self-hosted con IA propia (en desarrollo).** Elimina dependencias de servicios cloud comerciales con una arquitectura modular bajo tu propio control.

<p align="center"><img src="icon.png" alt="LifeOS" width="170" /></p>

- **Chat en tiempo real** (WebSockets) y notificaciones push (Gotify)
- **Calendario** compartido con recordatorios
- **Gestor de gastos** con reparto de deudas en tiempo real
- **Lista de compra** colaborativa, **notas**, **nube** con galería y cuotas por usuario
- **Geolocalización** y **panel de administración** (observabilidad de BD, migraciones, depurador de Docker)
- **IA propia "Lito"**: RAG sobre pgvector/Qdrant + LLMs vía **Model Context Protocol (MCP)**

Multitenant y federación con cifrado **AES-GCM**, seguridad **JWT**, i18n ES/EN.

**Stack** — Backend: NestJS + PostgreSQL + TypeORM + BullMQ + Redis · Frontend: Angular 18 + Ionic 8 + Capacitor · DevOps: Docker + Caddy + Cloudflare

---

## Home Lab e infraestructura (Pesoz, 24/7)

~30 servicios en **Docker** sobre un **NAS Synology DS224+**, replicando arquitecturas de producción para I+D:

- **Red y acceso** — Caddy (TLS automático), WireGuard VPN con allow-list, Cloudflare DNS + DDNS, AdGuard Home
- **Datos** — PostgreSQL, Redis, Qdrant + pgvector, MongoDB
- **Observabilidad** — Prometheus, Grafana, Loki, Tempo, cAdvisor
- **Entrega (GitOps)** — Forgejo (Git + CI/CD), n8n, Portainer
- **Media e IA local** — Jellyfin, LLMs locales; backups automatizados con pruebas de restauración

---

## Tech Stack

**Lenguajes**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="38" alt="java" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="38" alt="python" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="38" alt="typescript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="38" alt="javascript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" height="38" alt="dart" />
</p>

**Backend y Frontend**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" height="38" alt="nestjs" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" height="38" alt="spring" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" height="38" alt="fastapi" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angular/angular-original.svg" height="38" alt="angular" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="38" alt="react" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="38" alt="nextjs" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/astro/astro-original.svg" height="38" alt="astro" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ionic/ionic-original.svg" height="38" alt="ionic" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" height="38" alt="flutter" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" height="38" alt="tailwind" />
</p>

**Datos e IA**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="38" alt="postgresql" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="38" alt="mongodb" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="38" alt="redis" />
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat&logo=qdrant&logoColor=white" height="28" alt="qdrant" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white" height="28" alt="pgvector" />
  <img src="https://img.shields.io/badge/RAG_·_MCP-ff6b00?style=flat&logoColor=white" height="28" alt="rag-mcp" />
</p>

**DevOps e infraestructura**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="38" alt="docker" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="38" alt="linux" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="38" alt="git" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prometheus/prometheus-original.svg" height="38" alt="prometheus" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" height="38" alt="grafana" />
  <img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat&logo=caddy&logoColor=white" height="28" alt="caddy" />
  <img src="https://img.shields.io/badge/Forgejo-FB923C?style=flat&logo=forgejo&logoColor=white" height="28" alt="forgejo" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" height="28" alt="n8n" />
  <img src="https://img.shields.io/badge/WireGuard-88171A?style=flat&logo=wireguard&logoColor=white" height="28" alt="wireguard" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white" height="28" alt="cloudflare" />
</p>

---

## Objetivos

Busco un rol de ingeniería donde aportar mi **mentalidad de sistemas aplicada al ciclo de vida del software**:

- Arquitecturas cloud-native y microservicios
- CI/CD e infraestructura como código (IaC)
- Observabilidad y monitorización
- Seguridad desde el diseño (DevSecOps)
- Integración de IA en producto (RAG, MCP, agentes)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=IvanjonasFC&show_icons=true&hide_border=true&count_private=true&title_color=ff6b00&icon_color=ff6b00" height="150" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IvanjonasFC&layout=compact&hide_border=true&title_color=ff6b00" height="150" alt="top-langs" />
</p>

<p align="center"><i>Disponible para nuevos proyectos y colaboraciones.</i></p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=IvanjonasFC&label=Visitas&color=ff6b00&style=flat" alt="Visitas" />
</p>
