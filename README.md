# miniguia-estudos-notebooklm
Desafio plataforma DIO - Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM
Guia de Estudo para Concurseiros – Área Ambiental

# 1. Contexto e Objetivos

O projeto tem como tema a elaboração de um guia de estudo voltado para concurseiros interessados na área ambiental, com foco na preparação para oportunidades profissionais de caráter técnico.

O objetivo é reunir e organizar conteúdos relevantes da legislação e das normas ambientais brasileiras, facilitando o acesso do estudante a materiais confiáveis e contribuindo para uma preparação mais direcionada para concursos públicos e processos seletivos relacionados à área técnica ambiental.

O guia poderá abordar temas como licenciamento ambiental, legislação florestal, proteção da vegetação nativa, competências dos órgãos ambientais, normas do CONAMA e principais conceitos relacionados à gestão ambiental.

Além de servir como material de revisão, a proposta busca apresentar os conteúdos de forma organizada e objetiva, permitindo que o concurseiro identifique os principais pontos de estudo e compreenda sua aplicação no contexto profissional.

# 2. Curadoria de Fontes

Para garantir a confiabilidade e a qualidade das informações apresentadas no guia, serão utilizadas como referências fontes institucionais, legislativas e técnicas reconhecidas.

Links:
#1 - https://www2.camara.leg.br/legin/fed/lei/2025/lei-15190-8-agosto-2025-797833-publicacaooriginal-176089-pl.html
#2 - https://conama.mma.gov.br/?option=com_sisconama&task=arquivo.download&id=450
#3 - https://www.embrapa.br/codigo-florestal/entenda-o-codigo-florestal
#4 - https://www.demarest.com.br/ebook-licenciamento-ambiental-lei-geral-e-sancionada-com-63-vetos-e-nova-mp-institui-modalidade-especial-com-aplicacao-imediata/
#5 - https://repositorio.londrina.pr.gov.br/index.php/menu-assistencia/estrutura-1/legislacao-5/legislacao-nacional/21832-lei-fed-6938-81/file

# 3. Engenharia de Prompts e "Cicatrizes"

Estratégias de Refinamento de Prompts Utilizadas no NotebookLM

Durante a construção do meu material de estudo sobre Meio Ambiente e Legislação Ambiental, utilizei diferentes técnicas de prompt no NotebookLM com o objetivo de testar a capacidade da ferramenta de interpretar as fontes adicionadas e, posteriormente, refinar a forma como as informações eram apresentadas.

A estratégia adotada foi baseada em um processo de experimentação e refinamento progressivo. Inicialmente, utilizei perguntas mais abertas, buscando compreender como o NotebookLM apresentava determinado assunto. Conforme percebi algumas limitações na interpretação das solicitações, passei a utilizar técnicas mais específicas, principalmente prompts de explicação, contextualização, instruções de formato e Few-Shot Prompting.

3.1 Prompt de Explicação

A primeira estratégia utilizada foi o Prompt de Explicação, fazendo perguntas abertas sobre os conteúdos presentes nas fontes.

Alguns exemplos foram:

"Me fale sobre o SNUC."
"Qual foi o prazo para o fim dos lixões?"
"Fim dos lixões no mundo?"
"Explique para mim os tipos de vegetações conhecidas no Brasil."

Nesse primeiro momento, o objetivo era verificar como o NotebookLM identificava as informações relevantes dentro das fontes e como organizava uma explicação a partir delas.

Essa técnica foi útil principalmente para obter uma visão geral dos assuntos, permitindo identificar conceitos importantes e compreender como os conteúdos estavam relacionados.

3.2 Utilização de Mapas Mentais

Depois das explicações iniciais, passei a solicitar uma organização mais visual das informações.

Um exemplo foi:

"Elabore para mim o mapa mental das principais informações sobre SNUC."

Essa abordagem buscou transformar um conteúdo mais extenso em uma estrutura hierárquica, facilitando a identificação dos conceitos principais, subdivisões e relações entre os assuntos.

