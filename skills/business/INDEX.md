# SKILL LIBRARY — Business & Tax Brasil
# Indice Geral | Versao: 1.0.0 | Criado: 2026-05-17
# Sessao: sess_20260517_2226_biz | Autor: Joelson Hott
# GitHub: https://github.com/Joehott/skills/tree/main/skills/business

---

## VISAO GERAL

Esta biblioteca reune 11 arquivos (10 skills + 1 script Python) cobrindo
analise de negocios, validacao de ideias, plano de negocios, tributacao brasileira
completa e otimizacao fiscal para pessoa fisica. Destina-se a uso em chats
especializados de mentoria, analise e planejamento empresarial.

```
TOTAL: ~213 KB de conhecimento estruturado
ARQUIVOS: 10 skills (.md) + 1 script executavel (.py)
LINHAS: ~4.900 linhas de conteudo
CNAE: 200+ codigos mapeados (script Python)
```

---

## MAPA DE USO — QUANDO CARREGAR CADA SKILL

```
SITUACAO                                  | SKILLS A CARREGAR
------------------------------------------|------------------------------------------
Abrir uma nova empresa                    | brazil_tax_regulatory + brazil_tax_complete
Validar uma ideia de negocio              | business_idea_validation + business_viability_calculation
Fazer plano de negocios completo          | business_plan_creation + business_viability_calculation + brazil_tax_regulatory
Analise rapida de empresa existente       | business_analysis
Calcular viabilidade financeira           | business_viability_calculation
Consultar regime tributario por CNAE      | brazil_cnae_database.py (executar) + brazil_tax_complete
Planejar calendario fiscal 2026           | brazil_tax_obligations_calendar
Aproveitar regime especial (RET/ZFM/etc)  | brazil_tax_special_regimes
Entender impacto da Reforma Tributaria    | brazil_tax_reform_2026_2032
Otimizar retirada do socio (PF)          | brazil_tax_individual_optimization
Planejamento sucessorio / ITCMD          | brazil_tax_individual_optimization
Negociar divida tributaria               | brazil_tax_special_regimes (secao 7)
Captacao de investimento                 | business_viability_calculation (secao 9)
```

---

## GRUPO 1 — ANALISE E ESTRATEGIA DE NEGOCIOS

### 1.1 business_analysis.md
**Tamanho:** 9.1 KB | **Drive:** `1AbOI6nBDYwzCoPhiVqqoV-K7jXHSe5yC`
**GitHub:** `skills/business/business_analysis.md`

Frameworks de analise empresarial:
- SWOT (Strengths, Weaknesses, Opportunities, Threats)
- Porter's 5 Forces (rivalidade, entrantes, substitutos, fornecedores, clientes)
- PESTEL (Politico, Economico, Social, Tecnologico, Ecologico, Legal)
- Cadeia de Valor (Porter)
- Matriz BCG (Stars, Cash Cows, Question Marks, Dogs)
- VRIO (Valor, Raridade, Imitabilidade, Organizacao)
- Analise Financeira (liquidez, rentabilidade, endividamento)
- Mapa Competitivo (posicionamento vs concorrencia)
- Checklist de analise completa
- Fontes de dados no Brasil (CVM, IBGE, SEBRAE, B3)

---

### 1.2 business_idea_validation.md
**Tamanho:** 12.3 KB | **Drive:** `17tEnZgF14RlXuAsyE1tL9U02YAuqqG20`
**GitHub:** `skills/business/business_idea_validation.md`

Metodologias de validacao:
- Lean Canvas (9 blocos)
- Business Model Canvas (BMC)
- Problem-Solution Fit (entrevistas e experimentos)
- Product-Market Fit (PMF) — metricas e sinais
- TAM / SAM / SOM (dimensionamento de mercado)
- Experimentos Lean (MVP, A/B, smoke test, landing page)
- Jobs To Be Done (JTBD)
- Unit Economics (LTV, CAC, payback, margem de contribuicao)
- Checklist de validacao completa

---

### 1.3 business_plan_creation.md
**Tamanho:** 12.8 KB | **Drive:** `1-4UzQxspzYqZPrgZd01QD8VNJZ2yKS7s`
**GitHub:** `skills/business/business_plan_creation.md`

