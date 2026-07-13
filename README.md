# Inteligencia-Artificial-na-Analise-de-dados
Miniguia de estudos desenvolvido com NotebookLM sobre Inteligência Artificial aplicada à Análise de Dados e Business Intelligence.

# Inteligência Artificial na Análise de Dados e Business Intelligence com NotebookLM

## Sobre o projeto

Este projeto foi desenvolvido como parte do desafio prático da DIO utilizando o Google NotebookLM como ferramenta de aprendizagem ativa.

O objetivo foi estudar como a Inteligência Artificial está transformando a Análise de Dados e o Business Intelligence (BI), identificando suas principais aplicações, oportunidades, limitações e tendências a partir de fontes acadêmicas e técnicas.

Além do estudo do tema, o projeto também teve como foco a aplicação de diferentes técnicas de Engenharia de Prompts para compreender como pequenas alterações na estrutura dos prompts influenciam diretamente a qualidade das respostas produzidas pelo NotebookLM.

---

# Objetivos

- Estudar aplicações da Inteligência Artificial na Análise de Dados e no Business Intelligence.
- Desenvolver um processo de aprendizagem baseado em curadoria de fontes.
- Experimentar diferentes técnicas de Engenharia de Prompts.
- Construir um miniguia de estudos para futuras revisões.
- Documentar dificuldades encontradas e aprendizados obtidos durante o processo.

---

# Fontes utilizadas

As seguintes fontes abertas foram carregadas no NotebookLM para compor a base de conhecimento do projeto:

- Gartner Magic Quadrant for Analytics and Business Intelligence Platforms (2026)
- Opportunities and Challenges for AI-supported Business Intelligence Systems – A Delphi Study
- The Role of Inquiry in AI-powered Data Analysis (Observable)
- The Impact of Artificial Intelligence on Research Efficiency
- Inteligência Artificial e Ensino Superior em Contabilidade: Impactos, Desafios e Potencialidades

---

# Engenharia de Prompts

Durante o desenvolvimento foram realizados diversos testes para avaliar como diferentes estratégias de construção de prompts afetam a qualidade das respostas produzidas pelo NotebookLM.

## Prompt 1 — Prompt Inicial

**Objetivo**

Obter uma visão geral sobre as aplicações da IA em Business Intelligence.

**Prompt**

```
Quais são as principais aplicações da Inteligência Artificial na Análise de Dados e no Business Intelligence?
```

### Resultado observado

O NotebookLM apresentou uma visão geral consistente sobre o tema, porém com respostas bastante amplas e pouca comparação entre as fontes carregadas.

### Aprendizado

Prompts muito genéricos tendem a produzir respostas corretas, porém pouco aprofundadas.

---

## Prompt 2 — Instruções Claras

Foi definido um papel para o modelo e restringido o uso apenas das fontes carregadas.

### Aprendizado

As respostas tornaram-se mais organizadas e aderentes ao material estudado.

---

## Prompt 3 — Estrutura de Saída

Foi solicitado que a resposta fosse organizada em:

- Aplicações
- Benefícios
- Limitações
- Tendências
- Conclusão

### Aprendizado

A organização da saída tornou a leitura mais clara e facilitou a comparação entre os diferentes aspectos do tema.

---

## Prompt 4 — Divisão da Tarefa

O problema foi dividido em etapas menores:

- identificar aplicações;
- agrupar aplicações semelhantes;
- identificar benefícios;
- identificar limitações;
- produzir uma conclusão.

### Aprendizado

A divisão da tarefa aumentou significativamente a profundidade da análise.

---

## Prompt 5 — Guardrails

Foram adicionadas restrições para que o NotebookLM utilizasse exclusivamente as fontes carregadas e informasse quando determinada informação não estivesse disponível.

### Aprendizado

As respostas passaram a apresentar maior confiabilidade e reduziram extrapolações desnecessárias.

---

## Prompt 6 — Comparação entre Fontes

Foi solicitado que o NotebookLM comparasse todas as fontes, destacando:

- principais ideias;
- contribuições;
- limitações;
- diferenças entre os autores.

### Aprendizado