Para um contexto de preparação para concursos, essa estratégia é interessante porque permite transformar textos legislativos e conceitos ambientais em estruturas mais fáceis de revisar posteriormente.

3.3 Refinamento por meio de Contextualização

Durante os testes, percebi que simplesmente solicitar que determinado conteúdo fosse "resumido" nem sempre produzia o resultado esperado.

Por exemplo, ao solicitar um resumo de determinado conteúdo, o NotebookLM poderia interpretar "resumir" de maneiras diferentes: retirar algumas informações, produzir um texto ainda relativamente extenso ou não destacar exatamente os pontos que eu considerava importantes para estudar.

Dessa forma, percebi que apenas utilizar a instrução "faça um resumo" não era suficiente.

Passei então a utilizar uma técnica de contextualização, explicando melhor qual era o objetivo da resposta e como eu gostaria que as informações fossem organizadas.

Essa mudança tornou o prompt mais específico, reduzindo a margem de interpretação da ferramenta.

3.4 Few-Shot Prompting

Outra técnica utilizada foi o Few-Shot Prompting, em que forneci exemplos do formato que esperava receber.

Um exemplo utilizado foi:

"Me explique as características de cada UC só que em formato de tópicos."

Em seguida, forneci um modelo de como gostaria que a informação fosse apresentada.

Também utilizei exemplos para solicitar respostas mais sucintas, como:

"Faça um resumo do conteúdo de unidades de conservação de forma mais sucinta."

E apresentei um modelo:

"Unidades de Proteção Integral — Preservar natureza, uso indireto dos recursos naturais."

"Estação Ecológica — Preservação da natureza e pesquisas científicas, restrição educacional."

Outro exemplo foi a estrutura:

"Zona de Amortecimento
Características:

Controle de uso do solo
Diminui o efeito de borda"

Nesse caso, o exemplo funcionou como uma referência prática para o modelo entender tanto o nível de profundidade quanto o formato esperado da resposta.

3.5 Contextualização + Exemplo

Uma das principais conclusões obtidas durante o processo foi que a combinação entre contextualização e exemplos produziu resultados melhores do que uma instrução genérica.

Quando solicitei apenas que o conteúdo fosse "resumido", o NotebookLM nem sempre interpretou corretamente o nível de síntese que eu desejava.

Por esse motivo, passei a explicar o que eu considerava uma resposta sucinta e, posteriormente, forneci um exemplo do resultado esperado.

Essa estratégia permitiu direcionar melhor a ferramenta, pois o prompt deixou de informar apenas o que fazer e passou também a demonstrar como o resultado deveria ser apresentado.

3.6 Estratégia de Refinamento Progressivo

De maneira geral, minha metodologia seguiu uma sequência de refinamento:

1. Pergunta aberta → 2. Análise da resposta → 3. Identificação da limitação → 4. Contextualização → 5. Exemplo → 6. Novo teste → 7. Refinamento do resultado.

Esse processo permitiu perceber que a qualidade da resposta não depende somente das fontes adicionadas ao NotebookLM, mas também da forma como a pergunta é construída.

Assim, comecei utilizando prompts mais simples para explorar o conteúdo e, posteriormente, passei a utilizar instruções mais detalhadas para controlar estrutura, nível de profundidade, quantidade de informações e forma de apresentação.



4. Miniguia de Estudo (Entrega Final):

   A utilização dessas diferentes técnicas demonstrou que o refinamento de prompts é um processo iterativo. Inicialmente, perguntas abertas foram suficientes para explorar os conteúdos de Meio Ambiente e Legislação Ambiental. Entretanto, quando o objetivo passou a ser produzir materiais específicos para estudo e revisão, tornou-se necessário fornecer mais contexto e exemplos.

O principal aprendizado foi que quanto mais específico era o objetivo da resposta, mais importante se tornava explicar o contexto e demonstrar, por meio de exemplos, o resultado esperado.

Dessa forma, as técnicas de Prompt de Explicação, Contextualização, Few-Shot Prompting, síntese e organização estruturada foram utilizadas de maneira complementar para transformar as fontes do NotebookLM em materiais de estudo mais objetivos, organizados e adequados à preparação para concursos na área ambiental.