8 secoes completas do plano de negocios:
- Sumario Executivo
- Descricao da Empresa (missao, visao, valores, CNPJ)
- Analise de Mercado (TAM/SAM/SOM, personas, concorrencia)
- Plano de Marketing e Vendas (4Ps, CAC, funil)
- Plano Operacional (processos, tecnologia, fornecedores)
- Estrutura Organizacional (organograma, equipe-chave)
- Plano Financeiro (DRE 3 anos, capex, break-even)
- Analise de Riscos (matriz probabilidade × impacto)
- Guia para Pitch Deck (10 slides)
- Checklist de qualidade do plano

---

### 1.4 business_viability_calculation.md
**Tamanho:** 13.6 KB | **Drive:** `1izTAFQi7855xt2QNjzTu5LsjNaRHyUTE`
**GitHub:** `skills/business/business_viability_calculation.md`

Calculos financeiros de viabilidade:
- Break-Even: contabil, financeiro e economico
- Payback Simples e Payback Descontado (com tabela exemplo)
- VPL — Valor Presente Liquido (formula + exemplo + Excel)
- TIR — Taxa Interna de Retorno (benchmarks Brasil 2025)
- Modelo de Projecao Financeira 3 anos (template DRE mensal)
- Analise de Cenarios (pessimista / base / otimista)
- Valuation: DCF, Multiplos, Berkus, Scorecard, VC Method
- Fontes de financiamento no Brasil (BNDES, Finep, angel, VC)
- TMA referencia Brasil 2025: SELIC + premio risco = 15-20%
- Checklist de viabilidade completo (6 gates de aprovacao)

---

## GRUPO 2 — TRIBUTACAO BRASILEIRA — NUCLEO

### 2.1 brazil_tax_regulatory.md
**Tamanho:** 15.9 KB | **Drive:** `1x1pOXlla4vOaR3xgcWn5JJCwZV4uq6sQ`
**GitHub:** `skills/business/brazil_tax_regulatory.md`

Guia estrategico de tributacao:
- Comparativo de tipos de empresa (MEI, ME, EPP, LTDA, SAS, SA)
- Regimes tributarios: tabela de decisao (MEI → Simples → Presumido → Real)
- Simples Nacional: todos os 5 Anexos com tabelas completas
- Formula da aliquota efetiva (RBT12 × nominal - deducao) / RBT12
- Reforma Tributaria 2026: dividendos (PL 1087) + CBS/IBS
- Pro-labore vs dividendos: calculadora de remuneracao do socio
- Holding familiar: quando criar e como estruturar
- Abertura de empresa: fluxo passo a passo
- 8 armadilhas tributarias mais comuns
- Carga tributaria real: simulador mental

---

### 2.2 brazil_tax_complete.md
**Tamanho:** 32.8 KB | **Drive:** `1axWv7hrDpKUbvKLXMcGj94cRLzmuOASv` *(maior arquivo)*
**GitHub:** `skills/business/brazil_tax_complete.md`

Referencia completa de todos os 6 regimes:
- MEI: DAS fixo 2025, limites, vedacoes, passo a passo
- Simples Nacional: 5 Anexos + Fator-R + PGDAS-D + DEFIS
- Lucro Presumido: tabela IRPJ/CSLL por setor, PIS/COFINS cumulativos
- Lucro Real: LALUR, estimativa mensal vs trimestral, ECD/ECF
- SA Capital Aberto: IPO, B3, CVM, IFRS, Formulario de Referencia
- Capital Estrangeiro: RDE-IED BACEN, Transfer Pricing OCDE 2024
- CNAE × Regime: mapeamento de 30+ setores
- CLT × Regime: encargos patronais por regime
- Topicos especiais: CPRB, ISS Fixo, ICMS-ST, Lucro Arbitrado
- Arvore de decisao final de regime

---

## GRUPO 3 — TRIBUTACAO BRASILEIRA — EXPANSAO

