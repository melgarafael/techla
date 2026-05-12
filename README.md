# Techla

> Operação Comercial com IA para Clínicas de Estética

Página de aplicação e documentação estratégica da **Techla** — agência de IA baseada em Divinópolis/MG, especializada em clínicas de estética com 2-3 funcionários.

## Estrutura

```
.
├── docs/                                ← Documentação estratégica completa
│   ├── README.md                        ← Índice mestre
│   ├── 01-estrategia/                   ← 3 Ps, posicionamento, modelo comercial
│   └── 02-operacao-comercial/
│       └── 01-pagina-aplicacao/
│           ├── 01-discovery.md          ← Fase 1
│           ├── 02-research.md           ← Fase 2 (concorrentes, linguagem, refs, dados)
│           ├── 03-briefing.md           ← Fase 3 — Mapa-mestre
│           ├── 04-copy.md               ← Fase 5 — Copy completa das 8 seções
│           ├── index.html               ← Página final (deploy)
│           └── previews/
│               ├── design-system.html   ← Design system v0.1
│               └── demo.html            ← Preview de hero + agitação
├── vercel.json                          ← Configuração de deploy
└── .gitignore
```

## A página

Single-file HTML (~76KB) com:

- 8 seções (Hero, Agitação, Calculadora ROI, Solução, Comparativo, Antecipação, Garantia, CTA + FAQ)
- Sistema visual "Chanel meets Linear" — champagne + rose-gold sobre `#0A0A0B`
- Tipografia Fraunces + Inter (Google Fonts)
- Calculadora de ROI interativa com fórmula real
- Conic-gradient animado, aurora gradient, particle field, glassmorphism, top-down spotlight
- WCAG AA · `prefers-reduced-motion` respeitado · responsivo 320px→1920px
- SEO: meta tags + Open Graph + JSON-LD Schema.org

## Stack

- HTML/CSS/JS puro (zero dependências de build)
- Google Fonts (Fraunces, Inter) via CDN
- Vercel (deploy estático)

## Construído com

Pipeline de 8 fases via Claude Code + agentes paralelos de pesquisa.

---

© 2026 Techla · Divinópolis/MG
