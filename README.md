Avaliação e Conformidade de Modelos de Inteligência Artificial Responsável em Saúde

Dissertação de Mestrado — PPGIT/UFMG

Autor: Bruno Martins Bartolomeu
Programa: Programa de Pós-Graduação em Inovação Tecnológica — PPGIT
Instituição: Universidade Federal de Minas Gerais — UFMG
Orientador: Prof. Wagner Meira Jr. — DCC/UFMG
Coorientação científica: Profa. Patrícia M. Parreiras — Instituto René Rachou / Fiocruz Minas
Área: Inteligência Artificial Responsável, Saúde Digital, Governança de IA e Ciência de Dados

Sobre o projeto

Este repositório reúne códigos, análises, documentação e artefatos computacionais desenvolvidos no contexto da dissertação de mestrado “Avaliação e Conformidade de Modelos de Inteligência Artificial Responsável em Saúde”.

A pesquisa investiga mecanismos para avaliação sistemática de modelos e sistemas de Inteligência Artificial aplicados à saúde, considerando de forma integrada aspectos técnicos, éticos e regulatórios. O trabalho busca contribuir para o desenvolvimento, avaliação, governança e uso responsável de IA em ambientes de saúde.

Problema de pesquisa

A crescente utilização de Inteligência Artificial na saúde amplia a necessidade de mecanismos capazes de avaliar não apenas o desempenho técnico dos modelos, mas também governança, proteção de dados, segurança e risco clínico, transparência, explicabilidade, robustez, monitoramento e responsabilidade.

Objetivo

Desenvolver e avaliar uma estrutura sistemática para análise de Inteligência Artificial Responsável em Saúde, integrando requisitos técnicos, éticos, regulatórios, de governança, proteção de dados, segurança e risco clínico, transparência, explicabilidade, robustez e monitoramento.

Metodologia

A pesquisa foi estruturada com base em Design Science Research (DSR). O percurso contempla identificação do problema, revisão da literatura e referenciais, definição dos requisitos, desenvolvimento do artefato, aplicação em contexto clínico, análise dos resultados e discussão das limitações e implicações para IA responsável em saúde.

FAC-IA Saúde

O principal artefato da pesquisa é o FAC-IA Saúde — Framework de Avaliação e Conformidade de Inteligência Artificial em Saúde.

O framework é organizado em 5 etapas, 5 domínios e uma tríade de avaliação composta por 3 pilares, com 15 critérios por pilar, totalizando 45 critérios. A avaliação também considera quatro dimensões de risco.

Pilar

Perspectiva

Técnico

desempenho, robustez, segurança, confiabilidade e monitoramento

Ético

equidade, transparência, explicabilidade, responsabilidade e supervisão humana

Regulatório

governança, conformidade, proteção de dados, documentação e responsabilização

Domínios de avaliação

Governança — responsabilidade, gestão, documentação, supervisão e ciclo de vida da IA.

Dados e LGPD — qualidade, procedência, governança, privacidade e proteção dos dados.

Segurança e risco clínico — riscos associados ao uso da IA e potenciais impactos assistenciais.

Transparência e explicabilidade — documentação, compreensão e comunicação do funcionamento e limitações dos modelos.

Robustez e monitoramento — estabilidade, generalização, desempenho e acompanhamento contínuo.

Base empírica — MIMIC-IV v3.1

A etapa empírica utiliza a MIMIC-IV v3.1 — Medical Information Mart for Intensive Care, disponibilizada pelo MIT Laboratory for Computational Physiology por meio do PhysioNet.

Base oficial: https://physionet.org/content/mimiciv/3.1/

População considerada no projeto:

364.627 pacientes;

546.028 internações.

As análises utilizam estruturas do módulo hospitalar (hosp) e tabelas derivadas (derive) da MIMIC-IV.

Os dados originais da MIMIC-IV não são redistribuídos neste repositório. O acesso deve ser realizado diretamente pelo PhysioNet, observando os requisitos de credenciamento, treinamento e uso da base.

Preparação para acesso aos dados

CITI Program — conclusão em 03/07/2025

HIPAA: 97%;

