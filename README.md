 Inteligência Artificial na Análise de Dados e Business Intelligence com NotebookLM

Sobre o projeto

Este projeto foi desenvolvido durante o Bootcamp Bradesco - Java Cloud Native em parceria com a DIO, utilizando o Google NotebookLM como ferramenta de aprendizagem ativa.

Escolhi estudar Inteligência Artificial aplicada à Análise de Dados e ao Business Intelligence porque atualmente estou direcionando minha carreira para a área de Dados. Meu objetivo não era apenas entender as aplicações da IA, mas também experimentar como diferentes formas de construir prompts influenciam a qualidade das respostas produzidas pela ferramenta.

Ao invés de utilizar o NotebookLM apenas para resumir documentos, procurei utilizá-lo como um ambiente de estudo, testando diferentes estratégias de Engenharia de Prompts, comparando respostas e registrando os aprendizados obtidos durante o processo.



 Objetivos

Durante este projeto busquei:

- compreender como a IA vem sendo utilizada em Business Intelligence e Análise de Dados;
- identificar benefícios, limitações e tendências observadas nas fontes estudadas;
- aprender a construir prompts mais eficientes;
- criar um material que possa servir como guia de revisão no futuro.


## Fontes utilizadas

Para montar o caderno no NotebookLM foram utilizadas cinco fontes abertas relacionadas ao tema.

- Gartner Magic Quadrant for Analytics and Business Intelligence Platforms (2026)
- Opportunities and Challenges for AI-supported Business Intelligence Systems – A Delphi Study
- The Role of Inquiry in AI-powered Data Analysis (Observable)
- The Impact of Artificial Intelligence on Research Efficiency
- Inteligência Artificial e Ensino Superior em Contabilidade: Impactos, Desafios e Potencialidades

A escolha das fontes buscou reunir perspectivas diferentes sobre o tema, combinando estudos acadêmicos, pesquisas de mercado e aplicações práticas.

## Como conduzi o estudo

Depois de carregar as fontes no NotebookLM, preferi não pedir imediatamente um resumo completo. Resolvi começar com perguntas simples para entender como a ferramenta responderia utilizando apenas o material disponível.

O primeiro prompt utilizado foi:

"Quais são as principais aplicações da Inteligência Artificial na Análise de Dados e no Business Intelligence?"

A resposta foi satisfatória para uma visão geral, mas ainda bastante ampla. Os conceitos principais apareceram corretamente, porém senti falta de uma organização melhor e de uma comparação entre os diferentes documentos.

A partir desse resultado comecei a modificar a forma de escrever os prompts.

Primeiro defini um contexto para o modelo, informando que ele deveria atuar como especialista em Business Intelligence e utilizar exclusivamente as fontes carregadas no NotebookLM. A resposta ficou mais consistente e aderente ao material utilizado.

Depois experimentei pedir uma estrutura fixa para a resposta, separando aplicações, benefícios, limitações, tendências e conclusão. Essa pequena mudança tornou o conteúdo muito mais fácil de compreender.

Na etapa seguinte resolvi dividir o problema em partes menores, solicitando primeiro a identificação das aplicações, depois o agrupamento por categorias, em seguida os benefícios, limitações e somente ao final uma conclusão geral. Esse foi o teste que apresentou os resultados mais completos.

Também utilizei restrições (guardrails), orientando o NotebookLM a utilizar apenas as informações presentes nas fontes e informar explicitamente quando determinado assunto não estivesse documentado. Essa estratégia reduziu respostas especulativas e aumentou a confiabilidade das informações.

Por fim, pedi uma comparação entre todas as fontes carregadas. Esse foi, na minha opinião, o experimento mais interessante do projeto, pois permitiu identificar pontos de convergência, divergências e diferentes perspectivas sobre o uso da IA em Business Intelligence.

## O que aprendi durante os testes

A principal conclusão foi que a qualidade das respostas depende muito mais da construção do prompt do que da quantidade de documentos utilizados.

Durante os testes observei que:

- prompts muito genéricos produzem respostas corretas, porém superficiais;
- definir claramente o contexto melhora significativamente a qualidade das respostas;
- solicitar uma estrutura de saída facilita a leitura e organização das informações;
- dividir problemas complexos em etapas produz análises mais completas;
- limitar o modelo às fontes carregadas reduz extrapolações desnecessárias;
- comparar documentos diferentes ajuda a identificar consensos e pontos de divergência.

## Miniguia de estudos

A partir das respostas obtidas foi possível consolidar alguns pontos principais.

A Inteligência Artificial já está presente em praticamente todas as etapas do ciclo analítico, desde a preparação dos dados até a geração automática de insights. Entre as aplicações mais recorrentes encontradas nas fontes estão a limpeza automatizada de dados, analytics conversacional, analytics agêntico, análise preditiva, geração de dashboards inteligentes e criação automática de narrativas.

Entre os benefícios mais citados destacam-se o aumento da produtividade, a redução do tempo necessário para análise de grandes volumes de dados, a democratização do acesso às informações e o apoio à tomada de decisão.

Ao mesmo tempo, todas as fontes chamam atenção para limitações importantes, principalmente relacionadas à qualidade dos dados utilizados, vieses algorítmicos, alucinações em modelos generativos, privacidade e necessidade de supervisão humana.

Outro aspecto recorrente foi a tendência de evolução das plataformas de Business Intelligence para modelos cada vez mais orientados por IA, incorporando agentes inteligentes, interfaces em linguagem natural e camadas semânticas capazes de melhorar a governança dos dados.


 Glossário

**Business Intelligence (BI):** conjunto de processos e ferramentas utilizados para transformar dados em informações úteis para tomada de decisão.

**Analytics Agêntico:** utilização de agentes de IA capazes de executar tarefas analíticas de forma autônoma ou semiautônoma.

**IA Generativa:** modelos capazes de produzir textos, códigos, imagens e outros conteúdos a partir de comandos em linguagem natural.

**Governança de Dados:** conjunto de práticas responsáveis por garantir qualidade, segurança e consistência dos dados utilizados por uma organização.

**Storytelling de Dados:** técnica de comunicação que utiliza narrativas para explicar resultados obtidos durante análises.


 Prompts que pretendo reutilizar

Alguns prompts se mostraram especialmente úteis durante o desenvolvimento e certamente serão reaproveitados em estudos futuros.

- Comparar diferentes fontes sobre um mesmo tema.
- Produzir resumos estruturados utilizando apenas os documentos carregados.
- Construir glossários automaticamente.
- Identificar convergências e divergências entre autores.
- Organizar conteúdos em níveis crescente de complexidade para revisão.

Considerações finais

Mais do que estudar Inteligência Artificial aplicada ao Business Intelligence, este projeto me permitiu compreender como a Engenharia de Prompts influencia diretamente a qualidade das respostas produzidas por modelos de IA.

Também ficou evidente que ferramentas como o NotebookLM podem ser utilizadas como instrumentos de aprendizagem ativa, auxiliando não apenas na síntese de conteúdos, mas também na organização do conhecimento e no desenvolvimento de um processo de estudo mais estruturado.
