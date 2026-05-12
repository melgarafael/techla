# Fase 3 — Briefing Estratégico (Mapa-Mestre de Construção)

> **Este documento é a única referência necessária para construir a página.**
> Quem abrir só este arquivo deve ser capaz de produzir a landing inteira sem consultar mais nada.
> Versão: 1.0 — 2026-05-12
> Status: Aprovação pendente do Rafael

---

# 📑 ÍNDICE NAVEGÁVEL

1. [Sumário Executivo](#1-sumário-executivo) — leia primeiro, 1 página
2. [Fundamentos Estratégicos](#2-fundamentos-estratégicos) — o porquê de tudo
3. [Arquitetura da Página](#3-arquitetura-da-página) — mapa das 8 seções
4. [Blueprint Seção a Seção](#4-blueprint-seção-a-seção) — instrução de construção
5. [Sistema Visual](#5-sistema-visual) — tokens, componentes, motion
6. [Sistema de Copy](#6-sistema-de-copy) — voz, vocabulário, padrões
7. [Arquitetura de Conversão](#7-arquitetura-de-conversão) — CTA, formulário, objeções
8. [Mapa Informacional](#8-mapa-informacional) — onde achar cada insumo
9. [Métricas de Sucesso](#9-métricas-de-sucesso) — como saber se funcionou
10. [Anti-padrões](#10-anti-padrões) — o que NUNCA fazer

---

# 1. Sumário Executivo

## O que estamos construindo

Uma **landing page de aplicação** para a **Techla** — agência de IA baseada em Divinópolis/MG que vende **Operação Comercial com IA pra Clínicas de Estética**. A página tem **um único objetivo**: fazer a dona de uma clínica de estética preencher um formulário para uma **call de diagnóstico gratuito**.

## A 1-Frase de Diretriz Criativa

> **"Stripe encontra Chanel. Ogilvy escreve. Schwartz arquiteta. A página fala empresária — não fala tech."**

## A Grande Promessa (memorizar)

> **Sua clínica atendendo, qualificando e agendando clientes 24h por dia — sem contratar mais uma secretária.**

## Os 5 elementos não-negociáveis

1. ⭐ **Estatística-âncora epistemológica:** MIT/Harvard — *"Responder em 5 min = 21x mais chance de fechar venda que em 30 min."* Toda a tese da página orbita esse fato.
2. ⭐ **Diferenciação visual:** champagne (`#D4A574`) + rose-gold sobre preto azulado (`#0A0A0B`). Fraunces serif italic em UMA palavra-chave. Anti-convergência B2B.
3. ⭐ **Calculadora de ROI interativa** — a cliente faz a conta sozinha e percebe que perde mais do que custa a Techla.
4. ⭐ **Comparativo Techla vs. Secretária CLT** — tabela que mata a dor #5 com matemática brutal.
5. ⭐ **Garantia dupla** — 30 dias money-back + Performance bônus (2 meses grátis em 90 dias).

## Decisões finais consolidadas

| Decisão | Valor |
|---------|-------|
| **CTA primário** | "Aplicar para diagnóstico gratuito" (formulário inline no hero) |
| **CTA secundário** | "Falar direto no WhatsApp" (rodapé, fallback) |
| **Profundidade** | 8 seções (médio-longo) |
| **Framework narrativo** | **PAS + Antecipação Schwartz** (Problem → Agitation → Solution + Future Pacing) |
| **Tom visual** | Premium escuro editorial — "Chanel meets Linear" |
| **Tipografia** | Fraunces (display) + Inter (body) — ambas Google Fonts |
| **Paleta** | `#0A0A0B` base, `#D4A574` rose-gold accent, `#F5F4F0` text |
| **Idioma** | pt-BR (interior de MG — tom direto, sem anglicismo) |

---

# 2. Fundamentos Estratégicos

## 2.1 — Quem é a leitora (em 1 parágrafo)

Mulher entre 28-45 anos, biomédica esteta ou dentista HOF, em Divinópolis ou região, atende clientes 8-10h por dia, dona de clínica com 2-3 funcionários e faturamento entre R$50-100k/mês. Aprendeu marketing no Instagram. Já tentou contratar mais secretária (caro), curso de gestão (não aplicou) e agência de tráfego (gastou e não viu retorno). Sente que **chegou ao limite operacional** e tem medo de crescer porque crescer significa contratar — e contratar significa mais dor de gestão. **Não compra tecnologia. Compra liberdade.**

## 2.2 — Nível de consciência (Eugene Schwartz)

**Nível 3 — Consciente da Solução.** Ela já sabe que tem problema, já ouviu falar de IA/chatbot, **não está convencida que funciona pro caso dela**. Implicações operacionais:

- ❌ Não educar sobre o problema (ela vive ele todo dia)
- ❌ Não educar sobre IA (ela já ouviu até demais)
- ✅ **Provar que funciona PRO CASO DELA** (specificidade vertical)
- ✅ **Diferenciar Techla de chatbot genérico** (gap competitivo)
- ✅ **Mostrar matemática** (ela é empresária — números convencem)

## 2.3 — Framework Narrativo: PAS + Antecipação Schwartz

```
P  PROBLEMA       → "Você perde R$ todo dia. Já sabe disso."
A  AGITAÇÃO       → "Esse R$ tem nome, tem hora, tem cara. Vamos calcular?"
S  SOLUÇÃO        → "A Techla fecha o ralo. Eis como."
[+ ANTECIPAÇÃO]  → "Em 60 dias, sua clínica é outra. Eis o futuro com Techla."
[+ PROVA]        → "Garantia, matemática, comparativo."
[+ CTA]          → "Aplique para um diagnóstico gratuito agora."
```

**Por que PAS + Antecipação (não AIDA puro nem Story Bridge):**
- AIDA serve melhor pra Nível 1-2 (introduzir produto)
- Story Bridge serve melhor pra produto novo/inédito
- **PAS** é o framework de mais alta conversão pra Nível 3 (público que sente dor diariamente)
- A camada de **Antecipação Schwartz** (visualização do futuro) faz a oferta deixar de ser "compra" e virar "transferência pra outra realidade"

## 2.4 — Os 3 Eixos de Diferenciação

A página inteira reforça três vetores únicos da Techla:

| Eixo | Como aparece na página |
|------|------------------------|
| **1. Especialização vertical** | Vocabulário do nicho ("protocolo", "anamnese", "HOF"), exemplos só de estética, NUNCA "qualquer negócio" |
| **2. Operação completa** | Listar TUDO que entra (agente + CRM + follow-up + reativação + relatório) — não vendemos chatbot solto |
| **3. Presença regional** | Mencionar Divinópolis/MG. "Suporte de quem está perto, não fila de atendimento de SP." |

## 2.5 — Mapeamento das 5 Dores → Páginas da Página

Cada seção tem que tocar pelo menos uma dor dos 3 Ps:

| Dor (dos 3 Ps) | Seção que toca |
|----------------|----------------|
| Perde lead à noite/fim de semana | Hero + Seção 2 (Agitação) + Calculadora ROI |
| Secretária só agenda, não vende | Seção 3 (Solução) + Comparativo |
| 25% de no-show | Calculadora ROI + Seção Solução |
| Base de WhatsApp morta | Solução + Antecipação (futuro) |
| Não cresce sem contratar | Comparativo Techla vs Secretária + Antecipação |

---

# 3. Arquitetura da Página

## 3.1 — As 8 seções em ordem

```
┌─────────────────────────────────────────────────────────┐
│  1. HERO                                                 │
│     Headline + sub-headline + form inline + mockup      │
│     Função: parar o scroll, ancorar promessa            │
├─────────────────────────────────────────────────────────┤
│  2. AGITAÇÃO (o ralo invisível)                          │
│     A estatística MIT + visualização do prejuízo         │
│     Função: nomear a dor com matemática                  │
├─────────────────────────────────────────────────────────┤
│  3. CALCULADORA DE ROI                                   │
│     Interativa — 4 sliders + output em R$/mês            │
│     Função: fazer a leitora se ver no número             │
├─────────────────────────────────────────────────────────┤
│  4. SOLUÇÃO (a operação completa)                        │
│     Bento grid com 6 componentes da operação             │
│     Função: mostrar o quê + como funciona                │
├─────────────────────────────────────────────────────────┤
│  5. COMPARATIVO TECHLA vs SECRETÁRIA                     │
│     Tabela visual — 9 linhas de comparação               │
│     Função: matar a dor "não posso crescer sem contratar"│
├─────────────────────────────────────────────────────────┤
│  6. ANTECIPAÇÃO (futuro com vs sem)                      │
│     "30 dias, 60 dias, 90 dias depois"                   │
│     Função: future pacing — criar desejo                 │
├─────────────────────────────────────────────────────────┤
│  7. GARANTIA + COMO COMEÇAR                              │
│     Garantia dupla + 3 passos da implementação           │
│     Função: anular risco percebido                       │
├─────────────────────────────────────────────────────────┤
│  8. CTA FINAL + FAQ                                      │
│     Formulário grande + 6 FAQs estratégicos              │
│     Função: capturar lead + responder objeção residual   │
└─────────────────────────────────────────────────────────┘
```

## 3.2 — Lei da Conversão Vertical

A cada 2-3 seções, **deve haver um momento de CTA** (não necessariamente o formulário — pode ser um botão "Quero meu diagnóstico"). Mapa:

- Hero (formulário inline) ✅
- Pós-calculadora (botão CTA)
- Pós-comparativo (botão CTA)
- Pós-antecipação (botão CTA)
- Final (formulário completo) ✅

**5 oportunidades de conversão em 1 scroll.**

## 3.3 — Hierarquia de leitura (F-pattern adaptado)

A leitora não lê tudo. Lê:
1. Headline do hero
2. Sub-headline
3. Bullets (se houver)
4. **Headlines de cada seção**
5. Números grandes (estatísticas + R$ da calculadora)
6. CTA

**Implicação:** cada seção deve ter uma **headline auto-suficiente** (entendível sem ler o body) e um **número grande** (se possível). A leitora que só rolou já saiu vendida.

---

# 4. Blueprint Seção a Seção

> Cada blueprint contém: **Função estratégica · Copy direction · Visual direction · Referências cruzadas · Critérios de sucesso**.

---

## 🔷 SEÇÃO 1 — HERO

### Função estratégica
- Parar o scroll em <3 segundos
- Estabelecer a Grande Promessa
- Coletar lead JÁ (form inline) — para a leitora pronta

### Copy direction

**Headline (Fraunces, 1 palavra italic):**
> **A IA que sua clínica precisa para nunca mais perder uma cliente *enquanto você dorme*.**

(Variação testar: *"A IA que atende sua clínica enquanto você **dorme**, qualifica enquanto você **atende**, e agenda enquanto você **fecha o caixa**."*)

**Sub-headline (Inter, 1 linha):**
> Especializada em clínicas de estética com 2-3 funcionários. Implementação em 14 dias. Garantia de 30 dias.

**Microcopy do form:**
- Label: "Aplique para um diagnóstico gratuito"
- Placeholder do WhatsApp: "WhatsApp da clínica (com DDD)"
- Botão: "Quero meu diagnóstico"
- Compromisso: "Sem custo. Sem compromisso. Apenas se fizer sentido."

### Visual direction

- **Layout:** headline esquerda alinhada (60% da largura), mockup do dashboard à direita (40%) com `tilt 3D sutil + sombra difusa gigante`
- **Background:** `#0A0A0B` base + **gradient mesh** champagne→rosé animado lentíssimo (cycle 30s) atrás da headline
- **Headline:** Fraunces, `clamp(56px, 8vw, 96px)`, peso 500, leading 1.05, tracking -0.02em. UMA palavra em italic.
- **Sub-headline:** Inter, 18-20px, peso 400, opacity 0.7
- **Form:** horizontal, fundo `#131316`, border `1px solid rgba(212,165,116,0.18)`, input transparente, botão `#D4A574` sólido com texto `#0A0A0B`
- **Mockup:** screenshot estilizado de WhatsApp com bolha do agente Techla + dashboard de CRM ao fundo, em browser frame
- **Animação:** mesh em movimento contínuo + headline fade-in 600ms, mockup tilt-in 800ms com easing cubic-bezier

### Referências cruzadas
- Hero: **Stripe** (mesh + headline-form) + **Cal.com** (form inline) + **Attio** (mockup com sombra)
- Promessa: `02-posicionamento.md` § Grande Promessa
- Form: `03-modelo-comercial.md` § Bloco D Discovery (campos do formulário)

### Critérios de sucesso da seção
- ✅ Leitora entende o que é Techla em <5 segundos
- ✅ Promessa não usa palavra "IA" mais que 1x
- ✅ Form tem zero fricção (1 campo visível: WhatsApp)
- ✅ Mockup é específico de clínica (não genérico)

---

## 🔷 SEÇÃO 2 — AGITAÇÃO (O Ralo Invisível)

### Função estratégica
- Validar a dor da leitora com matemática
- Plantar a estatística-âncora MIT/Harvard
- Preparar mentalmente pra Calculadora (seção 3)

### Copy direction

**Headline:**
> Todo dia, sua clínica perde dinheiro *invisível*.

**Sub-headline:**
> Não é sobre vender mais. É sobre parar de perder o que já é seu.

**Body (3 blocos curtos):**

> **R$ 8.000 por mês** somem em leads que chegam às 22h e nunca são respondidos.
> *"Se a clínica leva horas para responder, o paciente esfria."* — Valentins Digital, 2024
> Responder em 5 minutos te dá **21x mais chance** de fechar venda do que responder em 30. **MIT / Harvard Business Review.**

> **R$ 12.000 por mês** evaporam em no-show. *Falta dói no caixa e na agenda.*
> 1 em cada 3 clínicas brasileiras perde **mais de 10%** das consultas marcadas. *Panorama Clínicas 2026.*

> **R$ 6.000 por mês** estão parados na sua base de WhatsApp. *Cliente que sumiu não é destino — é retorno que ninguém marcou.*

### Visual direction

- **Layout:** 3 colunas (desktop) / 3 cards empilhados (mobile)
- **Cada bloco:** R$ grande em Fraunces (cor `#D4A574`), peso 500, ~64px + linha em Inter abaixo
- **Background:** `#0A0A0B` puro com **subtle noise texture** (1% opacity)
- **Divisores:** linhas finas `1px solid rgba(245,244,240,0.06)` separando os blocos
- **Citações:** Inter italic, 14px, opacity 0.5, antes de cada estatística
- **Estatística MIT:** card especial, fundo `#131316`, border destaque rose-gold, headline "21x" em Fraunces gigante

### Referências cruzadas
- Estatísticas: `02-research.md` § Dados de Mercado
- Citações de blogs: `02-research.md` § Linguagem do Público
- Tom: `02-posicionamento.md` § Hook de abertura
- Copy "falta dói no caixa": citação literal do Valentins Digital

### Critérios de sucesso
- ✅ Leitora reconhece a dor em 1ª pessoa ("é exatamente o que acontece comigo")
- ✅ Estatística MIT fica grudada na memória
- ✅ Citações trazem voz autêntica do nicho (não suam tech)

---

## 🔷 SEÇÃO 3 — CALCULADORA DE ROI

### Função estratégica
- Forçar a leitora a fazer a conta com OS NÚMEROS DELA
- Transformar abstração em valor concreto pessoal
- Pré-vender antes do pitch da solução

### Copy direction

**Headline:**
> Faça a conta. Quanto sua clínica perde *agora*?

**Sub-headline:**
> Use os sliders abaixo com os números reais da sua clínica. O cálculo é conservador.

**4 sliders (com valores default):**
1. **Leads recebidos por mês** (default: 150, range 50-500)
2. **Ticket médio por procedimento** (default: R$1.200, range R$300-R$3.000)
3. **% de no-show atual** (default: 25%, range 10-40%)
4. **Tamanho da base de contatos inativos** (default: 1.500, range 200-3.000)

**Output (atualiza em tempo real):**

> Sua clínica perde, conservadoramente, **R$ XX.XXX por mês**.
>
> Recuperando só **30%** disso com a Techla, você ganharia **R$ YY.YYY/mês líquidos** (já descontados os R$ 897 da mensalidade).
>
> Em 12 meses: **R$ ZZZ.ZZZ recuperados**.

**CTA in-section:**
> "Quero parar de perder esse dinheiro" → leva ao formulário

### Visual direction

- **Layout:** sliders à esquerda (50%), card de resultado à direita (50%) — sticky no mobile
- **Sliders:** track `#131316` + handle `#D4A574` + label do valor atual em Fraunces número
- **Card de resultado:** fundo `#131316`, border `2px solid rgba(212,165,116,0.3)`, sombra glow rose-gold sutil
- **Número grande de perda:** Fraunces, `clamp(48px, 6vw, 80px)`, cor `#F5B7B1` (rosé — sinaliza perda emocional)
- **Número de recuperação:** Fraunces, cor `#7DD3A8` (sage green success)
- **Animação:** sliders animam o número com easing 400ms, transição de cor

### Referências cruzadas
- Cálculo: `03-modelo-comercial.md` § A Matemática do ROI (cenário-base)
- Inspiração: **BeautyBot** tem calculadora no topo (analisado em `02-research.md`)
- Princípio Schwartz: "o leitor não quer ser convencido, quer convencer a si mesmo"

### Critérios de sucesso
- ✅ Funciona sem JS quebrar
- ✅ Default values geram um número impactante (>R$30k de perda)
- ✅ Output muda em tempo real, sem lag
- ✅ CTA aparece imediatamente quando número é calculado

---

## 🔷 SEÇÃO 4 — SOLUÇÃO (Operação Completa)

### Função estratégica
- Mostrar que NÃO é "só chatbot"
- Listar TUDO que entra na operação (densidade comunica seriedade)
- Diferenciar de concorrente (BeautyBot vende módulos avulsos)

### Copy direction

**Headline (Fraunces, italic na palavra-chave):**
> Não é chatbot. É *operação*.

**Sub-headline:**
> A Techla monta toda a estrutura comercial da sua clínica com IA. Em 14 dias.

**Bento grid — 6 cards:**

1. **🤖 Agente SDR no WhatsApp 24/7**
   > Atende, qualifica e agenda — em português natural, treinado com o vocabulário da sua clínica. Não parece robô. Acolhe.

2. **📅 Sistema de Agendamento Integrado**
   > A agenda fecha sozinha. Lembrete automático 24h antes e 2h antes. No-show despenca.

3. **📊 CRM com Pipeline Visual**
   > Veja cada lead no funil: novo → qualificado → agendado → fechado. Sem planilha, sem WhatsApp Business bagunçado.

4. **🔁 Follow-up Automatizado**
   > Lead que não fechou recebe sequência de 3-5 toques em horários estratégicos. A IA não esquece.

5. **💌 Reativação de Base Inativa**
   > Sua base de 1.500 contatas adormecidas vira receita. Campanha mensal com mensagem personalizada.

6. **📈 Relatório Semanal**
   > Métricas reais: leads atendidos, taxa de qualificação, agendamentos, no-show recuperado. Toda segunda-feira no seu WhatsApp.

### Visual direction

- **Layout:** bento grid 3x2 (desktop), 1x6 (mobile)
- **Cada card:** fundo `#131316`, border `1px solid rgba(212,165,116,0.12)`, padding 32px
- **Ícone:** custom outline ícone, cor `#D4A574`, 32px
- **Headline do card:** Fraunces, 24px, peso 500
- **Body:** Inter, 15px, opacity 0.75
- **Mini-mockup ou viz por card:** screenshot estilizado, gráfico pequeno, ou animação CSS (depende do componente)
- **Hover:** card sobe `translateY(-4px)` + glow border `rgba(212,165,116,0.3)`

### Referências cruzadas
- Lista de componentes: `03-modelo-comercial.md` § O que a cliente recebe
- Inspiração visual: **Vercel** bento grid + **Linear** card styling
- Posicionamento "não é chatbot, é operação": `02-posicionamento.md` § Mecanismos Únicos

### Critérios de sucesso
- ✅ Cada card tem 1 frase emocional + 1 frase racional
- ✅ Densidade visual sem confusão (uso de espaçamento)
- ✅ Ícones todos no mesmo estilo (outline, não preenchido)
- ✅ Leitora entende: "comprar Techla = comprar 6 coisas, não 1"

---

## 🔷 SEÇÃO 5 — COMPARATIVO TECHLA vs SECRETÁRIA

### Função estratégica
- Matar a objeção "vou contratar mais uma secretária" (dor #5)
- Usar matemática brutal pra forçar a comparação
- Posicionar o ticket de R$ 897 como **barato** vs alternativa óbvia

### Copy direction

**Headline:**
> Pelo preço de *meia secretária*, sua clínica ganha uma operação inteira.

**Sub-headline:**
> Comparado a contratar mais uma secretária CLT no interior de MG.

**Tabela — 9 linhas:**

| Critério | Secretária Adicional CLT | Techla (Plano Completo) |
|----------|--------------------------|--------------------------|
| Custo mensal real | R$ 2.400-2.800 (salário + 35% encargos) | **R$ 897** |
| Horário de trabalho | 8h/dia, segunda a sexta | **24/7, todos os dias** |
| Tempo de resposta | Minutos a horas | **Segundos** |
| Treinamento | 30-90 dias | **Pronta em 14 dias** |
| Férias / faltas / atestados | Custo extra ou clínica para | **Não existe** |
| Esquece follow-up | Acontece toda semana | **Não esquece** |
| Custos trabalhistas no desligamento | Aviso, multa FGTS, rescisão | **Cancelamento direto** |
| Dobrar volume | Contratar mais uma | **Sem custo adicional** |
| Faz reativação de base | Não tem tempo | **Sim, automaticamente** |

**CTA in-section:**
> "Faz mais sentido contratar a Techla" → leva ao formulário

### Visual direction

- **Layout:** tabela em 2 colunas com header sticky, mobile vira cards comparativos lado a lado
- **Coluna Secretária:** cor neutra, opacity 0.7, ícones cinza
- **Coluna Techla:** cor `#D4A574`, fundo levemente realçado `#131316`, ícones rose-gold
- **Linhas:** alternam fundo `#0A0A0B` / `#0C0C0E` (zebra striping sutil)
- **Linha de custo (primeira):** destaque visual extra, números em Fraunces grande
- **Microanimação:** linhas fade-in com stagger 80ms cada na entrada do viewport

### Referências cruzadas
- Tabela: `03-modelo-comercial.md` § Comparativo "Techla vs. Secretária Adicional"
- Salário real MG: `02-research.md` § Custo CLT secretária (Salário.com.br RAIS/CAGED)
- Inspiração: **Attio** tem padrão de "comparison table"

### Critérios de sucesso
- ✅ Cada linha é factual, não exageros
- ✅ Mobile não quebra (cards comparativos)
- ✅ Leitora termina a tabela mentalmente vendida
- ✅ Aparece um botão CTA imediatamente após

---

## 🔷 SEÇÃO 6 — ANTECIPAÇÃO (Future Pacing)

### Função estratégica
- Esta é a **etapa de Antecipação** do funil GrowthOS (ver `00-playbook-referencia.md`)
- Fazer a leitora **visualizar o futuro com a Techla**
- Antecipar valor, antecipar transformação, antecipar identidade nova

### Copy direction

**Headline:**
> 60 dias depois, sua clínica é *outra*.

**Sub-headline:**
> Não na receita. Na sensação. (Na receita também — mas a sensação muda primeiro.)

**Timeline com 3 marcos:**

**📍 Dia 14 — Go-live**
> O agente entra no ar. Você dorme tranquila pela primeira vez em meses. O lead que chegou às 23h47 já foi atendido, qualificado e tem horário pra terça-feira.

**📍 Dia 30 — Primeiro Relatório**
> 87 leads atendidos. 41 qualificados. 18 agendadas. 3 no-shows evitados. Sua secretária está focada no que importa. Você ganhou tempo de volta.

**📍 Dia 60 — Sua Clínica é Outra**
> Você fatura 30-40% mais sem ter contratado ninguém. Sua base inativa virou receita. Sua agenda fecha sozinha. Você está pensando em abrir a **segunda unidade** — porque agora cresceu sem dor de gestão.

**Frase de fechamento:**
> Essa é a clínica que a Techla constrói.
> Em 60 dias.

### Visual direction

- **Layout:** timeline vertical à esquerda, conteúdo de cada marco à direita
- **Linha do tempo:** linha vertical `1px solid rgba(212,165,116,0.3)` com pontos `#D4A574` em cada marco
- **Background:** `#0A0A0B` puro
- **Cada marco:** card sutil, fundo `#131316`, padding generoso, animação fade-in com stagger ao scroll
- **Headlines de marco:** Fraunces, 32px, com 📍 emoji ou ícone customizado champagne
- **Frase de fechamento:** centralizada, Fraunces italic, 28px, peso 400, opacity 0.9
- **Microanimação:** ao scroll, o ponto da timeline ativa com glow + linha desenha

### Referências cruzadas
- Funil playbook: `00-playbook-referencia.md` § Etapa Antecipação
- Future pacing principle: técnica clássica de Schwartz / Tony Robbins
- Tom narrativo: `02-posicionamento.md` § Storyboard de prova social

### Critérios de sucesso
- ✅ Leitora consegue visualizar a cena (não é abstração)
- ✅ Os números são plausíveis, não exagero
- ✅ A "abrir segunda unidade" no dia 60 é o gancho ambicioso
- ✅ Frase de fechamento dá pele de galinha

---

## 🔷 SEÇÃO 7 — GARANTIA + COMO COMEÇAR

### Função estratégica
- Anular o risco percebido (objeção "e se não funcionar?")
- Mostrar processo simples (objeção "vai ser complicado?")

### Copy direction

**Headline:**
> Se não funcionar, *você não paga*.

**Sub-headline:**
> Duas garantias. Porque a gente tem certeza que funciona.

**Garantia 1 — Card grande:**

> **30 dias ou seu dinheiro de volta.**
> Implementamos sua operação completa em 14 dias. Você tem **30 dias corridos a partir do go-live** pra testar. Se não estiver satisfeita, devolvemos 100% — setup e mensalidade.

**Garantia 2 — Card grande:**

> **90 dias ou 2 meses grátis.**
> Se em 90 dias a operação não recuperar pelo menos **3x o valor da mensalidade** em receita atribuível (no-show evitado + leads convertidos), você ganha **2 meses adicionais grátis**. Medido pelo CRM da própria operação.

**Subseção: Os 3 passos da implementação**

1. **Aplicação** — Você preenche o formulário, a gente agenda uma call de diagnóstico (30min, gratuita)
2. **Setup** — Em 14 dias úteis, sua operação está pronta: agente treinado, CRM configurado, WhatsApp conectado
3. **Go-live + Acompanhamento** — A operação entra no ar. Revisão semanal nos primeiros 90 dias. Suporte direto no WhatsApp.

### Visual direction

- **Layout:** 2 cards de garantia lado a lado, depois 3 passos em timeline horizontal
- **Cards de garantia:** fundo `#131316`, border `2px solid rgba(212,165,116,0.4)`, padding 40px, glow sutil
- **Selo de garantia:** ícone customizado champagne com "30" ou "90" grande
- **Headline da garantia:** Fraunces, 36px, peso 500
- **Passos:** numerados em Fraunces gigante (1, 2, 3 em rose-gold), com ícone customizado abaixo

### Referências cruzadas
- Garantia dupla: `03-modelo-comercial.md` § Garantia
- Processo de implementação: `03-modelo-comercial.md` § Prazo de implementação

### Critérios de sucesso
- ✅ Garantias parecem **incrivelmente generosas** (são)
- ✅ A leitora sente que **o risco é da Techla, não dela**
- ✅ Os 3 passos parecem simples (porque são)

---

## 🔷 SEÇÃO 8 — CTA FINAL + FAQ

### Função estratégica
- Capturar lead com formulário completo
- Responder a objeção residual
- Último ponto de conversão

### Copy direction

**Headline:**
> Sua clínica pode atender melhor *hoje*. Decida agora.

**Sub-headline:**
> Preencha abaixo. Em até 24h, a gente entra em contato pra agendar seu diagnóstico gratuito.

**Formulário completo (campos):**
- Nome (obrigatório)
- E-mail (obrigatório)
- WhatsApp da clínica (obrigatório)
- Nome da clínica (obrigatório)
- Faturamento aproximado (select: <30k / 30-50k / 50-100k / 100k+)
- Principal dor hoje (select: Perco lead / No-show alto / Secretária sobrecarregada / Base parada / Outro)

**Microcopy do botão:**
> "Quero meu diagnóstico gratuito"

**Compromisso:**
> Sem custo. Sem compromisso. Se a Techla não fizer sentido pra sua clínica, a gente fala isso na call.

**FAQ — 6 perguntas estratégicas:**

1. **Vai parecer robô?**
   Não. O agente é treinado com o vocabulário da sua clínica, fala em português natural e foi desenhado pra **acolher**. Você pode pedir uma demo na call e julgar.

2. **Funciona com o WhatsApp que eu já uso?**
   Sim. A gente conecta no número da sua clínica via WhatsApp Business API. Você não muda nada.

3. **E se eu quiser cancelar?**
   30 dias de aviso, sem multa. Os dados (conversas, base, métricas) são seus — exportamos em 7 dias.

4. **Quanto tempo demora pra ficar pronto?**
   14 dias úteis. Em 2 semanas sua operação está no ar.

5. **Atende clínica em qualquer lugar do Brasil?**
   Sim. Mas começamos com clínicas de Divinópolis e região. Pra quem está perto, dá pra fazer reunião presencial.

6. **Por que vocês são diferentes de outros chatbots?**
   Porque a gente **não vende chatbot.** A Techla é uma operação inteira pronta: agente + CRM + follow-up + reativação + relatórios. E somos especializados em estética — não generalistas.

### Visual direction

- **Layout:** form ocupando 60% à esquerda, FAQ accordion à direita 40%
- **Form:** fundo `#131316`, campos com border `1px solid rgba(245,244,240,0.08)`, focus state em `#D4A574`
- **Botão:** sólido `#D4A574` com texto `#0A0A0B`, padding generoso, largura 100% do form, hover glow
- **FAQ:** accordion clean, headline da pergunta em Fraunces 18px, body em Inter, divisor sutil

### Referências cruzadas
- Campos do form: `01-discovery.md` § Bloco D
- FAQ baseado em objeções de `02-posicionamento.md` § Quebras de Objeção

### Critérios de sucesso
- ✅ Form tem validação visual clara
- ✅ FAQ responde 100% das objeções esperadas (sem deixar dúvida)
- ✅ Última frase do FAQ #6 reforça a USP (especialização + operação completa)
- ✅ Post-submit: thank-you state com próximo passo claro

---

# 5. Sistema Visual

## 5.1 — Tokens de design

### Cores

```css
:root {
  /* Backgrounds */
  --bg-base: #0A0A0B;
  --bg-elevated: #131316;
  --bg-overlay: #1C1C21;

  /* Text */
  --text-primary: #F5F4F0;
  --text-secondary: #8B8B93;
  --text-muted: rgba(245, 244, 240, 0.5);

  /* Accents */
  --accent-primary: #D4A574;      /* rose-gold (CTA, highlights) */
  --accent-secondary: #F5B7B1;    /* rosé suave (mesh, glows) */
  --accent-success: #7DD3A8;      /* sage green (métricas positivas) */
  --accent-warning: #F5B7B1;      /* rosé (métricas de perda) */

  /* Borders */
  --border-subtle: rgba(245, 244, 240, 0.06);
  --border-default: rgba(245, 244, 240, 0.08);
  --border-strong: rgba(212, 165, 116, 0.18);
  --border-emphasis: rgba(212, 165, 116, 0.4);
}
```

### Tipografia

```css
:root {
  --font-display: 'Fraunces', Georgia, serif;
  --font-body: 'Inter', -apple-system, system-ui, sans-serif;

  /* Scale (fluid) */
  --text-xs: clamp(12px, 0.875rem, 14px);
  --text-sm: clamp(13px, 0.95rem, 15px);
  --text-base: clamp(15px, 1.05rem, 17px);
  --text-lg: clamp(18px, 1.25rem, 21px);
  --text-xl: clamp(22px, 1.5rem, 26px);
  --text-2xl: clamp(28px, 2rem, 36px);
  --text-3xl: clamp(36px, 2.75rem, 48px);
  --text-4xl: clamp(48px, 4vw, 64px);
  --text-5xl: clamp(56px, 8vw, 96px);   /* hero headline */
  --text-6xl: clamp(64px, 10vw, 120px); /* big numbers */
}
```

**Google Fonts import:**
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,wght@0,400;0,500;0,600;1,400;1,500&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
```

### Espaçamento

```css
:root {
  --space-1: 4px;
  --space-2: 8px;
  --space-3: 12px;
  --space-4: 16px;
  --space-6: 24px;
  --space-8: 32px;
  --space-12: 48px;
  --space-16: 64px;
  --space-24: 96px;
  --space-32: 128px;

  /* Section padding (vertical) */
  --section-padding-y: clamp(80px, 12vh, 160px);
}
```

### Border radius

```css
:root {
  --radius-sm: 4px;
  --radius-md: 8px;     /* botões, inputs */
  --radius-lg: 16px;    /* cards */
  --radius-xl: 24px;    /* hero mockup */
  --radius-pill: 999px; /* tags */
}
```

### Sombras

```css
:root {
  --shadow-sm: 0 1px 2px rgba(0,0,0,0.4);
  --shadow-md: 0 4px 24px rgba(0,0,0,0.5);
  --shadow-lg: 0 16px 64px rgba(0,0,0,0.6);
  --shadow-glow: 0 0 64px rgba(212,165,116,0.2);  /* CTA hover */
  --shadow-mockup: 0 32px 96px rgba(0,0,0,0.6), 0 0 120px rgba(212,165,116,0.08);
}
```

## 5.2 — Componentes-padrão

### Botão primário (CTA)
```css
.btn-primary {
  background: var(--accent-primary);
  color: var(--bg-base);
  font-family: var(--font-body);
  font-weight: 500;
  font-size: var(--text-base);
  padding: 14px 28px;
  border-radius: var(--radius-md);
  border: none;
  cursor: pointer;
  transition: all 200ms ease;
}
.btn-primary:hover {
  transform: translateY(-1px);
  box-shadow: var(--shadow-glow);
}
```

### Card padrão
```css
.card {
  background: var(--bg-elevated);
  border: 1px solid var(--border-default);
  border-radius: var(--radius-lg);
  padding: var(--space-8);
}
.card:hover {
  border-color: var(--border-strong);
  transform: translateY(-2px);
  transition: all 240ms ease;
}
```

### Headline com italic word
```html
<h1 class="headline">
  A IA que sua clínica precisa para nunca mais perder uma cliente
  <em class="headline-italic">enquanto você dorme</em>.
</h1>
```
```css
.headline {
  font-family: var(--font-display);
  font-size: var(--text-5xl);
  font-weight: 500;
  line-height: 1.05;
  letter-spacing: -0.02em;
  color: var(--text-primary);
}
.headline-italic {
  font-style: italic;
  font-weight: 400;
  color: var(--accent-primary);
}
```

## 5.3 — Motion / Animação

### Princípios
- Animações **só servem** se reforçam hierarquia (entrada de elementos chave)
- **Nunca animar por animar** — cada animação deve ter propósito narrativo
- Respeitar `prefers-reduced-motion: reduce` (animações desativam)
- GPU-only: `transform` e `opacity` (nada de `top/left/width/height`)

### Padrões aprovados
- **Fade-in scroll-driven** com `animation-timeline: view()` (CSS moderno)
- **Stagger** em listas/grids: 60-120ms entre elementos
- **Hero mesh:** loop infinito 30s com `transform: translate3d()`
- **Hover cards:** `translateY(-2px)` + border color shift, 240ms ease
- **Number counter** (calculadora): tween com `cubic-bezier(0.4, 0, 0.2, 1)`, 400ms

## 5.4 — Responsividade

### Breakpoints
```css
/* Mobile-first */
@media (min-width: 640px) { /* sm */ }
@media (min-width: 768px) { /* md */ }
@media (min-width: 1024px) { /* lg */ }
@media (min-width: 1280px) { /* xl */ }
```

### Regras críticas
- Hero: layout vira 1 coluna em <768px (headline + form em cima, mockup embaixo)
- Calculadora: sliders empilhados em mobile, card de resultado em sticky bottom
- Comparativo: tabela vira cards comparativos lado a lado (swipe horizontal)
- Bento grid: 3x2 → 2x3 → 1x6 conforme reduz
- Tipografia: sempre `clamp()` — nunca size fixo

---

# 6. Sistema de Copy

## 6.1 — Voz da Techla

### Faz
- ✅ Português direto, frases curtas
- ✅ Vocabulário do nicho (HOF, sessão, protocolo, anamnese, retorno, manutenção, recorrência)
- ✅ Números concretos (R$3.000, 25% no-show, 14 dias, 21x)
- ✅ Empatia com a rotina ("a gente sabe que você atende o dia inteiro")
- ✅ Confiança sem arrogância ("a gente faz isso e funciona")
- ✅ Palavra **"acolhimento"** sempre que falar de qualidade de atendimento

### Não faz
- ❌ Jargão de tech ("API", "webhook", "LLM", "machine learning")
- ❌ Palavra "inteligência artificial" repetida (usar "IA" ou "agente" ou "assistente")
- ❌ Promessas vazias ("revolucione seu negócio", "transforme sua clínica")
- ❌ Tom de palestrante de evento ("mindset", "sucesso é...", "vamos juntos")
- ❌ Anglicismo desnecessário ("engagement", "performance", "lead gen", "ROI" — esse último, usar "retorno")
- ❌ Promessa de "100% de conversão" / exageros não-substanciados

## 6.2 — Vocabulário sagrado do nicho

**Usar com frequência:**
- agenda, lead, WhatsApp, clínica, secretária, fechamento
- no-show, base, reativação, atender, qualificar, agendar
- protocolo, sessão, pacote, retorno, manutenção, recorrência
- anamnese, avaliação, ficha, procedimento
- **acolhimento** (palavra mais sagrada)
- **investimento** (em vez de "preço" ou "custo")

**Evitar:**
- plataforma, solução, transformação digital
- jornada do cliente, funil de conversão (usar "agenda", "fechamento")
- pricing, fee, subscription (usar "investimento", "mensalidade")

## 6.3 — Padrões de copy aprovados

### Padrão "Editorial Italic"
> *"O atendimento que sua clínica **merece**."*

Estrutura: frase comum + UMA palavra final em italic carregando o peso emocional.

### Padrão "Contraste matemático"
> *"R$ 2.400 de secretária CLT. R$ 897 de Techla. A conta não fecha pro outro lado."*

### Padrão "Citação + Estatística"
> *"Falta dói no caixa e na agenda."* — Valentins Digital, 2024
> 1 em cada 3 clínicas perde mais de 10% das consultas marcadas. Panorama 2026.

### Padrão "Antecipação narrativa"
> *"60 dias depois, sua clínica é outra."*

### Padrão "Inversão de objeção"
> *"IA fria não. Atendimento que acolhe — só que às 23h47 de um sábado."*

## 6.4 — Banco de frases-âncora (para reaproveitar)

- *"Sua clínica não para às 18h. Por que sua secretária pararia?"*
- *"O lead que entra à noite é o que sua concorrência já fechou."*
- *"Crescer sem contratar é matemática nova — e ela só existe com IA."*
- *"A gente não vende chatbot. A gente monta sua operação comercial."*
- *"Em 14 dias sua clínica atende sozinha. Em 30 dias, ou funciona ou devolvemos."*
- *"R$ 10.000 por mês evaporando em no-show. A gente fecha esse ralo."*
- *"Sua base de WhatsApp não está morta. Só está esperando a mensagem certa."*
- *"Sua agenda parece cheia. Seu caixa não fecha. A diferença tem nome: horário fantasma."*

---

# 7. Arquitetura de Conversão

## 7.1 — CTA Strategy

### CTA Primário (5 instâncias na página)
- **Texto:** "Quero meu diagnóstico" / "Aplique para diagnóstico gratuito" (varia por contexto)
- **Aparição:** hero (form inline), pós-calculadora, pós-comparativo, pós-antecipação, footer (form completo)
- **Visual:** botão sólido `#D4A574`

### CTA Secundário (1 instância)
- **Texto:** "Falar direto no WhatsApp"
- **Aparição:** rodapé, como fallback pra quem não topa preencher form
- **Visual:** link com ícone WhatsApp, sem botão

## 7.2 — Formulário

### Hero (mínima fricção)
1 campo visível: **WhatsApp da clínica**
Botão: "Quero meu diagnóstico"

Pós-submit do hero: modal/redirect pro form completo.

### Final (qualificação completa)
- Nome*
- E-mail*
- WhatsApp da clínica*
- Nome da clínica*
- Faturamento (select: <30k / 30-50k / 50-100k / 100k+)
- Principal dor hoje (select: 5 opções)

### Validação
- Campos obrigatórios marcados com *
- WhatsApp validado por máscara (DDD + 9 dígitos)
- E-mail validado por regex
- Erro inline em vermelho rosé `#F5B7B1`

### Pós-submit
- Thank-you page (ou inline) com:
  > "Recebemos sua aplicação. Em até 24h, a gente entra em contato pelo WhatsApp pra agendar seu diagnóstico. Enquanto isso, você pode dar uma olhada nesse vídeo de 3min explicando como a operação funciona."

## 7.3 — Mapeamento de Objeções → Resposta

| Objeção | Onde a página responde |
|---------|------------------------|
| "Vai parecer robô" | Solução § Card 1 + FAQ #1 + palavra "acolhimento" repetida |
| "Não vai entender da minha área" | Discovery especializado + vocabulário do nicho na copy inteira |
| "Vou ficar dependente de vocês" | FAQ #3 + cláusulas de "dados são seus" |
| "É caro pra começar" | Calculadora ROI + Comparativo + Garantia dupla |
| "Tecnologia dá problema" | Garantia + "Suporte semanal nos primeiros 90 dias" + presença regional |
| "Não tenho tempo de implementar" | "14 dias úteis, a gente faz tudo" + 3 passos visualmente simples |

---

# 8. Mapa Informacional (onde achar cada insumo)

> Se você precisa de qualquer informação para construir a página, **comece por este mapa**.

## 8.1 — Por tipo de informação

| Precisa de... | Vá para... |
|---------------|------------|
| Promessa central, headlines, tom | `docs/01-estrategia/02-posicionamento.md` |
| ICP detalhado, dores, sub-nichos | `docs/01-estrategia/01-tres-ps.md` |
| Pricing, garantias, ROI matemático | `docs/01-estrategia/03-modelo-comercial.md` |
| Concorrentes, vocabulário, citações | `docs/02-operacao-comercial/01-pagina-aplicacao/02-research.md` |
| Estatísticas com fontes auditadas | `02-research.md` § Dados de Mercado |
| Decisões da página (CTA, profundidade, tom) | `docs/02-operacao-comercial/01-pagina-aplicacao/01-discovery.md` |
| Playbook GrowthOS (funil de 5 etapas) | `docs/01-estrategia/00-playbook-referencia.md` |

## 8.2 — Por seção da página

| Seção | Insumos principais |
|-------|---------------------|
| Hero | `02-posicionamento.md` (headlines) + `01-discovery.md` (CTA) + `02-research.md` (visual refs) |
| Agitação | `02-research.md` (estatísticas + citações) + `01-tres-ps.md` (dores) |
| Calculadora ROI | `03-modelo-comercial.md` (matemática do cenário-base) |
| Solução | `03-modelo-comercial.md` (lista de componentes) + `02-posicionamento.md` (mecanismos únicos) |
| Comparativo | `03-modelo-comercial.md` (tabela Techla vs Secretária) + `02-research.md` (salário CLT) |
| Antecipação | `00-playbook-referencia.md` (etapa Antecipação do funil) |
| Garantia | `03-modelo-comercial.md` (garantia dupla) |
| FAQ | `02-posicionamento.md` (quebras de objeção) |

## 8.3 — Por elemento visual

| Elemento | Referência |
|----------|------------|
| Paleta + tokens | Seção 5.1 deste documento |
| Tipografia | Seção 5.1 deste documento + `02-research.md` § Referências Visuais |
| Hero pattern (mesh + form inline + mockup) | `02-research.md` § Referências Visuais (Stripe + Cal + Attio) |
| Bento grid | `02-research.md` § Vercel pattern |
| Comparison table | `02-research.md` § Attio pattern |
| Calculadora interativa | `02-research.md` § BeautyBot inspiration |

---

# 9. Métricas de Sucesso

## 9.1 — Métricas da página (técnicas)

- **LCP (Largest Contentful Paint):** < 2.5s
- **CLS (Cumulative Layout Shift):** < 0.1
- **Lighthouse Performance:** ≥ 90
- **Lighthouse Accessibility:** ≥ 90
- **Tamanho total:** < 200KB (HTML + CSS + JS inline + fontes)
- **Mobile-friendly:** 100% no PageSpeed

## 9.2 — Métricas de conversão (de negócio)

- **Taxa de conversão alvo (lead → form):** 4-8% (tráfego pago direcionado)
- **Custo por lead (CPL) alvo:** R$ 30-60 (Meta Ads)
- **Taxa de qualificação (form → call agendada):** ≥ 50%
- **Taxa de fechamento (call → cliente):** ≥ 25%
- **Resultado esperado:** 8-12 clientes fechados nos primeiros 3 meses (com investimento de tráfego de R$ 3k-5k/mês)

## 9.3 — Métricas qualitativas (a observar)

- A página passa o "teste dos 5 segundos" (leitora entende a oferta em <5s)?
- O comparativo Techla vs Secretária é o ponto onde a leitora "se ganha"?
- A calculadora ROI gera screenshot / compartilhamento orgânico?
- O FAQ #1 ("vai parecer robô?") é suficiente pra desarmar a objeção principal?

---

# 10. Anti-Padrões (o que NUNCA fazer)

## 10.1 — Visuais proibidos

- ❌ Gradient roxo/azul tipo Stripe sem adaptação (vira "mais um SaaS")
- ❌ Stock photos de "equipe sorrindo no escritório"
- ❌ Ícones 3D coloridos genéricos (Lordicon, Iconscout default)
- ❌ Hero com vídeo full-screen autoplay (carrega lento, não converte)
- ❌ Bordas arredondadas demais (border-radius > 24px em cards)
- ❌ Animações decorativas (parallax sem propósito, scroll-jacking)
- ❌ Múltiplos accent colors competindo (UM accent: rose-gold. Acabou.)
- ❌ Tipografia em mais de 2 famílias (Fraunces + Inter. Fim.)

## 10.2 — Copy proibida

- ❌ "Transforme sua clínica" / "Revolucione seu atendimento"
- ❌ "Solução inteligente de IA"
- ❌ "Aumente em 300% sua conversão" (números sem fonte)
- ❌ "A melhor IA do Brasil" (superlativos vazios)
- ❌ "Não perca essa oportunidade" (urgência fake)
- ❌ "Trabalhamos com tecnologia de ponta"
- ❌ "Empresa séria e comprometida"

## 10.3 — Padrões de UX proibidos

- ❌ Exit-intent popup com desconto (queima a percepção premium)
- ❌ Chat widget bloqueando conteúdo no mobile
- ❌ Cookie banner gigante (LGPD bem feita: 1 linha de aviso, link "saiba mais")
- ❌ Múltiplos pixels de tracking visíveis no console (FB Pixel + GA + Hotjar todos juntos)
- ❌ Form com mais de 6 campos obrigatórios
- ❌ Botão CTA com texto genérico ("Saiba mais", "Clique aqui", "Submit")

## 10.4 — Frases-tipo proibidas

| Não escrever | Escrever |
|--------------|----------|
| "Solução de IA para clínicas" | "Operação comercial com IA pra clínica de estética" |
| "Aumente sua conversão" | "Recupere R$ 30 mil/mês em no-show" |
| "Atendimento 24/7" | "Atende às 23h47 de sábado, sem reclamar" |
| "Plataforma intuitiva" | "Funciona no WhatsApp que você já usa" |
| "Empresa especializada" | "A gente só atende clínica de estética. Nada mais." |

---

# 🎯 CHECKLIST DE APROVAÇÃO (para Rafael ler antes de avançar)

Antes de partir pra Fase 4 (Visual Design final) e Fase 5 (Narrative + Copy), confirme:

- [ ] A Grande Promessa do hero faz sentido? (*"A IA que sua clínica precisa para nunca mais perder uma cliente enquanto você dorme."*)
- [ ] O framework PAS + Antecipação é o caminho certo (vs AIDA ou Story Bridge)?
- [ ] A paleta champagne + rose-gold sobre `#0A0A0B` está aprovada?
- [ ] A tipografia Fraunces + Inter está aprovada? (ou prefere alternativa B/C de `02-research.md`?)
- [ ] As 8 seções na ordem proposta fazem sentido?
- [ ] A calculadora de ROI deve ser interativa (JS) ou estática (números fixos baseados em cenário-padrão)?
- [ ] O comparativo Techla vs Secretária CLT é a abordagem que você quer manter?
- [ ] A garantia dupla (30 dias money-back + 90 dias performance) será publicada?
- [ ] O formulário com 6 campos no final está OK, ou prefere reduzir/expandir?
- [ ] Domínio decidido? (sugestões: `techla.com.br`, `techla.ai`, `agendadahora.com.br`)

---

# Estado do Pipeline pós-Fase 3

```json
{
  "phase_completed": ["1-discovery", "2-research", "3-briefing"],
  "phase_current": 3,
  "ready_for": ["4-visual-design", "5-narrative-copy"],
  "blocking_questions": [
    "Aprovação do briefing pelo Rafael",
    "Decisão final sobre domínio"
  ]
}
```

---

# Próximas fases

- **Fase 4 — Visual Design:** sistema visual final (mockup do hero, paleta aplicada, componentes em isolamento)
- **Fase 5 — Narrativa & Copy:** TODA a copy escrita, seção a seção, pronta pra colar no código
- **Fase 6 — Fusion:** mockup HTML estático com copy + visual aplicados
- **Fase 7 — Build:** página HTML/CSS/JS final, otimizada
- **Fase 8 — QA:** testes responsivos, performance, accessibilidade