Conflict of Interest (COI): 80%.

Variáveis analisadas

idade;

sexo;

escore SOFA;

sepse, considerando Sepsis-3;

mortalidade hospitalar;

tempo de permanência hospitalar (LOS);

comorbidades;

características clínicas relevantes para estratificação de risco.

Análises desenvolvidas

Foram realizadas caracterização da população, análises de idade e mortalidade, sexo e gravidade clínica, escore SOFA, sepse, comorbidades e escores prognósticos, além da investigação da heterogeneidade de risco entre subgrupos.

Principais achados

As análises indicaram crescimento da mortalidade com o avanço da idade e com maiores níveis de SOFA, diferenças por sexo em cenários de maior gravidade e heterogeneidade de risco entre subgrupos. Esses resultados reforçam a importância de avaliar modelos de IA considerando características clínicas e populacionais, e não apenas métricas agregadas de desempenho.

Inteligência Artificial Responsável em Saúde

A pesquisa contempla governança de IA, equidade, transparência, explicabilidade, supervisão humana, segurança, monitoramento contínuo e proteção de dados como dimensões fundamentais para avaliação responsável de sistemas de IA em saúde.

Referenciais técnicos, éticos e regulatórios

O trabalho considera, entre outros, LGPD, EU AI Act, orientações da OMS, UNESCO e OCDE, NIST AI RMF, ISO/IEC 42001, IEC 62304 e referenciais da FDA relacionados a Software as a Medical Device (SaMD).

Ética em pesquisa

A pesquisa de campo inicialmente planejada foi retirada da dissertação em razão das exigências éticas aplicáveis à coleta com participantes. A coleta com profissionais é tratada separadamente, mediante tramitação ética pertinente, considerando especialmente as Resoluções CNS nº 466/2012 e nº 510/2016.

Produção científica associada

A pesquisa originou frentes relacionadas a:

Heterogeneidade de risco clínico e mortalidade na sepse — implicações para estratificação de risco e IA responsável.

Comorbidades e escores prognósticos na estratificação de risco de pacientes com sepse — análise utilizando a MIMIC-IV v3.1.

FAC-IA Saúde — framework de avaliação, governança e uso responsável de IA em saúde.

Transparência, explicabilidade e supervisão humana — mecanismos para sistemas de IA mais transparentes, compreensíveis, auditáveis e supervisionáveis.

Tecnologias utilizadas

Python;

Pandas;

NumPy;

Matplotlib;

análise estatística;

processamento e preparação de dados clínicos;

Jupyter Notebook;

SQL;

Git e GitHub;

MIMIC-IV / PhysioNet.

Organização sugerida do repositório

Projeto_Pesquisa_PPGIT_UFMG/
├── README.md
├── data/
├── notebooks/
├── scripts/
├── results/
├── figures/
├── docs/
└── references/

Limitações

Os resultados devem ser interpretados considerando a natureza observacional da MIMIC-IV, o contexto clínico e institucional dos dados, limitações inerentes ao uso secundário de registros eletrônicos de saúde, diferenças de representatividade e limites de generalização. Os resultados não constituem recomendações clínicas individuais.

Instituições relacionadas à pesquisa

Universidade Federal de Minas Gerais — UFMG
Programa de Pós-Graduação em Inovação Tecnológica — PPGIT

Departamento de Ciência da Computação — DCC/UFMG

Instituto René Rachou — Fiocruz Minas

Autor

Bruno Martins Bartolomeu

Áreas relacionadas: Inteligência Artificial Responsável, Ciência de Dados, Saúde Digital, Governança de IA, avaliação e conformidade de sistemas de IA e Machine Learning aplicado à saúde.

Referências

Inteligência Artificial, ética, saúde e governança

BRASIL. Lei nº 13.709, de 14 de agosto de 2018. Lei Geral de Proteção de Dados Pessoais (LGPD). Brasília, DF, 2018.

EUROPEAN UNION. Regulation (EU) 2024/1689 of the European Parliament and of the Council laying down harmonised rules on artificial intelligence (Artificial Intelligence Act). Official Journal of the European Union, 2024.

