# Playbook de Referência — Operação Comercial com IA

> Material-base fornecido pelo Rafael na sessão de fundação (2026-05-12).
> Origem: GrowthOS / TomikOS.
> Este documento serve como **mapa do território** — é o roteiro completo que vamos seguir e adaptar para o contexto da Techla.

---

## Visão Geral

Uma **Operação Comercial com IA** é um funil completo onde a inteligência artificial assume o papel de SDR (Sales Development Representative), qualificando e agendando leads automaticamente, enquanto humanos focam nas etapas de alto valor (fechamento e entrega).

---

## Estrutura de uma Operação Comercial

Componentes essenciais:

- **Canais de presença:** Instagram / YouTube / LinkedIn (não precisa de milhares de seguidores)
- **Produção de conteúdo e anúncios** — geração de demanda
- **Página de aplicação** — captura e qualificação inicial
- **Sistema operacional de vendas com IA:**
  - Integração: página de aplicação → sistema operacional
  - WhatsApp conectado ao sistema
  - Agente de IA SDR (qualificador e agendador de calls)
  - Sistema de follow-up + CRM (sequência de atendimento + gestão de contatos)

---

## As 5 etapas do funil (e o que cada uma desperta)

| Etapa | Ativo | Despertar emocional |
|-------|-------|---------------------|
| **1. Interesse / Curiosidade** | Anúncio, conteúdo, marketing | "Hmm, isso pode ser pra mim" |
| **2. Esclarecimento** | Landing page + IA SDR | "Entendi o que é e como funciona" |
| **3. Antecipação → Desejo** | IA SDR | "Eu quero ter isso" |
| **4. Confiança → CTA** | Call de fechamento (humano) | "Eu vou comprar" |
| **5. Entrega** | Implementação da solução | "Funcionou — vou indicar" |

### O que a IA SDR antecipa no lead

- Antecipa que existe algo a ser vendido
- Antecipa o valor que isso pode gerar
- Antecipa o futuro do cliente com a solução
- Tudo isso gera **desejo de ter a solução**

---

## Operação real (o que o fundador faz no dia a dia)

- Montagem da estrutura
- Otimização da estrutura
- Realização das calls (fechamento humano)
- Relacionamento com o cliente
- Implementação da solução

---

## Roteiro de construção da operação Techla

### 1. Definindo o ICP — Método dos 3 Ps
**Status:** ✅ Concluído — ver [`01-tres-ps.md`](./01-tres-ps.md)

### 2. Página de Qualificação (com GrowthOS)
- Corpo da página
- Copy (referência: Eugene Schwartz — níveis de consciência de mercado)
- Design
- Formulário de aplicação (campos obrigatórios: nome, email, telefone)
- Integração formulário → sistema de IA
- Deploy: GitHub → Vercel
- Domínio (Hostinger)

### 3. Anúncios (com GrowthOS)
- Processo de criação
- Definindo a comunicação
- Copy com IA
- Subida do anúncio
- Métricas importantes

### 4. Abordagem com IA
- Webhook no TomikOS
- Envio JSON do formulário → webhook
- Mensagem de abordagem
- Template de abordagem
- Testes

### 5. Agente de IA SDR
- Briefing da agência (informações para construção do agente)
- Fluxo/script de venda (recepção → agendamento)
- Configuração do sistema operacional:
  - Conectar WhatsApp
  - Criar colaboradores
  - Configurar estágios do CRM
- Prompt do agente:
  - Identidade
  - Script / fluxo de trabalho + exemplos
  - Informações essenciais
  - Instrução de uso de tools + skills
  - Regras indispensáveis
- Configuração final:
  - Etapas
  - Key da OpenAI
  - Canal
  - Follow-up
  - Skills
  - Tools por etapa

### 6. Testes e Iteração
**Rotina contínua após go-live:**
- Testes
- Monitoramento
- Iteração nos ajustes da estrutura

A otimização do agente é o que diferencia uma operação amadora de uma profissional. O agente precisa estar cada vez mais refinado para:
- Seguir o script de vendas correto
- Acionar as tools no momento certo
- Cumprir o objetivo: qualificar e agendar calls

---

## Como vamos usar este playbook

Este documento é o **mapa**. Cada item do roteiro vira um documento próprio em `docs/02-operacao-comercial/` ou `docs/03-conteudo/`, com:
- Decisões específicas da Techla
- Adaptações ao nicho (clínicas de estética em Divinópolis)
- Artefatos prontos (copy, prompts, configurações)