### 3.1 brazil_tax_obligations_calendar.md (TAREFA 1)
**Tamanho:** 18.5 KB | **Drive:** `1huXNBoL7MIZyYjGA3Am6EhmGKZNpEPY3`
**GitHub:** `skills/business/brazil_tax_obligations_calendar.md`

Calendario fiscal completo:
- Calendario mensal: FGTS (dia 7), DAS/PGDAS-D (dia 20), PIS/COFINS (dia 25), DCTFWeb
- Calendario trimestral: IRPJ/CSLL Lucro Presumido/Real, ITR (SA)
- Calendario anual por regime: MEI (DASN-SIMEI), Simples (DEFIS), Lucro (ECD/ECF)
- TCO fiscal: custo real de conformidade por porte (MEI → SA Capital Aberto)
- Tabela de multas referencia rapida (DAS, DCTFWeb, EFD, FGTS, eSocial)
- Calendario consolidado 2026: todas as datas criticas do ano
- Obrigacoes por evento: admissao CLT, demissao, capital estrangeiro, fusao
- Sistemas e portais obrigatorios: eSocial, SPED, e-CAC, FGTS Digital
- Checklist de conformidade fiscal anual

---

### 3.2 brazil_tax_special_regimes.md (TAREFA 2)
**Tamanho:** 21.6 KB | **Drive:** `1pOId5qtTtLa68gU-NLqP7qaTRubV81qD`
**GitHub:** `skills/business/brazil_tax_special_regimes.md`

Regimes especiais e incentivos:
- RET (imobiliario): 4% unificado vs ~5.9% Lucro Presumido — economia ~1.9pp
- REIDI (infraestrutura): suspensao PIS/COFINS em projetos >R$50M
- Lei do Bem (P&D): exclusao 60-80% despesas do IRPJ/CSLL no Lucro Real
- Zona Franca de Manaus: IPI zero + ICMS reduzido + beneficios ate 2073
- RECAP (exportadores): suspensao PIS/COFINS no imobilizado (>50% exportacao)
- PADIS (semicondutores): aliquota zero IPI/PIS/COFINS ate 2049
- Transacao Tributaria / PERT: descontos ate 100% multas/juros (120-145 parcelas)
- Comparativo: quando usar cada regime especial
- Checklists de adesao rapida
- Impacto da Reforma 2026-2032 em cada regime

---

### 3.3 brazil_tax_reform_2026_2032.md (TAREFA 3)
**Tamanho:** 21.9 KB | **Drive:** `1jiScpU62Zu_Rrtph80GC1Nk6_CJvCdhq`
**GitHub:** `skills/business/brazil_tax_reform_2026_2032.md`

Guia completo da Reforma Tributaria (EC 132/2023 + LC 214/2025):
- Cronograma 2026-2033: aliquotas CBS/IBS ano a ano
- CBS (substitui PIS/COFINS): 0.9% em 2026, ~8-9% plena 2027+
- IBS (substitui ICMS/ISS): 0.1% em 2026, ~17-19% pleno 2033
- Imposto Seletivo (IS): tabaco, bebidas, veiculos por emissao CO2
- PL 1087/2025: IRPF Minimo 10% (renda >R$600K/ano) + IRRF 10% dividendos >R$50K/mes
- Split Payment: CBS/IBS retidos na fonte do pagamento — impacto no caixa
- Principio de destino: elimina guerra fiscal entre estados, elimina DIFAL
- Impacto por setor: SaaS/servicos digitais (+15pp), industria (neutro), exportacao (positivo)
- Simples Nacional na transicao: DAS mantido, decisao 2027
- Simulacoes numericas: SaaS R$1M/mes e industria R$1M/mes
- Checklist de preparacao empresarial por ano

---

### 3.4 brazil_tax_individual_optimization.md (TAREFA 4)
**Tamanho:** 22.0 KB | **Drive:** `1IiyHUJus1DO7aVtixuBgQ-OQDXPS2rHh`
**GitHub:** `skills/business/brazil_tax_individual_optimization.md`