OECD. Recommendation of the Council on Artificial Intelligence. Paris: Organisation for Economic Co-operation and Development, 2019.

UNESCO. Recommendation on the Ethics of Artificial Intelligence. Paris: UNESCO, 2021.

WORLD HEALTH ORGANIZATION. Ethics and governance of artificial intelligence for health: WHO guidance. Geneva: World Health Organization, 2021.

Gestão de risco, conformidade e sistemas de IA

NATIONAL INSTITUTE OF STANDARDS AND TECHNOLOGY. Artificial Intelligence Risk Management Framework (AI RMF 1.0). Gaithersburg: NIST, 2023.

INTERNATIONAL ORGANIZATION FOR STANDARDIZATION; INTERNATIONAL ELECTROTECHNICAL COMMISSION. ISO/IEC 42001:2023 — Information technology — Artificial intelligence — Management system. Geneva: ISO, 2023.

INTERNATIONAL ELECTROTECHNICAL COMMISSION. IEC 62304 — Medical device software — Software life cycle processes. Geneva: IEC.

U.S. FOOD AND DRUG ADMINISTRATION. Software as a Medical Device (SaMD) and Artificial Intelligence/Machine Learning-Enabled Medical Devices. Silver Spring: FDA.

Inteligência Artificial aplicada à medicina

TOPOL, E. J. High-performance medicine: the convergence of human and artificial intelligence. Nature Medicine, v. 25, p. 44–56, 2019.

OBERMEYER, Z.; POWERS, B.; VOGELI, C.; MULLAINATHAN, S. Dissecting racial bias in an algorithm used to manage the health of populations. Science, v. 366, n. 6464, p. 447–453, 2019.

HOLZINGER, A.; LANGS, G.; DENK, H.; ZATLOUKAL, K.; MÜLLER, H. Causability and explainability of artificial intelligence in medicine. WIREs Data Mining and Knowledge Discovery, v. 9, n. 4, 2019.

Interpretabilidade e explicabilidade

LIPTON, Z. C. The mythos of model interpretability. Communications of the ACM, v. 61, n. 10, p. 36–43, 2018.

DOSHI-VELEZ, F.; KIM, B. Towards a rigorous science of interpretable machine learning. 2017.

Ética e bioética

BEAUCHAMP, T. L.; CHILDRESS, J. F. Principles of Biomedical Ethics. 8. ed. New York: Oxford University Press, 2019.

MIMIC-IV e sepse

JOHNSON, A. E. W. et al. MIMIC-IV, a freely accessible electronic health record dataset. Scientific Data, v. 10, 2023.

PHYSIONET. MIMIC-IV v3.1. Disponível em: https://physionet.org/content/mimiciv/3.1/

SINGER, M. et al. The Third International Consensus Definitions for Sepsis and Septic Shock (Sepsis-3). JAMA, v. 315, n. 8, p. 801–810, 2016.

Design Science Research

HEVNER, A. R.; MARCH, S. T.; PARK, J.; RAM, S. Design science in information systems research. MIS Quarterly, v. 28, n. 1, p. 75–105, 2004.

PEFFERS, K.; TUUNANEN, T.; ROTHENBERGER, M. A.; CHATTERJEE, S. A design science research methodology for information systems research. Journal of Management Information Systems, v. 24, n. 3, p. 45–77, 2007.

Ética em pesquisa no Brasil

CONSELHO NACIONAL DE SAÚDE. Resolução nº 466, de 12 de dezembro de 2012. Diretrizes e normas regulamentadoras de pesquisas envolvendo seres humanos.

CONSELHO NACIONAL DE SAÚDE. Resolução nº 510, de 7 de abril de 2016. Normas aplicáveis a pesquisas em Ciências Humanas e Sociais.

Aviso

Este repositório possui finalidade acadêmica e científica. Os resultados, códigos, análises e artefatos devem ser interpretados no contexto da pesquisa e não constituem ferramentas para diagnóstico, prognóstico ou tomada de decisão clínica. O uso da MIMIC-IV deve respeitar integralmente as condições estabelecidas pelo PhysioNet.