# 4.2 Glossário — Conceitos Aprendidos na Interação

## A

**Análise de Resposta**
Processo de avaliar a resposta produzida pela IA para identificar se ela atende ao objetivo do prompt. Quando a resposta não apresenta o nível de detalhe, formato ou síntese desejados, o prompt pode ser refinado.

**Análise Iterativa**
Processo de testar um prompt, analisar o resultado, identificar problemas e realizar novos ajustes. É uma das principais estratégias utilizadas durante a construção dos prompts no NotebookLM.

## C

**Contextualização**
Técnica de fornecer informações adicionais sobre o objetivo da solicitação, ajudando a IA a compreender melhor o que deve ser produzido. Foi utilizada principalmente quando uma solicitação genérica, como "faça um resumo", não produziu o resultado esperado.

**Controle de Formato**
Utilização de instruções para determinar como a resposta deve ser apresentada, como tópicos, listas, mapas mentais, resumos ou estruturas hierárquicas.

## E

**Engenharia de Prompt (Prompt Engineering)**
Processo de criação, estruturação e refinamento de instruções fornecidas a uma inteligência artificial para obter respostas mais precisas, relevantes e adequadas ao objetivo do usuário.

**Exemplo de Saída**
Trecho apresentado no prompt para demonstrar à IA como o resultado desejado deve ser estruturado. Foi utilizado na interação para mostrar, por exemplo, como resumir as características das Unidades de Conservação.

## F

**Few-Shot Prompting**
Técnica em que são fornecidos um ou mais exemplos antes ou durante a solicitação para orientar a IA sobre o padrão esperado de resposta. No seu caso, você apresentou exemplos de como gostaria que os conteúdos fossem resumidos e organizados.

**Formato Estruturado**
Organização das informações segundo uma estrutura previamente definida, como títulos, subtítulos, tópicos, características e exemplos.

## M

**Mapa Mental**
Forma de organização visual e hierárquica das informações, geralmente partindo de um conceito central e dividindo-o em categorias e subcategorias. Você utilizou essa estratégia para organizar os principais conceitos relacionados ao SNUC.

**Meta de Resposta**
Objetivo que se pretende alcançar com o prompt, como obter uma explicação, resumo, mapa mental ou material de revisão.

## P

**Prompt**
Instrução ou conjunto de instruções fornecidas a uma inteligência artificial para orientar a geração de uma resposta.

**Prompt de Explicação**
Prompt utilizado para solicitar que a IA explique determinado assunto de maneira compreensível. Exemplos utilizados: "Me fale sobre o SNUC" e "Explique para mim os tipos de vegetações conhecidas no Brasil".

**Prompt Iterativo**
Prompt que passa por sucessivos testes e modificações até que a resposta produzida esteja de acordo com o objetivo desejado.

**Prompt de Contextualização**
Instrução que apresenta contexto adicional para reduzir ambiguidades e ajudar a IA a compreender exatamente o objetivo da solicitação.

## R

**Refinamento de Prompt**
Processo de modificar um prompt para melhorar a qualidade, precisão, estrutura ou nível de detalhamento da resposta.

**Resposta Genérica**
Resposta que atende superficialmente à solicitação, mas não necessariamente apresenta o formato, profundidade ou nível de síntese esperado pelo usuário.

## S

**Síntese**
Processo de reduzir um conteúdo extenso, preservando suas informações essenciais. No seu estudo, a síntese foi utilizada para transformar conteúdos ambientais mais extensos em materiais rápidos para revisão.

**Sumarização**
Processo de produzir um resumo de um conteúdo, destacando suas informações consideradas mais relevantes.

**SNUC — Sistema Nacional de Unidades de Conservação da Natureza**
Sistema instituído pela Lei nº 9.985/2000 que estabelece critérios e normas para criação, implantação e gestão das Unidades de Conservação no Brasil.

## U

