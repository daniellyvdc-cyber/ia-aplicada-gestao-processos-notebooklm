# 🤖 Inteligência Artificial Aplicada à Gestão de Processos

> Projeto desenvolvido para explorar como a Inteligência Artificial pode apoiar a Gestão de Processos de Negócio (BPM), utilizando o NotebookLM como ambiente de estudo, experimentação e consolidação do conhecimento.

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio **“Acelere sua Aprendizagem com IA: Explore o Poder do NotebookLM”**, com o objetivo de utilizar Inteligência Artificial como ferramenta de aprendizagem ativa.

O tema escolhido foi **“Inteligência Artificial aplicada à Gestão de Processos: fundamentos, oportunidades, riscos e aplicações práticas”**.

O estudo foi desenvolvido a partir da curadoria de fontes técnicas e institucionais sobre BPM, modelagem de processos, Inteligência Artificial Generativa e gestão de riscos de IA.

Além da exploração do conteúdo, foram realizados diferentes testes de prompts no NotebookLM. As respostas foram progressivamente estruturadas, auditadas e refinadas, permitindo observar na prática como a qualidade das instruções e a validação das fontes influenciam a confiabilidade das respostas produzidas por IA.

---

## 🎯 Objetivos

### Objetivo Geral

Compreender como a Inteligência Artificial, especialmente os Modelos de Linguagem de Grande Porte (LLMs) e a IA Generativa, pode apoiar as diferentes etapas da Gestão de Processos de Negócio.

### Objetivos Específicos

- Identificar aplicações da IA ao longo do ciclo de Gestão de Processos;
- compreender como a IA pode apoiar descoberta, modelagem, análise, redesenho, implementação e monitoramento de processos;
- identificar benefícios, riscos e limitações relacionados ao uso de IA em BPM;
- diferenciar aplicações de IA de técnicas tradicionais de BPM e Mineração de Processos;
- compreender a importância da supervisão humana e da governança no uso da IA;
- experimentar técnicas de Engenharia de Prompt;
- avaliar criticamente respostas geradas por IA com base nas fontes utilizadas;
- construir um miniguia de estudo e uma biblioteca de prompts reutilizáveis.

---

## 📚 Fontes Utilizadas

Foram selecionadas quatro fontes complementares para construção do notebook:

### 1. Evaluating Large Language Models on Business Process Modeling

**Autores:** Kourani, H.; Berti, A.; Schuster, D.; van der Aalst, W. M. P.  
**Publicação:** Software and Systems Modeling, 2025.

Artigo científico utilizado principalmente para compreender aplicações de LLMs na modelagem de processos, geração de modelos, Engenharia de Prompt, mecanismos de avaliação e estratégias de refinamento e autoaperfeiçoamento.

### 2. Business Process Model and Notation — BPMN 2.0.2

**Instituição:** Object Management Group (OMG).

Especificação utilizada como referência para os fundamentos da modelagem de processos e para compreensão dos principais elementos da BPMN.

### 3. Artificial Intelligence Risk Management Framework — AI RMF 1.0

**Instituição:** National Institute of Standards and Technology (NIST), 2023.

Framework utilizado para incorporar ao estudo aspectos relacionados à governança e gestão de riscos de Inteligência Artificial por meio das funções **GOVERN, MAP, MEASURE e MANAGE**.

### 4. Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile

**Instituição:** National Institute of Standards and Technology (NIST), 2024.

Fonte utilizada para aprofundar riscos específicos relacionados à IA Generativa, incluindo confabulações, segurança, privacidade, supervisão humana e outros aspectos associados ao uso responsável desses sistemas.

---

# 🧪 Testes de Prompts e Processo de Aprendizagem

A experimentação foi realizada de forma iterativa. Cada resposta do NotebookLM foi analisada e utilizada como insumo para construção do prompt seguinte.

O objetivo não foi apenas obter uma resposta final, mas observar como diferentes estratégias de Engenharia de Prompt afetam a **estrutura, profundidade, rastreabilidade e confiabilidade das respostas**.

