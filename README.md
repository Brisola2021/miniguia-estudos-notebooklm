# miniguia-estudos-notebooklm
Desafio plataforma DIO - Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM
Guia de Estudo para Concurseiros – Área Ambiental
1. Contexto e Objetivos

O projeto tem como tema a elaboração de um guia de estudo voltado para concurseiros interessados na área ambiental, com foco na preparação para oportunidades profissionais de caráter técnico.

O objetivo é reunir e organizar conteúdos relevantes da legislação e das normas ambientais brasileiras, facilitando o acesso do estudante a materiais confiáveis e contribuindo para uma preparação mais direcionada para concursos públicos e processos seletivos relacionados à área técnica ambiental.

O guia poderá abordar temas como licenciamento ambiental, legislação florestal, proteção da vegetação nativa, competências dos órgãos ambientais, normas do CONAMA e principais conceitos relacionados à gestão ambiental.

Além de servir como material de revisão, a proposta busca apresentar os conteúdos de forma organizada e objetiva, permitindo que o concurseiro identifique os principais pontos de estudo e compreenda sua aplicação no contexto profissional.

2. Curadoria de Fontes

Para garantir a confiabilidade e a qualidade das informações apresentadas no guia, serão utilizadas como referências fontes institucionais, legislativas e técnicas reconhecidas.

Links:
#1 - https://www2.camara.leg.br/legin/fed/lei/2025/lei-15190-8-agosto-2025-797833-publicacaooriginal-176089-pl.html
#2 - https://conama.mma.gov.br/?option=com_sisconama&task=arquivo.download&id=450
#3 - https://www.planalto.gov.br/ccivil_03/leis/l9985.htm
#4 - https://www.demarest.com.br/ebook-licenciamento-ambiental-lei-geral-e-sancionada-com-63-vetos-e-nova-mp-institui-modalidade-especial-com-aplicacao-imediata/
#5 - https://repositorio.londrina.pr.gov.br/index.php/menu-assistencia/estrutura-1/legislacao-5/legislacao-nacional/21832-lei-fed-6938-81/file

3. Curadoria de Fontes

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
