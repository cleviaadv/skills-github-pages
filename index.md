# Clévia Ramos · Legal Strategy, Automação Jurídica & Data Analytics
> **Advogada (OAB/BA 81.964) na interseção entre Direito, dados e tecnologia.**
Portfólio pessoal construído em **React 19 + TanStack Start + Tailwind CSS v4**, com foco em performance, SEO e uma experiência editorial refinada. O projeto destaca a trajetória de Clévia como advogada plena na Jusbrasil, combinando execução jurídica com automações, dashboards estratégicos e IA aplicada.
---
## ✨ Destaques
- **Site bilingue** (PT/EN) com persistência de idioma via `localStorage`
- **SEO otimizado** — meta tags, Open Graph e fontes pré-conectadas
- **Design editorial** — tipografia monumental com Fraunces, elementos verticais e paleta verde floresta
- **Seções completas**: Hero com estatísticas, Projetos, Método (4 passos), Stack técnica, Trajetória profissional (timeline), Insights, Sobre e Contato
- **Totalmente responsivo** — do mobile ao desktop ultra-wide
- **Tematização via CSS** — tokens semânticos em `oklch` no `styles.css`
---
## 🛠 Stack Tecnológica
| Camada | Tecnologia |
|--------|-----------|
| Framework | TanStack Start v1 (React 19 + SSR/SSG) |
| Estilo | Tailwind CSS v4 + design tokens customizados |
| Roteamento | TanStack Router (file-based) |
| Fontes | Fraunces, Inter, JetBrains Mono (Google Fonts) |
| Build | Vite 7 |
| Deploy | Edge (Cloudflare Workers) |
---
## 🚀 Como executar
```bash
# Instalar dependências
bun install
# Servidor de desenvolvimento
bun dev
# Build para produção
bun run build
```
---
## 📁 Estrutura
```
src/
├── components/          # Componentes de seção (Hero, Projects, Skills, etc.)
│   ├── ui/              # Componentes shadcn/ui (Button, Card, Dialog, etc.)
│   ├── Experience.tsx   # Timeline de carreira vertical
│   ├── Hero.tsx         # Hero com texto monumental e estatísticas
│   ├── Projects.tsx     # Grid de projetos com Problem → Solution → Impact
│   └── Skills.tsx       # Chips de stack técnica categorizados
├── lib/
│   └── i18n.tsx         # Contexto de internacionalização (PT/EN)
├── routes/
│   ├── index.tsx        # Página principal — monta todas as seções
│   └── __root.tsx       # Layout raiz (html/head/body)
├── router.tsx           # Configuração do TanStack Router
├── styles.css            # Design tokens, tema verde floresta
└── assets/              # Imagens e mídia
```
---
## 🎨 Identidade Visual
- **Paleta**: Verde floresta profundo com acentos em tons quentes
- **Tipografia display**: Fraunces (editorial, serifada)
- **Tipografia corpo**: Inter (clean, legível)
- **Mono**: JetBrains Mono (dados, código, chips)
- **Direção**: Editorial sofisticado com elementos de revista — texto vertical, grids assimétricos e generosos espaços em branco
---
## 📬 Contato
- **LinkedIn**: [https://www.linkedin.com/in/clevia-cristina-ramos/]
- **E-mail**: cleviaramos.adv@gmail.com
- **WhatsApp**: +55 71 98253-3387
---
> Construído com cuidado. Salvador, BA → São Paulo · 2026
