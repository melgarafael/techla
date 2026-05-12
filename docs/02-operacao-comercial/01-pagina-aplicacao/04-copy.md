# Fase 5 — Narrativa & Copy completa

> Toda a copy das 8 seções da página, pronta para colar no código.
> Versão: 1.0 — 2026-05-12
> Framework: **PAS + Antecipação Schwartz**
> Tom: empresarial-editorial brasileiro, sem anglicismo, sem jargão tech, com vocabulário do nicho

---

## Como usar este documento

- Cada seção tem **3 blocos**: copy aprovada, variações testáveis (A/B), e notas de execução
- Toda copy aqui já passou pelo filtro de anti-padrões (sem "transforme", "revolucione", "solução inteligente")
- Palavras destacadas com `*itálico*` vão em **Fraunces italic rose-gold** no código
- Citações entre `""` vão em **Fraunces italic** menor, com fonte abaixo

---

# 📍 SEÇÃO 1 — HERO

## Eyebrow (badge acima da headline)

```
Para clínicas de estética com 2-3 funcionários
```

**Variação:** `Especialista em clínicas de estética · Divinópolis/MG`

## Headline (Fraunces, italic na última palavra)

```
A IA que sua clínica precisa para nunca mais perder uma cliente *enquanto você dorme*.
```

### Variações para A/B

**V2 — Foco temporal/operacional:**
```
A IA que atende sua clínica enquanto você *dorme*, qualifica enquanto você *atende*, e agenda enquanto você *fecha o caixa*.
```