| Teste | Objetivo | Estratégia | Resultado / Cicatriz | Aprendizado |
|---|---|---|---|---|
| **1. Exploração inicial** | Explorar as aplicações da IA em Gestão de Processos | Pergunta ampla e aberta | Resposta rica em conceitos, porém abrangente e pouco organizada segundo o ciclo de BPM | Prompts genéricos podem gerar conteúdo relevante, mas com menor direcionamento |
| **2. Estruturação** | Relacionar IA às etapas de BPM | Persona de especialista + etapas do processo + critérios + tabela + restrição às fontes | Resposta muito mais estruturada, relacionando aplicação, problema, benefício, risco e supervisão humana | Definir contexto, papel, critérios e formato melhora significativamente a utilidade da resposta |
| **3. Auditoria** | Verificar a confiabilidade da resposta anterior | Persona de auditor + classificação das afirmações segundo seu suporte nas fontes | Foi identificada uma imprecisão na forma como técnicas de Mineração de Processos haviam sido associadas à IA | Uma resposta detalhada e aparentemente correta ainda precisa ser confrontada com as fontes |
| **4. Consolidação** | Transformar o conteúdo validado em material de estudo | Definição de público, estrutura, linguagem e restrições | Geração de um miniguia voltado a profissionais de gestão | A adequação ao público deve fazer parte da Engenharia de Prompt |
| **5. Complementação** | Criar glossário e biblioteca de prompts | Solicitação de conceitos e prompts reutilizáveis | A primeira versão ficou excessivamente técnica e concentrada em aspectos como POWL e geração de código | O formato pode estar correto e ainda não atender adequadamente ao objetivo do usuário |
| **6. Refinamento** | Tornar o material mais útil para profissionais de processos | Redefinição do público, dos conceitos prioritários e das atividades práticas | Glossário ampliado e biblioteca com 8 prompts orientados ao trabalho de Gestão de Processos | Refinar uma resposta também significa avaliar sua utilidade prática, e não apenas sua correção técnica |

## 🩹 Principal “Cicatriz” do Experimento

Um dos principais aprendizados surgiu no **Teste 3**.

Na resposta anterior, técnicas como **Conformance Checking, Fitness e Precision** haviam sido apresentadas de forma que poderiam ser interpretadas como aplicações diretas de IA.

A auditoria das fontes mostrou que essas técnicas pertencem à **Mineração de Processos tradicional**. Elas podem ser utilizadas para analisar processos e para avaliar modelos produzidos com apoio de IA, mas não devem ser classificadas como algoritmos de IA Generativa.

Esse resultado demonstrou um ponto importante:

> **Uma resposta de IA pode ser detalhada, tecnicamente convincente e ainda conter enquadramentos conceituais que precisam ser verificados nas fontes.**

A partir dessa identificação, os prompts seguintes passaram a exigir explicitamente a diferenciação entre aplicações de IA, técnicas tradicionais de BPM e Mineração de Processos.

---

# 📖 Miniguia de Estudo

## 1. O que é IA aplicada à Gestão de Processos?

A Gestão de Processos de Negócio (BPM) utiliza modelos de processos para documentar, compreender, analisar e otimizar fluxos de trabalho organizacionais.

Tradicionalmente, a construção e manutenção desses modelos exige esforço manual e conhecimento especializado em linguagens de modelagem, como BPMN.

A Inteligência Artificial, especialmente por meio de **LLMs e IA Generativa**, pode atuar como uma ponte entre informações apresentadas em linguagem natural — como procedimentos, manuais, normas e entrevistas — e representações estruturadas de processos.

Isso permite utilizar IA como apoio em diferentes momentos do ciclo de Gestão de Processos.

---

## 2. Como a IA pode apoiar a Gestão de Processos?

### 🔎 Descoberta e Levantamento

A IA pode processar documentos, procedimentos e transcrições de entrevistas para identificar atividades, decisões e relacionamentos existentes no processo.

Isso pode apoiar o profissional durante o levantamento inicial e a organização de informações que posteriormente precisarão ser validadas com os especialistas do processo.

### 🗺️ Modelagem

LLMs podem apoiar a transformação de descrições textuais em representações estruturadas de processos.

Frameworks especializados podem utilizar representações intermediárias, como **POWL (Partially Ordered Workflow Language)**, para reduzir problemas estruturais antes da conversão para outras notações.

A IA, entretanto, não elimina a necessidade de validação do modelo pelo profissional responsável pelo processo.

### 🔍 Análise

A IA pode facilitar consultas e interpretações de modelos de processos utilizando linguagem natural.

É importante distinguir esse uso de técnicas tradicionais de **Mineração de Processos**, como *Conformance Checking*, *Fitness* e *Precision*.

Essas técnicas não são algoritmos de IA Generativa. Elas podem, entretanto, funcionar como mecanismos de análise e validação de processos e de modelos produzidos com apoio de IA.

### 🔄 Redesenho e Melhoria

A IA pode apoiar processos de melhoria por meio de ciclos de feedback e refinamento.

Uma estratégia identificada nas fontes é a **Output Optimization**, na qual o modelo é orientado a revisar e melhorar diretamente a saída anteriormente produzida.