Esse foi o prompt que gerou os resultados mais completos, permitindo identificar convergências e divergências entre diferentes perspectivas sobre IA aplicada ao BI.

---

# Principais Cicatrizes

Durante os testes foi possível perceber que:

| Dificuldade encontrada | Ajuste realizado | Resultado |
|------------------------|------------------|-----------|
| Respostas muito genéricas | Inclusão de contexto | Respostas mais específicas |
| Pouca organização | Estrutura de saída | Melhor legibilidade |
| Pouca profundidade | Divisão da tarefa | Análises mais completas |
| Informações além das fontes | Restrição às fontes | Maior confiabilidade |
| Pouca comparação | Prompt comparativo | Melhor compreensão do tema |

---

# Miniguia de Estudos

## Principais aplicações da IA

- Preparação e limpeza automatizada de dados;
- Analytics conversacional;
- Analytics agêntico;
- Descoberta automática de padrões;
- Modelagem preditiva;
- Dashboards inteligentes;
- Geração automática de narrativas;
- Embedded Analytics;
- Automação de auditorias;
- Apoio à pesquisa científica.

---

## Benefícios

- Maior produtividade;
- Redução do tempo de análise;
- Democratização do acesso aos dados;
- Apoio à tomada de decisão;
- Automação de tarefas repetitivas;
- Melhor aproveitamento de grandes volumes de dados.

---

## Limitações

- Dependência da qualidade dos dados;
- Possibilidade de vieses algorítmicos;
- Alucinações em modelos generativos;
- Necessidade de supervisão humana;
- Questões éticas e de privacidade.

---

## Tendências

- Analytics Agêntico;
- IA Generativa integrada ao BI;
- Camadas semânticas;
- Interfaces conversacionais;
- Automação de fluxos analíticos.

---

# Glossário

**Business Intelligence (BI)**  
Conjunto de processos e tecnologias utilizados para transformar dados em informações úteis para tomada de decisão.

**Analytics Agêntico**  
Modelo em que agentes de IA executam tarefas analíticas de forma autônoma ou semiautônoma.

**IA Generativa**  
Modelos capazes de gerar textos, códigos, imagens e outros conteúdos a partir de comandos em linguagem natural.

**Governança de Dados**  
Conjunto de práticas responsáveis por garantir qualidade, segurança e consistência dos dados.

**Camada Semântica**  
Estrutura que padroniza métricas e conceitos utilizados em análises.

**Storytelling de Dados**  
Uso de narrativas para explicar informações obtidas por meio da análise de dados.

**NLP (Processamento de Linguagem Natural)**  
Área da IA voltada para compreensão e geração de linguagem humana.

---

# Prompts reutilizáveis

### Resumo Estruturado

```
Analise exclusivamente as fontes carregadas.

Explique o tema utilizando a seguinte estrutura:

- Introdução
- Principais conceitos
- Benefícios
- Limitações
- Conclusão

Ao final cite as fontes utilizadas.
```

---

### Comparação de Fontes

```
Compare todas as fontes carregadas.

Identifique:

- principais ideias;
- convergências;
- divergências;
- limitações.

Ao final produza uma síntese crítica.
```

---

### Glossário

```
Crie um glossário contendo os principais conceitos encontrados nas fontes.

Explique cada conceito em até duas linhas.
```

---

# Conclusão

O desenvolvimento deste projeto demonstrou que o NotebookLM pode ser utilizado como uma ferramenta de aprendizagem ativa, indo além da simples geração de resumos.

A experiência evidenciou que a qualidade das respostas depende diretamente da construção dos prompts. Técnicas como definição de contexto, estruturação da saída, restrições e divisão da tarefa produziram respostas mais organizadas, consistentes e úteis para o estudo do tema.

Mais do que aprender sobre Inteligência Artificial aplicada ao Business Intelligence, este projeto permitiu compreender, na prática, como a Engenharia de Prompts influencia a interação com modelos de IA e potencializa o processo de aprendizagem.

Tecnologias Utilizadas :

Google NotebookLM
Inteligência Artificial Generativa
Engenharia de Prompts
Markdown
GitHub