**Unidade de Conservação (UC)**
Espaço territorial e seus recursos ambientais, incluindo águas jurisdicionais, com características naturais relevantes, legalmente instituído pelo Poder Público com objetivos de conservação e limites definidos.

**Unidades de Proteção Integral**
Categoria de Unidades de Conservação cujo objetivo principal é preservar a natureza, permitindo apenas o uso indireto dos recursos naturais, conforme as regras aplicáveis a cada categoria.

**Unidades de Uso Sustentável**
Categoria de Unidades de Conservação que busca compatibilizar a conservação da natureza com o uso sustentável de parcela dos seus recursos naturais.

**Zona de Amortecimento**
Área do entorno de uma Unidade de Conservação onde determinadas atividades e usos podem ser regulados para minimizar impactos negativos sobre a unidade.

## 🔄 Conceito central aprendido

**Refinamento Progressivo de Prompts**
Estratégia utilizada ao longo da interação em que o usuário começa com uma solicitação simples, observa o comportamento da IA e progressivamente adiciona **contexto, exemplos, formato e critérios de síntese**.

No seu caso, o processo pode ser representado da seguinte maneira:

**Prompt simples → Resposta da IA → Identificação de problema → Contextualização → Exemplo (Few-Shot) → Refinamento → Resposta mais adequada**

Esse foi provavelmente o principal conceito aprendido durante a atividade: **não é necessário tentar criar o prompt perfeito de primeira; é possível utilizar a própria resposta da IA como elemento para aprimorar o próximo prompt.**

4.3 Um conjunto de prompts reutilizáveis que possam apoiar futuras revisões sobre o tema.

* **Prompt de Explicação**

  * Explicar conceitos e assuntos de forma didática.
  * Exemplo: "Explique o SNUC utilizando as fontes disponíveis."

* **Prompt de Contextualização**

  * Informar o objetivo do estudo para direcionar a resposta.
  * Exemplo: "Explique o tema considerando que estou estudando para concursos na área ambiental."

* **Prompt de Síntese/Sumarização**

  * Reduzir conteúdos extensos, mantendo apenas as informações essenciais.
  * Exemplo: "Faça um resumo curto e objetivo sobre Unidades de Conservação."

* **Few-Shot Prompting**

  * Fornecer exemplos para demonstrar à IA o formato e o nível de detalhamento desejados.
  * Exemplo: apresentar um modelo de resumo e solicitar que o restante siga o mesmo padrão.

* **Controle de Formato**

  * Definir como a resposta deve ser estruturada.
  * Exemplos: tópicos, listas, tabelas, mapas mentais ou frases curtas.

* **Mapa Mental**

  * Organizar um assunto de forma hierárquica e facilitar a visualização dos conceitos.

* **Prompt de Comparação**

  * Comparar dois ou mais conceitos, destacando diferenças, semelhanças e características.

* **Prompt de Legislação**

  * Identificar conceitos, artigos, obrigações, proibições, prazos, exceções e informações relevantes de uma legislação.

* **Prompt de Pegadinhas**

  * Identificar conceitos que podem causar confusão ou aparecer como pegadinhas em questões de concursos.

* **Prompt de Memorização**

  * Destacar palavras-chave, conceitos, números, prazos e informações importantes para memorizar.

* **Prompt de Revisão Rápida**

  * Produzir uma revisão objetiva contendo apenas os pontos indispensáveis do conteúdo.

* **Prompt de Questões**

  * Criar questões de múltipla escolha para testar o conhecimento adquirido.

* **Prompt de Análise de Erros**

  * Identificar erros nas respostas e indicar quais conceitos precisam ser revisados.

* **Refinamento Iterativo**

  * Analisar a resposta obtida, identificar problemas e modificar o prompt para melhorar o resultado.

* **Estratégia de Refinamento Progressivo**

  * Utilizar a sequência:

    * Explorar o conteúdo
    * Explicar
    * Contextualizar
    * Fornecer exemplos
    * Resumir
    * Organizar
    * Memorizar
    * Testar
    * Refinar o prompt