Esse processo deve ser acompanhado pelo profissional responsável, principalmente para evitar alterações indevidas em regras de negócio.

### 📊 Implementação e Monitoramento

Modelos especializados podem analisar registros de execução e logs de sistemas para apoiar classificação de atividades, previsão de próximas atividades e identificação de anomalias.

Nessa etapa, mecanismos de governança tornam-se especialmente relevantes para acompanhar o comportamento da IA e identificar possíveis desvios, falhas ou riscos.

---

## 3. Principais Benefícios

Entre os benefícios identificados no estudo estão:

- maior facilidade para transformar linguagem natural em representações estruturadas de processos;
- redução do esforço manual na construção de rascunhos e levantamentos iniciais;
- apoio à análise e interpretação de processos;
- possibilidade de refinamento iterativo dos modelos;
- apoio à detecção de anomalias e ao monitoramento;
- maior acessibilidade das atividades de modelagem para profissionais de negócio.

---

## 4. Principais Riscos e Limitações

A utilização de IA em Gestão de Processos também apresenta riscos relevantes:

- **Alucinações ou confabulações:** criação de informações, etapas ou relações inexistentes;
- **alterações semânticas:** modificações que podem alterar inadvertidamente uma regra de negócio;
- **viés de automação:** tendência de confiar excessivamente nas respostas produzidas pela tecnologia;
- **opacidade:** dificuldade de compreender como determinados resultados foram produzidos;
- **segurança e privacidade:** possibilidade de exposição de dados ou exploração de vulnerabilidades como *prompt injection*;
- **dependência da qualidade das entradas:** documentos incompletos ou ambíguos podem afetar a qualidade da análise.

---

## 5. A importância da Supervisão Humana

A IA deve atuar como ferramenta de apoio ao profissional de processos, e não como substituta do julgamento especializado.

A supervisão humana é necessária para:

- validar se o resultado representa corretamente a realidade do processo;
- interpretar aspectos qualitativos e regras de negócio;
- identificar informações inventadas ou inferências inadequadas;
- revisar alterações propostas pela IA;
- intervir ou interromper o uso do sistema quando necessário.

A interação entre humanos e IA deve, portanto, estabelecer claramente papéis, responsabilidades e mecanismos de supervisão.

---

## 6. Cinco Boas Práticas para Uso Responsável da IA em Processos

### 1. Definir governança e responsabilidades

Estabelecer claramente os papéis dos profissionais e das ferramentas de IA, incluindo limites de utilização e responsabilidades pela validação.

### 2. Utilizar mecanismos de validação

Quando aplicável, combinar modelos gerados por IA com técnicas de análise e validação de processos.

### 3. Manter supervisão humana

Resultados gerados automaticamente devem ser analisados por profissionais que conheçam o processo e suas regras de negócio.

### 4. Utilizar Engenharia de Prompt estruturada

Definir claramente persona, contexto, objetivo, fontes, restrições e formato esperado da resposta.

### 5. Garantir rastreabilidade e proteção das informações

As organizações devem conhecer a origem dos dados utilizados, proteger informações pessoais ou confidenciais e monitorar riscos relacionados ao uso de IA.

---

# 📘 Glossário

| Conceito | Definição |
|---|---|
| **BPM** | Gestão de Processos de Negócio. Disciplina voltada à compreensão, documentação, análise e melhoria dos processos organizacionais. |
| **BPMN** | Padrão gráfico mantido pela OMG para representação visual de processos de negócio. |
| **IA Generativa** | Classe de modelos de IA capaz de gerar novos conteúdos a partir dos padrões aprendidos nos dados. |
| **LLM** | Modelo de Linguagem de Grande Porte treinado em grandes volumes de dados textuais e utilizado para tarefas relacionadas à linguagem natural. |
| **Process Discovery** | Descoberta e construção de representações de processos a partir de dados, documentos ou outras informações sobre sua execução. |
| **Process Mining** | Disciplina que utiliza dados registrados nos sistemas para analisar a execução real dos processos. |
| **Event Log** | Registro de eventos relacionados à execução de um processo, normalmente contendo caso, atividade e momento da execução. |
| **Conformance Checking** | Técnica de Mineração de Processos que compara o comportamento registrado com um modelo de referência. |
| **Fitness** | Métrica que avalia quanto do comportamento observado pode ser reproduzido pelo modelo. |
| **Precision** | Métrica relacionada à capacidade do modelo de evitar comportamentos que não foram observados. |
| **Soundness** | Propriedade estrutural relacionada à corretude lógica de um modelo de processo. |
| **POWL** | Linguagem de modelagem utilizada como representação intermediária e capaz de garantir *soundness* por construção. |
| **Prompt Engineering** | Estruturação de instruções, contexto, exemplos e restrições para orientar o comportamento de modelos de IA. |
| **Human-AI Configuration** | Distribuição estruturada de papéis e responsabilidades entre pessoas e sistemas de IA. |
| **Automation Bias** | Tendência humana de confiar excessivamente em resultados produzidos por sistemas automatizados. |
| **Alucinação / Confabulação** | Geração de informações plausíveis, porém incorretas ou não sustentadas pelas fontes. |
| **Prompt Injection** | Manipulação das instruções de um sistema de IA por meio da inserção de comandos maliciosos. |
| **NIST AI RMF** | Framework do NIST para governança e gerenciamento de riscos relacionados à Inteligência Artificial. |