Otimizacao fiscal para pessoa fisica e socio:
- Tabela IRPF 2026: isencao ate R$5.000/mes (PL 1087/2025)
- IRPF Minimo: calculo exato com 3 exemplos (R$300K, R$700K, R$1.2M/ano)
- Pro-labore otimo: R$5K/mes (isento) + dividendos ate R$50K/mes
- Tabela comparativa pro-labore vs dividendo para cada faixa de renda
- PGBL/VGBL: deducao 12% renda tributavel, tabela regressiva (10% apos 10 anos)
- ITCMD progressivo 2027: urgencia de doacao em vida em 2026 (janela critica)
- Holding familiar: quando vale a pena, estrutura, cláusulas de protecao
- VGBL para sucessao: fora do espolio, sem ITCMD (enquanto nao regulamentado)
- Seguro de vida: isento IRPF e ITCMD
- Simulador de carga fiscal: socio R$30K/mes = 1.8% carga, R$100K/mes = 10.5%
- Checklist de revisao anual para o socio

---

## GRUPO 4 — FERRAMENTAS

### 4.1 brazil_cnae_database.py (TAREFA 5)
**Tamanho:** 30 KB | **Drive:** `1F1pwoWU_xXkXXRuPbqK6PaFXoeCA44w9`
**GitHub:** `skills/business/brazil_cnae_database.py`

Script Python executavel — consulta CNAE × Regime × Aliquota:

```bash
# Consultar CNAE especifico
python3 brazil_cnae_database.py 6201500

# Buscar por termo
python3 brazil_cnae_database.py --search engenharia

# Simular aliquota com Fator-R
python3 brazil_cnae_database.py --simular --cnae 7112000 --faturamento 800000 --folha 250000

# Listar todos os CNAEs vedados no Simples
python3 brazil_cnae_database.py --list-vedados
```

Recursos:
- 200+ CNAEs mapeados com Anexo Simples, ISS, ICMS, IPI
- Calculo automatico do Fator-R (Anexo III vs Anexo V)
- Aliquota efetiva Simples por faixa de faturamento
- Comparativo automatico Simples vs Lucro Presumido
- CNAEs vedados com motivo de vedacao
- Busca textual por descricao da atividade

---

## REFERENCIAS EXTERNAS

```
SISTEMA            | URL                                    | USO
-------------------|----------------------------------------|---------------------------
GitHub Repo        | github.com/Joehott/skills              | Versionamento de todas as skills
Google Drive       | Pasta ID: 1rUocPt6teyKFQeS7zjF5HH7F9nE32kd2 | Backup e acesso externo
Notion Sessao      | notion.so (ver state.json)             | Documentacao e historico
Receita Federal    | receita.fazenda.gov.br                 | Validar aliquotas vigentes
Portal Simples SN  | receita.fazenda.gov.br/SimplesNacional | Calcular DAS oficial
Reforma Tributaria | gov.br/reformatributaria               | CBS/IBS regulamentacao
PGFN Transacao     | regularize.pgfn.gov.br                 | Negociar dividas PGFN
eSocial            | esocial.gov.br                         | Folha de pagamento
SPED               | sped.rfb.gov.br                        | ECD, ECF, EFD
```

---

## PROXIMOS PASSOS SUGERIDOS

```
EXPANSOES POSSIVEIS:
[ ] brazil_tax_municipal_iss.md — ISS por municipio (top 20 cidades)
[ ] brazil_financial_modeling.xlsx — Planilha integrada DRE + Fluxo + Indices
[ ] brazil_startup_equity.md — Cap table, ESOP, vesting, SAFEs no Brasil
[ ] brazil_labor_law.md — CLT completa: verbas, jornada, demissao, terceirizacao
[ ] brazil_international_trade.md — Importacao/exportacao, drawback, RAC
[ ] brazil_cnae_database_v2.py — Expandir para 500+ CNAEs + API da Receita Federal

INTEGRACAO FUTURA:
[ ] DB SQLite com todos os CNAEs da Receita Federal (~1.300 codigos)
[ ] API wrapper para consulta automatica de aliquota vigente
[ ] Integracao com Notion Database para gestao de clientes de mentoria
```

---

*Indice gerado automaticamente em 2026-05-17 | sess_20260517_2226_biz*
