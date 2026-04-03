# Task: Audit Conversion

## Objetivo
Auditar uma landing page existente para identificar gaps de conversão, pontos de abandono e oportunidades de otimização priorizadas.

## Quando Usar
Quando uma landing page já existe e a taxa de conversão está abaixo do esperado, ou quando você quer identificar o maior potencial de melhoria antes de investir em mudanças.

## Agentes Envolvidos
- **peep-laja** — Auditoria heurística pelos 7 fatores CXL
- **oli-gardner** — Auditoria de Attention Ratio e anatomia
- **michael-aagaard** — Auditoria de CTA e microcopy
- **cro-specialist** — Análise de dados (GA4, heatmaps, gravações)
- **performance-engineer** — Auditoria de Core Web Vitals

## Etapas

### 1. Coleta de Dados
- [ ] Taxa de conversão atual e período de referência
- [ ] Volume de tráfego por fonte
- [ ] Taxa de bounce por dispositivo
- [ ] Heatmap e scroll map (Hotjar/Clarity)
- [ ] Gravações de sessão (últimas 20 relevantes)
- [ ] Funil no GA4 — drop-off por etapa
- [ ] PageSpeed Insights — LCP, CLS, INP

### 2. Auditoria Heurística (peep-laja — 7 fatores)
- [ ] **Relevância**: A página corresponde à expectativa do visitante?
- [ ] **Clareza**: A proposta de valor está clara em 5 segundos?
- [ ] **Valor**: O benefício percebido supera o custo percebido?
- [ ] **Fricção**: Quanta resistência existe no caminho para a conversão?
- [ ] **Distração**: Existem elementos desviando do objetivo primário?
- [ ] **Ansiedade**: O que gera insegurança ou desconfiança?
- [ ] **Urgência**: Existe razão para agir agora?

### 3. Auditoria de Estrutura (oli-gardner)
- [ ] Attention Ratio calculado e avaliado
- [ ] Message match com anúncio de origem
- [ ] Hero section em 5 segundos test
- [ ] Hierarquia de seções avaliada
- [ ] Formulário auditado (campos, labels, submit button)

### 4. Auditoria de Copy & CTA (michael-aagaard)
- [ ] Headline avaliada (clareza, benefício, especificidade)
- [ ] CTA avaliado (verbo, primeira pessoa, benefício)
- [ ] Microcopy de segurança presente?
- [ ] Objeções sendo resolvidas?

### 5. Auditoria de Performance
- [ ] LCP, CLS, INP medidos
- [ ] Mobile PageSpeed score
- [ ] Scripts de terceiros auditados

## Output Esperado
- Relatório de auditoria com gaps identificados
- Lista priorizada de problemas (PIE Score)
- 5-10 hipóteses de teste A/B priorizadas
- Quick wins (mudanças de baixo esforço e alto impacto)
