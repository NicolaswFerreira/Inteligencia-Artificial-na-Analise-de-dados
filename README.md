Inteligência Artificial na Análise de Dados e Business Intelligence com NotebookLM

Sobre o projeto

Esse projeto foi desenvolvido durante o Bootcamp Bradesco - Java Cloud Native em parceria com a DIO, usando o Google NotebookLM como ferramenta de aprendizagem ativa.

Escolhi estudar Inteligência Artificial aplicada à Análise de Dados e ao Business Intelligence porque atualmente estou direcionando minha carreira para a área de Dados. Meu objetivo não somente entender as aplicações da IA, mas também experimentar como diferentes formas de construir prompts influenciam a qualidade das respostas produzidas pela ferramenta.

No lugaar de usar o NotebookLM só para resumir documentos, usei ele como um ambiente de estudo, testando diferentes estratégias de Engenharia de Prompts, comparando respostas e registrando os aprendizados obtidos durante o processo.

Objetivos

Durante esse projeto eu procuerei:

- compreender como a IA vem sendo utilizada em Business Intelligence e Análise de Dados;
- identificar benefícios, limitações e tendências observadas nas fontes estudadas;
- aprender a construir prompts mais eficientes;
- criar um material que possa servir como guia de revisão no futuro.

Fontes utilizadas para montar o caderno no NotebookLM foram utilizadas cinco fontes abertas relacionadas ao tema.

- Gartner Magic Quadrant for Analytics and Business Intelligence Platforms (2026)
- Opportunities and Challenges for AI-supported Business Intelligence Systems – A Delphi Study
- The Role of Inquiry in AI-powered Data Analysis (Observable)
- The Impact of Artificial Intelligence on Research Efficiency
- Inteligência Artificial e Ensino Superior em Contabilidade: Impactos, Desafios e Potencialidades

A escolha das fontes buscou reunir perspectivas diferentes sobre o tema, combinando estudos acadêmicos, pesquisas de mercado e aplicações práticas.

Como conduzi o estudo :

Depois de carregar as fontes no NotebookLM, preferi não pedir imediatamente um resumo completo. Resolvi começar com perguntas simples para entender como a ferramenta responderia usando somente o material disponível.

O primeiro prompt foi:

"Quais são as principais aplicações da Inteligência Artificial na Análise de Dados e no Business Intelligence?"

A resposta foi boa para uma visão geral, mas ainda sim bastante ampla, os conceitos principais apareceram corretamente, mas eu acabei sentindo falta de uma organização melhor e de uma comparação entre os diferentes documentos.

A partir dai comecei a mudar a forma de escrever os prompts, defini um contexto para o modelo, dizendo que ele deveria atuar como especialista em Business Intelligence e utilizar exclusivamente as fontes carregadas no NotebookLM, a resposta ficou mais consistente e aderente ao material utilizado.

Depois pedi uma estrutura fixa para a resposta, separando aplicações, benefícios, limitações, tendências e conclusão. Essa mudança deixou o conteúdo muito mais fácil de compreender.

Na etapa seguinte dividi o problema em partes menores, solicitando primeiro a identificação das aplicações, depois o agrupamento por categorias, em seguida os benefícios, limitações e somente ao final uma conclusão geral. Esse foi o teste que apresentou os resultados mais completos.

Também usei restrições (guardrails), orientando o NotebookLM a utilizar somente as informações presentes nas fontes e informar explicitamente quando determinado assunto não estivesse documentado. Essa estratégia reduziu respostas especulativas e aumentou a confiabilidade das informações.

Por fim, pedi uma comparação entre todas as fontes carregadas. Esse na minha opinião foi o experimento mais interessante do projeto ele permitiu com que eu conseguisse identificar pontos de convergência, divergências e diferentes perspectivas sobre o uso da IA em Business Intelligence.

A principal conclusão foi que a qualidade das respostas depende muito mais da construção do prompt do que da quantidade de documentos utilizados.

Durante os testes consegui notar :

- prompts muito genéricos produzem respostas corretas, porém superficiais;
- definir claramente o contexto melhora significativamente a qualidade das respostas;
- solicitar uma estrutura de saída facilita a leitura e organização das informações;
- dividir problemas complexos em etapas produz análises mais completas;
- limitar o modelo às fontes carregadas reduz extrapolações desnecessárias;
- comparar documentos diferentes ajuda a identificar consensos e pontos de divergência.

Miniguia de estudos

A partir dessas respostas foi possível consolidar alguns pontos principais.

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

Considerações finais

Esse projeto aumento muito a minha compreensão sobre o cenário atual da Inteligência Artificial aplicada à Análise de Dados e ao Business Intelligence. Durante a leitura das fontes e os experimentos realizados no NotebookLM, percebi que grande parte das discussões sobre o mercado de tecnologia gira em torno da automação e do impacto da IA sobre as nossas profissões. Um ponto em comum entre os materiais analisados é que a IA vem transformando a forma como os profissionais trabalham, o que pro bem ou pro mal exige adaptação contínua e o desenvolvimento de novas competências, em vez de simplesmente substituir funções.

Outro aprendizado importante foi entender que a qualidade dos resultados produzidos por uma IA depende diretamente da qualidade dos dados e da forma como interagimos com o modelo. Ao testar diferentes técnicas de engenharia de prompts, ficou evidente que pequenas mudanças na estrutura das instruções podem produzir respostas significativamente mais completas, organizadas e úteis.

No meu projeto anterior voltado a  Inteligência Artificial, eu já tinha visto que um dos desafios na construção de assistentes inteligentes não é o modelo de IA, mas principalmente na organização, limpeza e confiabilidade da base de conhecimento utilizada. Na construção desse novo projeto com o NotebookLM essa percepção ficou ainda mais clara: uma boa base de dados e uma boa engenharia de prompts são fatores tão importantes quanto o próprio modelo de Inteligência Artificial.