---

# 💬 Biblioteca de Prompts Reutilizáveis

## Prompt 1 — Descoberta e Levantamento de Processo

```text
Atue como especialista em Gestão de Processos de Negócio (BPM).

Sua tarefa é realizar a descoberta e o levantamento do processo [PROCESSO] a partir da documentação fornecida em [DOCUMENTOS/FONTES], considerando o contexto [CONTEXTO].

Diretrizes:
1. Utilize prioritariamente as informações contidas nas fontes.
2. Diferencie fatos declarados nas fontes de inferências ou sugestões.
3. Não apresente como fato informações não sustentadas pelas fontes.
4. Indique quando não houver informação suficiente para determinar uma etapa ou regra de negócio.

Apresente:
- objetivo do processo;
- descrição cronológica das etapas;
- lacunas ou ambiguidades que precisam ser validadas.
```

## Prompt 2 — Atividades, Atores, Entradas, Saídas e Decisões

```text
Atue como analista de processos experiente.

Analise a documentação do processo [PROCESSO] contida em [DOCUMENTOS/FONTES], considerando [CONTEXTO].

Extraia apenas elementos sustentados pelas fontes e diferencie fatos de inferências.

Estruture:
1. atores/papéis;
2. atividades/tarefas;
3. entradas;
4. saídas;
5. pontos de decisão e regras de negócio.

Quando uma informação não estiver disponível, registre "Informação não constante na fonte".
```

## Prompt 3 — Estruturação e Modelagem Conceitual

```text
Atue como modelador de processos sênior especializado em BPMN 2.0.

Com base em [DOCUMENTOS/FONTES], elabore uma especificação estruturada do processo [PROCESSO], considerando [OBJETIVO] e [CONTEXTO].

Mantenha fidelidade às fontes.

Identifique:
- eventos de início, intermediários e de fim;
- atividades;
- sequência do fluxo;
- gateways XOR, AND ou OR, quando sustentados pelas informações disponíveis;
- lacunas que impeçam o fechamento do fluxo.

Apresente a especificação em tópicos hierárquicos para posterior modelagem.
```

## Prompt 4 — Gargalos e Oportunidades de Melhoria

```text
Atue como consultor de eficiência operacional e BPM.

Analise o processo [PROCESSO], descrito em [DOCUMENTOS/FONTES], considerando [OBJETIVO] e [CONTEXTO].

Identifique possíveis:
- gargalos;
- esperas;
- retrabalhos;
- redundâncias;
- atividades sem agregação de valor.

Classifique cada achado como:
- FATO COMPROVADO NAS FONTES; ou
- INFERÊNCIA ANALÍTICA.

Quando não existirem métricas suficientes para uma conclusão, indique explicitamente essa limitação.
```

## Prompt 5 — Riscos e Controles

```text
Atue como especialista em Governança, Riscos e Conformidade em Processos.

Avalie o processo [PROCESSO] com base em [DOCUMENTOS/FONTES] e [CONTEXTO].

Identifique riscos operacionais, de conformidade ou de integridade de dados associados às etapas descritas.

Diferencie:
- falhas ou incidentes efetivamente relatados nas fontes;
- riscos potenciais identificados por inferência.

Apresente em tabela:

Etapa do Processo | Risco | Fato/Inferência | Impacto Potencial | Possível Controle/Salvaguarda

Indique quando não houver informações suficientes para avaliar probabilidade ou severidade.
```

## Prompt 6 — Redesenho do Processo To-Be