**V3 — Foco anti-crescimento contratado (dor #5):**
```
Sua clínica faturando 50% a mais — sem contratar *mais uma secretária*.
```

**V4 — Foco MIT/21x (dado científico):**
```
Responder em 5 minutos te dá *21x mais chance* de fechar venda. Sua clínica responde em 5 minutos?
```

## Sub-headline (Inter, 1 linha)

```
Agente SDR no WhatsApp 24/7, CRM, recuperação de no-show e reativação de base — entregues prontos em 14 dias. Garantia de 30 dias money-back.
```

## Formulário inline

**Placeholder:** `WhatsApp da clínica (com DDD)`
**Botão:** `Quero meu diagnóstico →`
**Hint abaixo:** `Sem custo. Sem compromisso. Apenas se fizer sentido pra sua clínica.`

## Trust badges (3 itens com ✓)

```
✓ 14 dias para go-live
✓ 30 dias money-back
✓ Atende em pt-BR natural
```

## Notas de execução

- A headline V1 é a aprovada — V2-V4 ficam de bolso pra teste depois do go-live
- Eyebrow muda dinamicamente: versão `Divinópolis/MG` quando rodar tráfego pago regional, versão genérica para tráfego nacional
- Mockup do WhatsApp ao lado da headline: conversa de uma "Camila" perguntando sobre HOF (harmonização orofacial) às 23:47 — prova visual da promessa do "enquanto você dorme"

---

# 📍 SEÇÃO 2 — AGITAÇÃO (O Ralo Invisível)

## Eyebrow

```
O ralo invisível
```

## Headline (Fraunces, italic na última palavra)

```
Todo dia, sua clínica perde dinheiro *invisível*.
```

## Sub-headline (Inter)

```
Não é sobre vender mais. É sobre parar de perder o que já é seu.
```

## 3 blocos de perda (em ordem)

### Bloco 1 — Lead que vaza

**Número grande (rosé):** `R$ 8.000`

**Caption:** `por mês somem em leads que chegam às 22h e nunca são respondidos.`

**Citação:**
> *"Se a clínica leva horas para responder, o paciente esfria."*
> — Valentins Digital, 2024

### Bloco 2 — No-show

**Número grande (rosé):** `R$ 12.000`

**Caption:** `evaporam em no-show. *Falta dói no caixa e na agenda.*`

**Citação:**
> 1 em cada 3 clínicas brasileiras perde mais de 10% das consultas marcadas.
> — Panorama Clínicas 2026 · n=639

### Bloco 3 — Base inativa

**Número grande (rosé):** `R$ 6.000`

**Caption:** `estão parados na sua base de WhatsApp inativa.`

**Citação:**
> *Cliente que sumiu não é destino — é retorno que ninguém marcou.*
> — Vocabulário do nicho, adaptado

## Bloco-âncora MIT (destaque maior)

**Número gigante (champagne):** `21×`

**Texto principal (Fraunces, italic na frase-chave):**
```
Responder um lead em 5 minutos te dá *21x mais chance* de fechar venda do que responder em 30.
```

**Fonte:**
```
MIT Lead Response Study · Harvard Business Review
```

## Notas de execução

- Os 3 R$ somam R$ 26.000/mês — número que já bate o "R$ 897 da Techla" mentalmente. Não precisa dizer, a leitora calcula
- A frase "Falta dói no caixa e na agenda" é citação literal do Valentins Digital — vocabulário 100% do nicho
- O bloco MIT 21x é o **bloco-âncora epistemológico** da página inteira. Tudo se ordena ao redor dele

---

# 📍 SEÇÃO 3 — CALCULADORA DE ROI

## Eyebrow

```
A conta
```

## Headline (Fraunces, italic na palavra-chave)

```
Faça a conta. Quanto sua clínica perde *agora*?
```

## Sub-headline (Inter)

```
Use os sliders abaixo com os números reais da sua clínica. O cálculo é conservador.
```

## Labels dos sliders

| Slider | Label | Default | Range |
|--------|-------|---------|-------|
| 1 | Leads por mês | 150 | 50–500 (step 10) |
| 2 | Ticket médio | R$ 1.200 | R$ 300–3.000 (step 50) |
| 3 | No-show atual | 25% | 10–40% (step 1) |
| 4 | Base inativa | 1.500 | 200–3.000 (step 50) |

## Card de Output (lado direito)

**Label superior:**
```
Sua clínica perde, por mês:
```

**Número de perda (Fraunces gigante, rosé):**
```
R$ XX.XXX  ← calculado em tempo real
```

**Label inferior:**
```
Recuperando 30% com Techla:
```

**Número de ganho (Fraunces, sage green):**
```
+R$ YY.YYY / mês
```

**Fineprint (mono pequeno):**
```
Cenário conservador. Cálculo já desconta a mensalidade de R$ 897.
```

## CTA in-section

**Texto do botão:** `Quero parar de perder esse dinheiro →`

## Frase de transição (após calculadora, antes da próxima seção)

```
Você acabou de calcular o tamanho do ralo. Agora vamos mostrar como fechá-lo.
```

## Notas de execução

- Fórmula do cálculo (4 ralos somados):
  - Leads perdidos: `30% × leads × 15% × ticket`
  - Conversão extra (qualificação): `(leads × 70%) × 15% × ticket`
  - No-show evitável: `(leads × 30%) × (noshow/2) × ticket`
  - Reativação trimestral: `(base × 3% × ticket) / 3`
- Output animado: tween com cubic-bezier, 400ms
- Acessibilidade: sliders com `aria-valuetext` formatado em pt-BR

---

# 📍 SEÇÃO 4 — SOLUÇÃO (Operação Completa)

## Eyebrow

```
A operação
```

## Headline (Fraunces, italic na última palavra)

```
Não é chatbot. É *operação*.
```

## Sub-headline (Inter)

```
A Techla monta toda a estrutura comercial da sua clínica com IA. Em 14 dias.
```

## Bento grid — 6 cards

### Card 1 — Agente SDR

**Ícone:** chat bubble
**Título:** `Agente SDR no WhatsApp 24/7`
**Body:**
```
Atende, qualifica e agenda em português natural — treinado com o vocabulário da sua clínica. Não parece robô: acolhe.
```

### Card 2 — Agendamento

**Ícone:** calendário
**Título:** `Agendamento integrado`
**Body:**
```
A agenda fecha sozinha. Lembrete automático 24h antes e 2h antes — no-show despenca.
```

### Card 3 — CRM

**Ícone:** kanban
**Título:** `CRM com pipeline visual`
**Body:**
```
Cada lead no funil: novo → qualificado → agendado → fechado. Sem planilha, sem WhatsApp Business bagunçado.
```

### Card 4 — Follow-up

**Ícone:** loop/refresh
**Título:** `Follow-up que não esquece`
**Body:**
```
Lead que não fechou recebe sequência de 3 a 5 toques em horários estratégicos. A IA não esquece.
```

### Card 5 — Reativação

**Ícone:** envelope
**Título:** `Reativação de base inativa`
**Body:**
```
Sua base de 1.500 contatas adormecidas vira receita. Campanha mensal com mensagem personalizada por perfil.
```

### Card 6 — Relatório

**Ícone:** gráfico de barras
**Título:** `Relatório semanal`
**Body:**
```
Leads atendidos, taxa de qualificação, agendamentos, no-show recuperado. Toda segunda no seu WhatsApp.
```

## CTA in-section

**Texto:** `Ver como tudo isso funciona junto →`

## Notas de execução

- Todos os ícones em outline (não preenchido), `1.5` stroke, cor `#D4A574`
- Hover dos cards: sobe `translateY(-4px)` + revela mesh radial sutil + border vira rose-gold
- Ordem dos cards é importante: começa pelo agente (impacto), termina pelo relatório (confiança/controle)

---

# 📍 SEÇÃO 5 — COMPARATIVO TECHLA vs SECRETÁRIA

## Eyebrow

```
A matemática
```

## Headline (Fraunces, italic na palavra-chave)

```
Pelo preço de *meia secretária*, sua clínica ganha uma operação inteira.
```

## Sub-headline

```
Comparado a contratar mais uma secretária CLT no interior de MG.
```

## Tabela completa (9 linhas)

| Critério | Secretária Adicional CLT | Techla (Plano Completo) |
|----------|--------------------------|--------------------------|
| **Custo mensal real** | R$ 2.400 – R$ 2.800 | **R$ 897** |
| **Horário de trabalho** | 8h/dia, segunda a sexta | **24/7, todos os dias** |
| **Tempo de resposta** | Minutos a horas | **Segundos** |
| **Pronta para operar em** | 30 a 90 dias | **14 dias** |
| **Férias, faltas e atestados** | Custo extra ou clínica para | **Não existe** |
| **Esquece follow-up** | ✗ Acontece toda semana | ✓ **Não esquece** |
| **Custos no desligamento** | Aviso, multa FGTS, rescisão | **Cancelamento direto** |
| **Dobrar volume sem custo** | ✗ Contratar mais uma | ✓ **Sem custo adicional** |
| **Reativa base inativa** | ✗ Não tem tempo | ✓ **Automaticamente** |

## Frase de fechamento da seção (antes do CTA)

```
A conta não fecha pro outro lado.
```

## CTA in-section

**Texto:** `Faz mais sentido contratar a Techla →`

## Notas de execução

- Coluna "Secretária CLT" em opacity 0.65 (visualmente "rebaixada")
- Coluna "Techla" com fundo `rgba(212, 165, 116, 0.03)` (sutilíssimo) e texto em `#F5F4F0`
- Header da coluna Techla com cor `#D4A574`
- Linhas com border-bottom `rgba(245, 244, 240, 0.06)`
- Mobile: vira 2 cards comparativos lado a lado com swipe horizontal

---

# 📍 SEÇÃO 6 — ANTECIPAÇÃO (Future Pacing)

## Eyebrow

```
60 dias depois
```

## Headline (Fraunces, italic na última palavra)

```
60 dias depois, sua clínica é *outra*.
```

## Sub-headline

```
Não na receita. Na sensação. (Na receita também — mas a sensação muda primeiro.)
```

## Timeline com 3 marcos

### 📍 Dia 14 — Go-live

**Título do marco:** `Dia 14 — Go-live`

**Body:**
```
O agente entra no ar. Você dorme tranquila pela primeira vez em meses.

O lead que chegou às 23h47 já foi atendido, qualificado e tem horário pra terça-feira. Sua secretária acordou e encontrou a agenda da semana fechada.
```

### 📍 Dia 30 — Primeiro Relatório

**Título do marco:** `Dia 30 — Primeiro relatório`

**Body:**
```
87 leads atendidos. 41 qualificados. 18 agendadas. 3 no-shows evitados.

Sua secretária está focada no que importa: receber bem quem chega. Você ganhou tempo de volta — tempo de atender com calma, tempo de planejar, tempo de respirar.
```

### 📍 Dia 60 — Sua Clínica é Outra

**Título do marco:** `Dia 60 — Sua clínica é outra`

**Body:**
```
Você fatura 30 a 40% mais sem ter contratado ninguém. Sua base inativa virou receita. Sua agenda fecha sozinha.

E pela primeira vez em anos, você está pensando em abrir a *segunda unidade* — porque agora cresceu sem dor de gestão.
```

## Frase de fechamento (centralizada, Fraunces italic)

```
Essa é a clínica que a Techla constrói.
Em 60 dias.
```

## Notas de execução

- Timeline vertical à esquerda, conteúdo dos marcos à direita
- Linha vertical `1px solid rgba(212, 165, 116, 0.3)` com pontos `#D4A574` em cada marco
- Animação ao scroll: ponto da timeline ativa com glow quando entra no viewport, linha "desenha" entre os pontos
- A palavra "*segunda unidade*" em italic rose-gold é o gancho ambicioso mais forte

---

# 📍 SEÇÃO 7 — GARANTIA + COMO COMEÇAR

## Eyebrow

```
Sem risco
```

## Headline (Fraunces, italic na palavra-chave)

```
Se não funcionar, *você não paga*.
```

## Sub-headline

```
Duas garantias. Porque a gente tem certeza que funciona.
```

## Garantia 1 — Card grande

**Selo (Fraunces gigante):** `30`
**Sub-selo:** `dias`

**Título do card:**
```
30 dias ou seu dinheiro de volta.
```

**Body:**
```
Implementamos sua operação completa em 14 dias. Você tem 30 dias corridos a partir do go-live para testar.

Se não estiver satisfeita, devolvemos 100% — setup e mensalidade.
```

## Garantia 2 — Card grande

**Selo (Fraunces gigante):** `90`
**Sub-selo:** `dias`

**Título do card:**
```
90 dias ou 2 meses grátis.
```

**Body:**
```
Se em 90 dias a operação não recuperar pelo menos 3x o valor da mensalidade em receita atribuível (no-show evitado + leads convertidos), você ganha 2 meses adicionais grátis.

Medido pelo CRM da própria operação. Métrica transparente, auditável.
```

## Subseção — Como começar (3 passos)

### Passo 1
**Número (Fraunces gigante):** `01`
**Título:** `Aplicação`
**Body:**
```
Você preenche o formulário. A gente agenda uma call de diagnóstico de 30 minutos — gratuita, sem compromisso. Se a Techla não fizer sentido pra sua clínica, a gente fala isso na call.
```

### Passo 2
**Número:** `02`
**Título:** `Setup em 14 dias`
**Body:**
```
A gente faz tudo: agente treinado com o vocabulário da sua clínica, CRM configurado, WhatsApp Business conectado, integrações testadas. Você só precisa aprovar.
```

### Passo 3
**Número:** `03`
**Título:** `Go-live + acompanhamento`
**Body:**
```
A operação entra no ar. Revisão semanal nos primeiros 90 dias. Suporte direto pelo WhatsApp — sem fila, sem ticket, sem URA.
```

## Notas de execução

- 2 cards de garantia lado a lado, glow rose-gold sutil
- 3 passos numerados em timeline horizontal (mobile vira vertical)
- Selos "30" e "90" são gigantes em Fraunces — pesam visualmente como prova

---

# 📍 SEÇÃO 8 — CTA FINAL + FAQ

## Eyebrow

```
Próximo passo
```

## Headline (Fraunces, italic na última palavra)

```
Sua clínica pode atender melhor *hoje*. Decida agora.
```

## Sub-headline

```
Preencha abaixo. Em até 24h, a gente entra em contato pelo WhatsApp para agendar seu diagnóstico gratuito.
```

## Formulário completo (6 campos)

| Campo | Label | Tipo | Obrigatório |
|-------|-------|------|-------------|
| 1 | Nome | text | ✓ |
| 2 | E-mail | email | ✓ |
| 3 | WhatsApp da clínica | tel | ✓ |
| 4 | Nome da clínica | text | ✓ |
| 5 | Faturamento aproximado | select | ✓ |
| 6 | Principal dor hoje | select | ✓ |

**Placeholders:**
- Nome: `Seu nome completo`
- E-mail: `voce@suaclinica.com.br`
- WhatsApp: `(37) 9 9999-9999`
- Clínica: `Nome da sua clínica`

**Opções de faturamento:**
- Até R$ 30 mil/mês
- R$ 30 a 50 mil/mês
- R$ 50 a 100 mil/mês
- Acima de R$ 100 mil/mês

**Opções de principal dor:**
- Perco lead à noite e fim de semana
- Tenho muito no-show
- Secretária sobrecarregada, não vende
- Base de WhatsApp parada
- Não consigo crescer sem contratar mais
- Outra

**Botão:** `Quero meu diagnóstico gratuito →`

**Compromisso (abaixo do botão):**
```
Sem custo. Sem compromisso. Se a Techla não fizer sentido pra sua clínica, a gente fala isso na call.
```

## FAQ — 6 perguntas estratégicas

### Q1 — Objeção "vai parecer robô"
**Pergunta:** `Vai parecer robô?`
**Resposta:**
```
Não. O agente é treinado com o vocabulário e o tom da sua clínica, fala em português natural e foi desenhado para acolher — não para "responder rápido". Na call de diagnóstico você vê uma demo real e julga você mesma.
```

### Q2 — Objeção "não funciona com meu WhatsApp"
**Pergunta:** `Funciona com o WhatsApp que eu já uso?`
**Resposta:**
```
Sim. A gente conecta no número que sua clínica já tem via WhatsApp Business API oficial. Você não muda nada — a cliente continua mandando mensagem pro mesmo número.
```

### Q3 — Objeção "vou ficar dependente / e se eu quiser sair?"
**Pergunta:** `E se eu quiser cancelar?`
**Resposta:**
```
30 dias de aviso, sem multa. Os dados — conversas, base de clientes, métricas — são seus. Exportamos tudo em 7 dias. Sem lock-in.
```

### Q4 — Objeção "vai demorar muito"
**Pergunta:** `Quanto tempo demora pra ficar pronto?`
**Resposta:**
```
14 dias úteis. Em duas semanas sua operação está no ar. A gente faz a parte técnica inteira — você só aprova o tom do agente e as regras.
```

### Q5 — Curiosidade "atendem em qualquer lugar?"
**Pergunta:** `Atendem clínica em qualquer lugar do Brasil?`
**Resposta:**
```
Sim. Mas começamos com clínicas de Divinópolis e região — para quem está perto, dá pra fazer reunião presencial e o suporte é ainda mais próximo. Fora daqui, atendemos 100% remoto pelo WhatsApp.
```

### Q6 — USP de fechamento
**Pergunta:** `Por que vocês são diferentes de outros chatbots?`
**Resposta:**
```
Porque a gente não vende chatbot.

A Techla é uma operação inteira pronta: agente + CRM + follow-up + reativação + relatórios. E somos especializados em clínica de estética — não generalistas que atendem qualquer negócio.

Você compra resultado, não ferramenta.
```

## Pós-submit (thank-you state)

**Título (Fraunces, italic):**
```
Recebemos *sua aplicação*.
```

**Body:**
```
Em até 24h, a gente entra em contato pelo WhatsApp pra agendar seu diagnóstico — 30 minutos, gratuitos, sem compromisso.

Enquanto isso, dá uma olhada nesse vídeo de 3 minutos explicando como uma operação Techla funciona na prática.
```

**CTA secundário (link):** `Voltar à página inicial`

## Notas de execução

- Form do hero (1 campo) leva pra essa seção via scroll ou modal pré-preenchido
- FAQ em accordion clean — pergunta em Fraunces 18px, resposta em Inter 15px
- Cada pergunta abre/fecha com animação 240ms
- Validação inline: campos obrigatórios com asterisco rose-gold

---

# 🎯 Banco de Frases-âncora (uso transversal)

Frases que podem aparecer **em qualquer seção** como peso emocional adicional ou frase de transição:

1. *Sua clínica não para às 18h. Por que sua secretária pararia?*
2. *O lead que entra à noite é o que sua concorrência já fechou.*
3. *Crescer sem contratar é matemática nova — e ela só existe com IA.*
4. *A gente não vende chatbot. A gente monta sua operação comercial.*
5. *Em 14 dias sua clínica atende sozinha. Em 30 dias, ou funciona ou devolvemos.*
6. *R$ 10.000 por mês evaporando em no-show. A gente fecha esse ralo.*
7. *Sua base de WhatsApp não está morta. Só está esperando a mensagem certa.*
8. *Sua agenda parece cheia. Seu caixa não fecha. A diferença tem nome: horário fantasma.*

---

# 🚫 Checklist de Validação Final da Copy

Antes de colar no código, conferir:

- [ ] Nenhuma palavra "transforme", "revolucione", "solução inteligente"
- [ ] Nenhum "ROI" — usar "retorno" ou número específico
- [ ] Nenhum "IA" mais que 2x por seção
- [ ] Palavra "acolhimento" aparece pelo menos 1x (objeção robô)
- [ ] Palavra "investimento" usada no lugar de "preço/custo"
- [ ] Vocabulário do nicho presente (HOF, protocolo, anamnese, retorno)
- [ ] Estatística MIT/21x aparece com fonte completa
- [ ] Garantia dupla aparece com termos exatos
- [ ] Cada seção termina com uma frase-gancho pra próxima
- [ ] Citações de blogs sempre com nome do veículo + ano
- [ ] Nenhuma promessa sem fonte ou sem garantia (ex: "+300%" sem números reais)

---

# Estado do pipeline pós-Fase 5

```json
{
  "phase_completed": ["1-discovery", "2-research", "3-briefing", "4-visual-design", "5-narrative-copy"],
  "phase_current": 5,
  "ready_for": ["6-fusion", "7-build"],
  "approvals_pending": [
    "Rafael revisar a copy seção por seção",
    "Definir domínio final (techla.com.br vs alternativas)",
    "Confirmar campos finais do formulário"
  ]
}
```

---

# Próximas fases

- **Fase 6 — Fusion:** mockup HTML completo com TODA a copy + visual aplicados. Versão estática, sem JS de conversão ainda — só visual + texto + animações
- **Fase 7 — Build:** produção da página final otimizada (performance, SEO, acessibilidade, métricas)
- **Fase 8 — QA:** testes responsivos, lighthouse, regressão visual
