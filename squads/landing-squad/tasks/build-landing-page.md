# Task: Build Landing Page

## Objetivo
Construir uma landing page de alto impacto do zero, com diagnóstico completo de conversão, arquitetura de funil, copy orientada a benefício, design responsivo e setup de rastreamento.

## Quando Usar
Quando o objetivo é criar uma nova landing page para campanha, produto, serviço ou captura de leads.

## Agentes Envolvidos
- **landing-chief** — Orquestra, define framework e faz QA final
- **funnel-architect** — Diagnóstico de awareness, arquitetura de funil e mapeamento de jornada
- **oli-gardner** — Anatomia de página, message match e estrutura de seções
- **peep-laja** — Pesquisa de conversão e priorização
- **michael-aagaard** — CTA copy, microcopy e copy de formulário
- **copy-squad/eugene-schwartz** — Copy principal baseada em níveis de consciência
- **design-squad/visual-generator** — Visual e UI
- **performance-engineer** — Performance e Core Web Vitals
- **cro-specialist** — Setup de tracking e plano de testes A/B

## Etapas

### 1. Briefing & Diagnóstico (landing-chief + funnel-architect)
- [ ] Definir objetivo primário da página (lead, venda, demo, trial)
- [ ] Identificar ICP (Ideal Customer Profile) — quem é o visitante
- [ ] Mapear nível de consciência do tráfego
- [ ] Identificar fonte de tráfego (frio, morno, quente)
- [ ] Definir a oferta (o que o visitante recebe ao converter)
- [ ] Selecionar framework de conversão (AIDA, PAS, BAB, PASTOR, PPPP)

### 2. Construção de Oferta (hormozi-squad/hormozi-offers se necessário)
- [ ] Definir o stack de valor da oferta
- [ ] Identificar o mecanismo único
- [ ] Construir a garantia / reversão de risco
- [ ] Definir urgência/escassez (real, nunca falsa)

### 3. Arquitetura de Página (oli-gardner)
- [ ] Definir Attention Ratio (remover distrações)
- [ ] Criar wireframe de seções above/below the fold
- [ ] Mapear hierarquia visual e fluxo de leitura
- [ ] Definir posicionamento de CTA primário e secundários
- [ ] Estruturar seção de prova social
- [ ] Definir FAQ com objeções reais

### 4. Copy (michael-aagaard + copy-squad)
- [ ] Escrever 5+ headlines para teste
- [ ] Escrever subheadline
- [ ] Escrever copy de cada seção (framework selecionado)
- [ ] Escrever CTA principal (primeira pessoa, orientado a benefício)
- [ ] Escrever microcopy de segurança
- [ ] Escrever copy do formulário (labels, submit button, helper text)
- [ ] Escrever FAQ com linguagem de objeções reais

### 5. Design & UI (design-squad)
- [ ] Design responsivo mobile-first
- [ ] Hierarquia visual clara (tamanho, contraste, espaçamento)
- [ ] Botão CTA com contraste suficiente
- [ ] Imagens/videos selecionados e otimizados
- [ ] Fontes e cores alinhadas com brand

### 6. Performance (performance-engineer)
- [ ] Imagens em WebP/AVIF, comprimidas e com dimensões explícitas
- [ ] Preload da imagem LCP
- [ ] Scripts de terceiros com defer/async ou lazy load
- [ ] Critical CSS inline
- [ ] CDN configurado
- [ ] LCP < 2.5s | CLS < 0.1 | INP < 200ms

### 7. Tracking & Analytics (cro-specialist + funnel-architect)
- [ ] GTM instalado e configurado
- [ ] Eventos de scroll (25%, 50%, 75%, 90%)
- [ ] Evento de click no CTA
- [ ] Eventos de form (focus, field, submit, error)
- [ ] Evento de conversão (GA4 + Meta Pixel + Google Ads)
- [ ] Página de obrigado com confirmation event
- [ ] CRM integration (lead data + fonte)

### 8. QA de Conversão (landing-chief)
- [ ] Message match com o anúncio de origem
- [ ] Attention Ratio verificado
- [ ] CTA above the fold
- [ ] Mobile testado em dispositivo real
- [ ] Velocidade validada no PageSpeed Insights
- [ ] Todos os tracking events disparando
- [ ] Formulário testado end-to-end
- [ ] Links/redirects testados

## Output Esperado
- Landing page publicada e funcionando
- Relatório de tracking configurado
- Plano de primeiros A/B tests priorizados
- Sequência de email pós-conversão configurada
