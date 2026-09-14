# 🧠 Avaliação e Conformidade de Modelos de Inteligência Artificial Responsável em Saúde

### Dissertação de Mestrado — PPGIT/UFMG

> Pesquisa sobre avaliação, governança, risco e conformidade de sistemas de Inteligência Artificial aplicados à saúde, integrando dimensões técnicas, éticas e regulatórias.

---

## 👤 Informações acadêmicas

| Informação | Descrição |
|---|---|
| **Autor** | Bruno Martins Bartolomeu |
| **Programa** | Programa de Pós-Graduação em Inovação Tecnológica — PPGIT |
| **Instituição** | Universidade Federal de Minas Gerais — UFMG |
| **Orientador** | Prof. Wagner Meira Jr. — DCC/UFMG |
| **Coorientação científica** | Profa. Patrícia M. Parreiras — Instituto René Rachou / Fiocruz Minas |
| **Área** | Inteligência Artificial Responsável, Saúde Digital, Governança de IA e Ciência de Dados |
| **Metodologia** | Design Science Research — DSR |
| **Base empírica** | MIMIC-IV v3.1 — PhysioNet |

---

## 📑 Sumário

- [Sobre a pesquisa](#-sobre-a-pesquisa)
- [Problema de pesquisa](#-problema-de-pesquisa)
- [Objetivo](#-objetivo)
- [Metodologia](#-metodologia)
- [FAC-IA Saúde](#-fac-ia-saúde)
- [Base empírica — MIMIC-IV v3.1](#-base-empírica--mimic-iv-v31)
- [Preparação e acesso aos dados](#-preparação-e-acesso-aos-dados)
- [Variáveis analisadas](#-variáveis-analisadas)
- [Análises desenvolvidas](#-análises-desenvolvidas)
- [Principais achados](#-principais-achados)
- [IA Responsável em Saúde](#-ia-responsável-em-saúde)
- [Referenciais técnicos, éticos e regulatórios](#-referenciais-técnicos-éticos-e-regulatórios)
- [Ética em pesquisa](#-ética-em-pesquisa)
- [Produção científica associada](#-produção-científica-associada)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Organização do repositório](#-organização-do-repositório)
- [Limitações](#-limitações)
- [Referências](#-referências)
- [Aviso](#-aviso)

---

## 🔬 Sobre a pesquisa

Este repositório reúne **códigos, análises, documentação, resultados e artefatos computacionais** desenvolvidos no contexto da dissertação de mestrado:

> **“Avaliação e Conformidade de Modelos de Inteligência Artificial Responsável em Saúde”**

A pesquisa investiga mecanismos para avaliação sistemática de modelos e sistemas de Inteligência Artificial aplicados à saúde, considerando de forma integrada aspectos **técnicos, éticos e regulatórios**.

O trabalho busca contribuir para o desenvolvimento, avaliação, governança e uso responsável de IA em ambientes de saúde, especialmente em cenários nos quais decisões automatizadas ou apoiadas por algoritmos podem produzir impactos clínicos, éticos, sociais e regulatórios.

---

## ❓ Problema de pesquisa

A crescente utilização de Inteligência Artificial na saúde amplia a necessidade de mecanismos capazes de avaliar não apenas o desempenho técnico dos modelos, mas também aspectos relacionados a:

- governança;
- proteção e qualidade dos dados;
- privacidade e LGPD;
- segurança e risco clínico;
- transparência;
- explicabilidade;
- robustez;
- monitoramento;
- equidade;
- supervisão humana;
- responsabilização.

Nesse contexto, a pesquisa estrutura uma abordagem multidimensional para **avaliação e conformidade de sistemas de IA aplicados à saúde**.

---

## 🎯 Objetivo

Desenvolver e avaliar uma estrutura sistemática para análise de **Inteligência Artificial Responsável em Saúde**, integrando requisitos:

- técnicos;
- éticos;
- regulatórios;
- de governança;
- de proteção de dados;
- de segurança e risco clínico;
- de transparência e explicabilidade;
- de robustez e monitoramento.

---

## 🧩 Metodologia

A pesquisa foi estruturada utilizando **Design Science Research (DSR)**.

A DSR possibilita desenvolver e avaliar artefatos destinados à resolução de problemas relevantes, estabelecendo uma relação entre fundamentação científica, construção do artefato e avaliação.

### Percurso metodológico

1. **Identificação e caracterização do problema**
2. **Revisão da literatura**
3. **Análise de referenciais técnicos, éticos e regulatórios**
4. **Definição dos requisitos e critérios de avaliação**
5. **Desenvolvimento do artefato**
6. **Aplicação em contexto clínico com dados reais**
7. **Análise dos resultados**
8. **Discussão das limitações e implicações para IA responsável em saúde**

---

# 🏥 FAC-IA Saúde

O principal artefato desenvolvido na pesquisa é o **FAC-IA Saúde — Framework de Avaliação e Conformidade de Inteligência Artificial em Saúde**.

O framework foi concebido para apoiar a avaliação estruturada de modelos e sistemas de IA utilizados no domínio da saúde.

## Estrutura geral

O FAC-IA Saúde possui:

| Elemento | Estrutura |
|---|---:|
| **Etapas** | 5 |
| **Domínios** | 5 |
| **Pilares** | 3 |
| **Critérios por pilar** | 15 |
| **Total de critérios** | **45** |
| **Dimensões de risco** | 4 |

### Tríade de avaliação

| Pilar | Perspectiva |
|---|---|
| **Técnico** | desempenho, robustez, segurança, confiabilidade e monitoramento |
| **Ético** | equidade, transparência, explicabilidade, responsabilidade e supervisão humana |
| **Regulatório** | governança, conformidade, proteção de dados, documentação e responsabilização |

---

## Os cinco domínios do FAC-IA Saúde

### 1. 🏛️ Governança

Avaliação das estruturas de responsabilidade, gestão, documentação, supervisão e processos relacionados ao ciclo de vida da IA.

### 2. 🔐 Dados e LGPD

Avaliação da qualidade, procedência, governança, privacidade e proteção dos dados utilizados pelos sistemas de IA.

### 3. 🩺 Segurança e risco clínico

Análise dos riscos associados ao uso da IA no contexto assistencial e dos potenciais impactos sobre pacientes, profissionais e organizações de saúde.

### 4. 🔎 Transparência e explicabilidade

Avaliação da capacidade de documentar, compreender e comunicar o funcionamento, as limitações e os resultados produzidos pelos modelos.

### 5. 📊 Robustez e monitoramento

Avaliação da estabilidade, desempenho, generalização e acompanhamento contínuo dos sistemas de IA durante seu ciclo de vida.

---

# 🗄️ Base empírica — MIMIC-IV v3.1

A etapa empírica utiliza a:

**MIMIC-IV v3.1 — Medical Information Mart for Intensive Care**

A base é disponibilizada pelo **MIT Laboratory for Computational Physiology / PhysioNet**.

### Base oficial

https://physionet.org/content/mimiciv/3.1/

### População considerada

| Indicador | Quantidade |
|---|---:|
| **Pacientes** | 364.627 |
| **Internações** | 546.028 |

Entre as estruturas utilizadas nas análises estão tabelas do módulo hospitalar (`hosp`) e tabelas derivadas (`derive`) da MIMIC-IV.

> ⚠️ **Os dados originais da MIMIC-IV não são redistribuídos neste repositório.** O acesso deve ser realizado diretamente pelo PhysioNet, observando os requisitos de credenciamento, treinamento e uso da base.

---

## 🔑 Preparação e acesso aos dados

Para utilização da MIMIC-IV foram cumpridos requisitos de capacitação e acesso estabelecidos pelo PhysioNet.

### CITI Program

**Conclusão:** 03/07/2025

| Avaliação | Resultado |
|---|---:|
| **HIPAA** | 97% |
| **Conflict of Interest — COI** | 80% |

---

## 📋 Variáveis analisadas

As análises consideram, entre outras:

| Grupo | Variáveis |
|---|---|
| **Demográficas** | idade e sexo |
| **Gravidade** | escore SOFA |
| **Condição clínica** | sepse |
| **Desfecho** | mortalidade hospitalar |
| **Hospitalização** | tempo de permanência — LOS |
| **Perfil clínico** | comorbidades |
| **Risco** | características clínicas relevantes para estratificação |

A caracterização de sepse considera os princípios estabelecidos pelo **Sepsis-3**.

---

## 📈 Análises desenvolvidas

### Caracterização da população

Análise descritiva dos pacientes e das internações para compreensão das principais características clínicas e demográficas.

### Idade e mortalidade

Investigação da relação entre idade, gravidade clínica e mortalidade hospitalar.

### Sexo e gravidade clínica

Avaliação de diferenças segundo sexo, com atenção especial aos estratos de maior gravidade.

### Escore SOFA

Análise da associação entre níveis de SOFA e mortalidade hospitalar, incluindo estratificação por níveis ou quartis de gravidade.

### Sepse

Caracterização dos pacientes com sepse e análise das relações entre gravidade, características clínicas e desfechos hospitalares.

### Comorbidades e escores prognósticos

Investigação da relação entre comorbidades, escores clínicos e estratificação de risco.

### Heterogeneidade de risco

Avaliação das diferenças de risco clínico e mortalidade entre subgrupos, evidenciando por que avaliações exclusivamente agregadas podem ser insuficientes para sistemas de IA aplicados à saúde.

---

## 📌 Principais achados

As análises desenvolvidas evidenciaram:

- **crescimento da mortalidade com o avanço da idade**;
- **aumento da mortalidade nos estratos mais elevados do escore SOFA**;
- diferenças segundo sexo em cenários de maior gravidade;
- **heterogeneidade de risco clínico entre diferentes subgrupos**;
- necessidade de avaliar sistemas de IA considerando características populacionais e clínicas, e não apenas métricas globais de desempenho.

Os resultados reforçam a necessidade de abordagens de IA responsável que integrem **desempenho, segurança, equidade, transparência, governança e conformidade**.

---

# ⚖️ IA Responsável em Saúde

A pesquisa considera que sistemas de IA aplicados à saúde devem ser avaliados em múltiplas dimensões.

| Dimensão | Foco |
|---|---|
| **Governança** | responsabilidades, documentação, rastreabilidade e supervisão |
| **Equidade** | diferenças de desempenho, risco e impacto entre grupos |
| **Transparência** | informações sobre dados, modelos, limitações e processos |
| **Explicabilidade** | compreensão dos fatores relacionados às previsões ou decisões |
| **Supervisão humana** | participação humana em decisões relevantes |
| **Segurança** | identificação e gerenciamento de riscos |
| **Monitoramento** | acompanhamento do desempenho ao longo do ciclo de vida |
| **Proteção de dados** | privacidade, governança e conformidade no tratamento de dados |

---

## 📚 Referenciais técnicos, éticos e regulatórios

A construção e discussão do FAC-IA Saúde consideram referenciais como:

- **Lei Geral de Proteção de Dados — LGPD (2018)**;
- **European Union Artificial Intelligence Act — EU AI Act (2024)**;
- **WHO — Ethics and Governance of Artificial Intelligence for Health (2021)**;
- **UNESCO — Recommendation on the Ethics of Artificial Intelligence (2021)**;
- **OECD Principles on Artificial Intelligence (2019)**;
- **NIST Artificial Intelligence Risk Management Framework — AI RMF**;
- **ISO/IEC 42001 — Artificial Intelligence Management System**;
- **IEC 62304 — Medical Device Software — Software Life Cycle Processes**;
- referenciais da **FDA** relacionados a Software as a Medical Device — SaMD;
- literatura científica sobre IA em medicina, interpretabilidade, explicabilidade, vieses algorítmicos, governança e bioética.

---

## 🧑‍⚕️ Ética em pesquisa

A pesquisa de campo inicialmente planejada para integrar a dissertação foi retirada do trabalho em razão das exigências éticas aplicáveis à coleta com participantes.

A eventual coleta com profissionais é tratada separadamente mediante tramitação ética pertinente, considerando especialmente:

- **Resolução CNS nº 466/2012**;
- **Resolução CNS nº 510/2016**.

Essa separação preserva a distinção entre as análises realizadas com dados clínicos desidentificados da MIMIC-IV e pesquisas que envolvam participação direta de profissionais ou outros participantes.

---

# 📝 Produção científica associada

A dissertação originou diferentes frentes de produção científica.

### 1. Heterogeneidade de risco clínico e mortalidade na sepse

**HETEROGENEIDADE DE RISCO CLÍNICO E MORTALIDADE NA SEPSE: IMPLICAÇÕES PARA ESTRATIFICAÇÃO DE RISCO E IA RESPONSÁVEL**

Investigação das diferenças de risco clínico entre subgrupos e de suas implicações para modelos de estratificação de risco e Inteligência Artificial Responsável.

### 2. Comorbidades e escores prognósticos

**COMORBIDADES E ESCORES PROGNÓSTICOS NA ESTRATIFICAÇÃO DE RISCO DE PACIENTES COM SEPSE: UMA ANÁLISE DA BASE MIMIC-IV v3.1**

Análise da relação entre comorbidades, escores clínicos e estratificação de risco utilizando dados da MIMIC-IV v3.1.

### 3. FAC-IA Saúde

Produção científica relacionada ao **framework de avaliação, governança e uso responsável de Inteligência Artificial na saúde**.

### 4. Transparência, explicabilidade e supervisão humana

Discussão dos mecanismos necessários para tornar sistemas de IA utilizados em saúde mais transparentes, compreensíveis, auditáveis e supervisionáveis.

---

## 🛠️ Tecnologias utilizadas

![Python](https://img.shields.io/badge/Python-Data%20Science-blue)
![MIMIC-IV](https://img.shields.io/badge/MIMIC--IV-v3.1-green)
![DSR](https://img.shields.io/badge/Methodology-Design%20Science%20Research-orange)
![AI](https://img.shields.io/badge/AI-Responsible%20AI-purple)

Principais tecnologias e ferramentas:

- Python;
- Pandas;
- NumPy;
- Matplotlib;
- análise estatística;
- processamento e preparação de dados clínicos;
- Jupyter Notebook;
- SQL;
- Git;
- GitHub;
- MIMIC-IV / PhysioNet.

---

## 📁 Organização do repositório

```text
Projeto_Pesquisa_PPGIT_UFMG/
│
├── README.md
│
├── data/
│   └── documentação e orientações sobre os dados
│
├── notebooks/
│   └── análises exploratórias
│
├── scripts/
│   └── códigos Python
│
├── results/
│   └── resultados das análises
│
├── figures/
│   └── gráficos e figuras
│
├── docs/
│   └── documentação científica
│
└── references/
    └── materiais de apoio e referências
```

---

## ⚠️ Limitações

Os resultados devem ser interpretados considerando:

- a natureza observacional da MIMIC-IV;
- o contexto clínico e institucional no qual os dados foram produzidos;
- limitações inerentes à utilização secundária de registros eletrônicos de saúde;
- possíveis diferenças de representatividade entre grupos;
- limites de generalização para outras populações e instituições.

Os resultados **não devem ser interpretados como recomendações clínicas individuais**.

O FAC-IA Saúde possui finalidade científica e metodológica de avaliação e conformidade de sistemas de Inteligência Artificial em saúde.

---

## 🏛️ Instituições relacionadas à pesquisa

**Universidade Federal de Minas Gerais — UFMG**  
Programa de Pós-Graduação em Inovação Tecnológica — PPGIT

**Departamento de Ciência da Computação — DCC/UFMG**

**Instituto René Rachou — Fiocruz Minas**

---

## 👨‍💻 Autor

### Bruno Martins Bartolomeu

Pesquisa desenvolvida no âmbito do **Programa de Pós-Graduação em Inovação Tecnológica da Universidade Federal de Minas Gerais — PPGIT/UFMG**.

Áreas relacionadas ao projeto:

- Inteligência Artificial Responsável;
- Ciência de Dados;
- Saúde Digital;
- Governança de IA;
- avaliação e conformidade de sistemas de IA;
- Machine Learning aplicado à saúde.

---

# 📖 Referências

## Inteligência Artificial, ética, saúde e governança

BRASIL. **Lei nº 13.709, de 14 de agosto de 2018. Lei Geral de Proteção de Dados Pessoais (LGPD)**. Brasília, DF, 2018.

EUROPEAN UNION. **Regulation (EU) 2024/1689 of the European Parliament and of the Council laying down harmonised rules on artificial intelligence (Artificial Intelligence Act)**. *Official Journal of the European Union*, 2024.

OECD. **Recommendation of the Council on Artificial Intelligence**. Paris: Organisation for Economic Co-operation and Development, 2019.

UNESCO. **Recommendation on the Ethics of Artificial Intelligence**. Paris: UNESCO, 2021.

WORLD HEALTH ORGANIZATION. **Ethics and governance of artificial intelligence for health: WHO guidance**. Geneva: World Health Organization, 2021.

### Gestão de risco, conformidade e sistemas de IA

NATIONAL INSTITUTE OF STANDARDS AND TECHNOLOGY. **Artificial Intelligence Risk Management Framework (AI RMF 1.0)**. Gaithersburg: NIST, 2023.

INTERNATIONAL ORGANIZATION FOR STANDARDIZATION; INTERNATIONAL ELECTROTECHNICAL COMMISSION. **ISO/IEC 42001:2023 — Information technology — Artificial intelligence — Management system**. Geneva: ISO, 2023.

INTERNATIONAL ELECTROTECHNICAL COMMISSION. **IEC 62304 — Medical device software — Software life cycle processes**. Geneva: IEC.

U.S. FOOD AND DRUG ADMINISTRATION. **Software as a Medical Device (SaMD) and Artificial Intelligence/Machine Learning-Enabled Medical Devices**. Silver Spring: FDA.

### Inteligência Artificial aplicada à medicina

TOPOL, E. J. **High-performance medicine: the convergence of human and artificial intelligence**. *Nature Medicine*, v. 25, p. 44–56, 2019.

OBERMEYER, Z.; POWERS, B.; VOGELI, C.; MULLAINATHAN, S. **Dissecting racial bias in an algorithm used to manage the health of populations**. *Science*, v. 366, n. 6464, p. 447–453, 2019.

HOLZINGER, A.; LANGS, G.; DENK, H.; ZATLOUKAL, K.; MÜLLER, H. **Causability and explainability of artificial intelligence in medicine**. *WIREs Data Mining and Knowledge Discovery*, v. 9, n. 4, 2019.

### Interpretabilidade e explicabilidade

LIPTON, Z. C. **The mythos of model interpretability**. *Communications of the ACM*, v. 61, n. 10, p. 36–43, 2018.

DOSHI-VELEZ, F.; KIM, B. **Towards a rigorous science of interpretable machine learning**. 2017.

### Ética e bioética

BEAUCHAMP, T. L.; CHILDRESS, J. F. **Principles of Biomedical Ethics**. 8. ed. New York: Oxford University Press, 2019.

### MIMIC-IV e sepse

JOHNSON, A. E. W. et al. **MIMIC-IV, a freely accessible electronic health record dataset**. *Scientific Data*, v. 10, 2023.

PHYSIONET. **MIMIC-IV v3.1**. Disponível em: https://physionet.org/content/mimiciv/3.1/

SINGER, M. et al. **The Third International Consensus Definitions for Sepsis and Septic Shock (Sepsis-3)**. *JAMA*, v. 315, n. 8, p. 801–810, 2016.

### Design Science Research

HEVNER, A. R.; MARCH, S. T.; PARK, J.; RAM, S. **Design science in information systems research**. *MIS Quarterly*, v. 28, n. 1, p. 75–105, 2004.

PEFFERS, K.; TUUNANEN, T.; ROTHENBERGER, M. A.; CHATTERJEE, S. **A design science research methodology for information systems research**. *Journal of Management Information Systems*, v. 24, n. 3, p. 45–77, 2007.

### Ética em pesquisa no Brasil

CONSELHO NACIONAL DE SAÚDE. **Resolução nº 466, de 12 de dezembro de 2012**. Diretrizes e normas regulamentadoras de pesquisas envolvendo seres humanos.

CONSELHO NACIONAL DE SAÚDE. **Resolução nº 510, de 7 de abril de 2016**. Normas aplicáveis a pesquisas em Ciências Humanas e Sociais.

---

# ⚠️ Aviso

Este repositório possui finalidade **acadêmica e científica**.

Os resultados, códigos, análises e artefatos disponibilizados devem ser interpretados no contexto da pesquisa e **não constituem ferramentas para diagnóstico, prognóstico ou tomada de decisão clínica**.

O uso da MIMIC-IV deve respeitar integralmente as condições estabelecidas pelo PhysioNet.

---

<p align="center">
  <strong>PPGIT • UFMG • Inteligência Artificial Responsável em Saúde</strong>
</p>

