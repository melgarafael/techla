# Fase 1 — Discovery (Página de Aplicação)

> Síntese estratégica consolidada como input para as fases seguintes do pipeline GrowthOS.
> Data: 2026-05-12

---

## Inputs primários consumidos

- [`docs/01-estrategia/01-tres-ps.md`](../../01-estrategia/01-tres-ps.md)
- [`docs/01-estrategia/02-posicionamento.md`](../../01-estrategia/02-posicionamento.md)
- [`docs/01-estrategia/03-modelo-comercial.md`](../../01-estrategia/03-modelo-comercial.md)
- Entrevista complementar de objetivos da página (sessão 2026-05-12)

---

## Bloco A — Produto

| Campo | Valor |
|-------|-------|
| **Nome do produto** | Operação Comercial com IA — Plano Clínica Estética |
| **Promessa central** | Sua clínica atendendo, qualificando e agendando clientes 24h por dia — sem contratar mais ninguém |
| **Entregáveis** | Agente SDR no WhatsApp, sistema de agendamento, CRM com pipeline, follow-up automatizado, recuperação de no-show, reativação de base, relatório semanal, suporte regional |
| **Plano-âncora** | Completo — R$2.497 setup + R$897/mês |
| **Redução de risco** | Garantia 30 dias money-back + Performance bônus (2 meses grátis se não atingir 3x mensalidade em 90 dias) |
| **Prazo de implementação** | 7-14 dias úteis |

---

## Bloco B — Audiência

| Campo | Valor |
|-------|-------|
| **Persona** | Dona de clínica estética, 28-45 anos, biomédica esteta / dentista HOF / fisioterapeuta dermatofuncional / esteticista |
| **Tamanho do negócio** | 2-3 funcionários, faturamento R$50k-100k/mês |
| **Localização** | Divinópolis/MG e região (raio ~150km) |
| **Sub-nicho prioritário** | Harmonização orofacial / facial |
| **Dor #1 (intensidade máxima)** | Perde lead à noite e fim de semana (30-50% dos leads vazam) |
| **Tentativas frustradas** | Secretária extra (caro), curso de gestão (não aplicou), agência de tráfego (sem ROI claro) |
| **Nível de consciência (Schwartz)** | **Nível 3 — Consciente da Solução** |
| **Top 5 objeções** | 1. "Vai parecer robô" / 2. "Não vai entender da minha área" / 3. "Vou ficar dependente" / 4. "É caro pra começar" / 5. "Tecnologia dá problema" |

---

## Bloco C — Contexto de Mercado

| Campo | Valor |
|-------|-------|
| **USP (Unique Selling Proposition)** | Especialização vertical (só estética) + operação completa (não ferramenta solta) + presença regional (Divinópolis) |
| **Pricing-âncora** | R$2.497 setup + R$897/mês |
| **Prova social inicial** | Zero casos próprios. Substituir por: lógica + matemática de ROI conservadora + garantia agressiva + autoridade técnica |
| **Concorrentes a pesquisar (Fase 2)** | Asksuite, Lara (ServiceUp), Aitana, NovoBots, Botconversa, secretária terceirizada Latam |

---

## Bloco D — Objetivos da Página ⭐ (decidido nesta sessão)

| Campo | Decisão |
|-------|---------|
| **CTA primário** | **Aplicar para diagnóstico gratuito** — formulário leva a call de 30min de diagnóstico consultivo |
| **CTA secundário** | (a definir na narrativa — provavelmente "Falar direto no WhatsApp" como fallback ao final) |
| **Tom visual** | **Premium escuro tipo Stripe/Linear** — fundo escuro, tipografia refinada, sensação de software top-tier |
| **Profundidade** | **Médio — 6-8 seções** — equilíbrio entre densidade argumentativa e leiturabilidade |
| **Estratégia narrativa** | A definir na Fase 5 — provavelmente **PAS (Problem → Agitation → Solution)** com camada de antecipação Schwartz pré-CTA |
| **Formulário (campos obrigatórios)** | Nome, E-mail, Telefone (WhatsApp), Nome da clínica, Faturamento aproximado, Principal dor hoje |
| **Idioma** | pt-BR |
| **Domínio futuro** | A definir (sugestão: `techla.ai` / `techla.com.br` / `agendadahora.com.br` — discutir depois) |

### Justificativa das escolhas

**Por que "Aplicar para diagnóstico gratuito":**
- Ticket de R$2.497+R$897 exige call de fechamento (não é compra de impulso)
- "Diagnóstico" comunica consultoria, não venda — quebra resistência
- Formulário qualifica antes da call → você não desperdiça tempo com lead errado
- Casa com a metodologia do playbook (etapa de qualificação via IA SDR após o formulário)

**Por que tom Premium Escuro:**
- Nível 3 de consciência exige **diferenciação visual** — fugir do "look de agência de tráfego"
- Cliente está cansada de chatbot genérico → visual de software sério muda percepção
- Dark theme é o "uniforme do top-tier" em SaaS B2B — comunica "isso é coisa séria, não é brincadeira"
- Diferencia da concorrência local (que tende a usar templates claros padronizados)

**Por que 6-8 seções (médio):**
- Long-form excessivo cansa Nível 3 (já está pronto, não precisa ser convencido por 14 seções)
- Enxuto demais não dá espaço pra calculadora de ROI + comparativo Techla vs Secretária — que são as armas pesadas
- 6-8 seções permite: hero → dor → solução → ROI → comparativo → garantia → FAQ → formulário

---

## Estado do Pipeline

```json
{
  "project_slug": "techla-pagina-aplicacao-v1",
  "phase_current": 1,
  "phase_completed": ["1-discovery"],
  "decisions": {
    "cta_primary": "aplicar-diagnostico-gratuito",
    "visual_tone": "premium-dark-stripe-linear",
    "page_depth": "medium-6-8-sections",
    "language": "pt-BR",
    "consciousness_level": "schwartz-3-solution-aware"
  },
  "next_phase": "2-research"
}
```

---

## Próximo passo

**Fase 2 — Research:**
1. Análise dos 6 concorrentes listados (WebFetch + WebSearch)
2. Pesquisa de linguagem do público-alvo (Reddit, fóruns de estética, grupos de Facebook de proprietárias de clínica)
3. Seleção de 3-5 referências visuais alinhadas ao tom Premium Escuro (Stripe, Linear, Vercel, Cal.com, Attio)
