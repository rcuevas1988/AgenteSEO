# SmartSalesAssistant — Asistente Inteligente para Ventas y Auditoría Web

SmartSalesAssistant es un sistema inteligente diseñado para ayudar a negocios y agencias digitales a analizar sitios web, recolectar datos, generar reportes automáticos y brindar asistencia contextual usando modelos de lenguaje y scraping avanzado.

## 🧠 Funcionalidades destacadas

- 🔍 Análisis SEO y auditoría web automática (Lighthouse + Puppeteer)
- 🤖 Agente inteligente basado en LangChain + OpenAI
- 🌐 Scraping con Cheerio, Puppeteer y Newspaper
- 📊 Generación de reportes y dashboards con React + Recharts
- 🧩 UI profesional con TailwindCSS, Radix UI y animaciones modernas
- 💬 Integración con SERPAPI, DuckDuckGo y procesamiento de HTML

## 🛠️ Tecnologías utilizadas

- **Frontend:** React, TailwindCSS, Lucide, Framer Motion, CMDK  
- **Backend:** Express, LangChain, Puppeteer, Drizzle ORM  
- **IA / NLP:** OpenAI, LangChain Core & Community, Newspaper  
- **Scraping:** Puppeteer, Cheerio, DuckDuckGo-Search, SerpAPI  
- **Integraciones:** NeonDB, Notion API, HTML Parsing, SEO Linting

## 📦 Instalación

```bash
git clone https://github.com/tu-usuario/SmartSalesAssistant.git
cd SmartSalesAssistant
npm install
npm run dev
```

> Asegúrate de configurar tu archivo `.env` usando `.env.example` como base.

## 🚀 Scripts principales

```bash
npm run dev        # Entorno de desarrollo
npm run build      # Compilar para producción
npm run start      # Ejecutar app en producción
npm run db:push    # Sincronizar esquema DB (Drizzle)
```

## 📁 Estructura del proyecto

```
/server              → Lógica backend, scraping y agentes IA
/src                 → Componentes, páginas y hooks de frontend
/components          → Elementos reutilizables del UI
.env.example         → Variables de entorno requeridas
tailwind.config.ts   → Configuración de estilos
vite.config.ts       → Configuración de bundler
```

## 🔐 Requisitos

- Node.js 18+
- Cuenta en OpenAI con API Key
- NeonDB o PostgreSQL
- (Opcional) API Key de SerpAPI o DuckDuckGo

## 📄 Licencia

MIT © 2025 SmartSalesAssistant

---

> Esta plantilla avanzada está orientada a startups, agencias de automatización y desarrolladores que buscan integrar scraping, análisis SEO y agentes conversacionales en un solo sistema.