```text
Atue como arquiteto de processos de negócio.

Elabore uma proposta de redesenho To-Be para [PROCESSO], utilizando [DOCUMENTOS/FONTES] e considerando [OBJETIVO] e [CONTEXTO].

Preserve os requisitos de negócio sustentados pelas fontes.

Avalie oportunidades de:
- eliminar redundâncias;
- simplificar atividades;
- automatizar tarefas repetitivas;
- reorganizar ou paralelizar atividades quando viável.

Diferencie claramente:
- MANUTENÇÃO DAS REGRAS ATUAIS (FATO);
- INOVAÇÃO PROPOSTA NO REDESENHO (SUGESTÃO/INFERÊNCIA).
```

## Prompt 7 — Revisão Crítica de uma Resposta de IA

```text
Atue como auditor sênior da qualidade de processos de negócio.

Revise criticamente a análise abaixo sobre [PROCESSO], comparando-a com [DOCUMENTOS/FONTES].

[ANÁLISE A SER REVISADA]
<Inserir conteúdo>

Avalie:
1. precisão e completude;
2. omissão de atividades ou decisões;
3. existência de afirmações sem sustentação;
4. coerência da lógica do fluxo.

Apresente:
- inconsistências identificadas;
- informações não sustentadas;
- omissões relevantes;
- versão corrigida da análise.
```

## Prompt 8 — Validação de Aderência às Fontes

```text
Atue como auditor da qualidade da informação e rastreabilidade documental.

Compare a resposta abaixo com [DOCUMENTOS/FONTES] referentes a [PROCESSO].

[RESPOSTA A SER VALIDADA]
<Inserir conteúdo>

Classifique cada afirmação relevante como:

[SUSTENTADO] — diretamente confirmada pelas fontes;
[INFERÊNCIA] — dedução razoável, mas não explicitamente declarada;
[NÃO SUSTENTADO/ALUCINAÇÃO] — afirmação sem respaldo nas fontes.

Indique também:
- a evidência utilizada;
- omissões relevantes;
- informações que não podem ser validadas por insuficiência das fontes.
```

---

# 💡 Principais Aprendizados

O desenvolvimento deste projeto mostrou que utilizar IA para aprender não significa apenas formular perguntas e aceitar as respostas produzidas.

A experimentação evidenciou alguns princípios importantes:

1. **A qualidade do prompt influencia diretamente a qualidade da resposta.** Persona, contexto, objetivo, critérios, fontes e formato de saída ajudam a tornar a resposta mais útil.

2. **Mais detalhes não significam necessariamente mais confiabilidade.** Respostas tecnicamente sofisticadas também podem conter associações conceituais inadequadas.

3. **A validação contra as fontes é indispensável.** O teste de auditoria foi fundamental para distinguir aplicações de IA de técnicas tradicionais de Mineração de Processos.

4. **Fatos e inferências devem ser separados.** Essa distinção tornou-se um dos principais critérios dos prompts desenvolvidos ao longo do projeto.

5. **O refinamento faz parte da Engenharia de Prompt.** Quando o primeiro glossário e a primeira biblioteca de prompts ficaram excessivamente técnicos, um novo prompt foi utilizado para adequar o resultado ao público e ao objetivo do estudo.

6. **A supervisão humana continua essencial.** A IA pode acelerar levantamento, organização, análise e redesenho de processos, mas a validação das regras de negócio e das decisões permanece sob responsabilidade dos profissionais envolvidos.

---

# 🛠️ Ferramentas Utilizadas

- **NotebookLM** — estudo das fontes, experimentação e consolidação do conhecimento;
- **GitHub** — documentação e publicação do projeto;
- **Markdown** — estruturação do README.

---

# 📚 Referências

**KOURANI, H.; BERTI, A.; SCHUSTER, D.; VAN DER AALST, W. M. P.** Evaluating large language models on business process modeling: framework, benchmark, and self-improvement analysis. *Software and Systems Modeling*, 2025.

**NATIONAL INSTITUTE OF STANDARDS AND TECHNOLOGY (NIST).** *Artificial Intelligence Risk Management Framework (AI RMF 1.0).* NIST AI 100-1, 2023.

**NATIONAL INSTITUTE OF STANDARDS AND TECHNOLOGY (NIST).** *Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile.* NIST AI 600-1, 2024.

**OBJECT MANAGEMENT GROUP (OMG).** *Business Process Model and Notation (BPMN), Version 2.0.2.* 2013.

---

## 🚀 Resultado

Como resultado, o projeto consolidou um material de estudo sobre **IA aplicada à Gestão de Processos** e, simultaneamente, registrou uma experiência prática de Engenharia de Prompt, validação de fontes e refinamento iterativo de respostas produzidas por Inteligência Artificial.

Mais do que utilizar IA para gerar conteúdo, o exercício demonstrou a importância de **formular, testar, questionar, validar e refinar** as respostas obtidas.
