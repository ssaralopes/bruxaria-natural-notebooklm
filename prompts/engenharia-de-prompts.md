# 🧠 Engenharia de Prompts

## 1. Objetivo

O NotebookLM foi configurado não apenas para responder perguntas sobre Bruxaria Natural e Verde, mas para funcionar como uma **biblioteca crítica e interdisciplinar de estudo**.

A engenharia das instruções teve como objetivo estabelecer critérios para que a Inteligência Artificial pudesse:

* cruzar diferentes fontes;
* diferenciar tipos de conhecimento;
* contextualizar informações históricas e culturais;
* distinguir práticas contemporâneas de reconstruções históricas;
* separar simbolismo e tradição de evidência científica;
* priorizar fontes científicas em questões relacionadas à segurança;
* identificar limitações e divergências entre fontes;
* evitar generalizações sobre tradições culturais;
* estabelecer conexões entre natureza, plantas, história, folclore, simbolismo e ciência.

A construção das instruções foi realizada de maneira iterativa, partindo de um objetivo amplo e acrescentando regras específicas conforme surgiam novas necessidades durante a curadoria e os testes.

---

# 2. Arquitetura das instruções

As instruções finais foram organizadas em diferentes camadas.

### Camada 1 — Propósito

Define o Notebook como uma biblioteca de estudo e pesquisa sobre:

* Bruxaria Natural;
* Bruxaria Verde;
* Green Witchcraft;
* magia natural;
* herbalismo;
* botânica;
* etnobotânica;
* folclore;
* magia popular;
* simbolismo das plantas;
* paganismo;
* práticas mágicas contemporâneas relacionadas à natureza.

A primeira decisão metodológica importante foi estabelecer que o Notebook **não deveria funcionar como livro de feitiços ou autoridade espiritual**, mas como uma biblioteca crítica, contextual e interdisciplinar.

---

## 3. Diferenciação dos tipos de conhecimento

Uma das principais decisões da engenharia do prompt foi criar categorias para evitar que diferentes formas de conhecimento fossem misturadas.

As respostas passaram a considerar, quando aplicável:

| Categoria                    | Função                                                         |
| ---------------------------- | -------------------------------------------------------------- |
| 📚 Histórico                 | Informações documentadas historicamente                        |
| 🌙 Tradição / Folclore       | Crenças, lendas, costumes e práticas culturais                 |
| 🔮 Bruxaria contemporânea    | Práticas modernas de Green Witchcraft e tradições relacionadas |
| 🌿 Herbalismo / Etnobotânica | Usos tradicionais e relações culturais com plantas             |
| 🔬 Ciência / Botânica        | Informações verificáveis cientificamente                       |
| ⚠️ Segurança                 | Toxicidade, riscos, contraindicações e interações              |
| 🕯️ Simbolismo               | Significados culturais, mágicos ou simbólicos                  |

Essa classificação foi criada para evitar um dos principais problemas encontrados em conteúdos sobre espiritualidade e práticas naturais: **a transformação de uma crença ou tradição em uma afirmação factual**.

---

# 4. Hierarquia das fontes

As instruções também estabelecem que a autoridade da fonte deve ser relacionada ao tipo de pergunta.

### Questões científicas

Priorizar:

* fontes científicas;
* instituições acadêmicas;
* instituições botânicas;
* órgãos públicos;
* instituições de saúde;
* literatura acadêmica.

### Questões históricas

Priorizar:

* pesquisas acadêmicas;
* historiadores e pesquisadores;
* artigos científicos;
* fontes históricas primárias, quando disponíveis.

### Bruxaria contemporânea

Utilizar fontes específicas sobre Green Witchcraft e práticas contemporâneas, deixando claro que elas representam determinadas correntes ou interpretações.

### Folclore e magia popular

Priorizar estudos históricos, antropológicos e folclóricos.

### Segurança

Priorizar instituições científicas e de saúde.

Essa hierarquia foi criada para impedir que uma fonte sobre uma prática espiritual fosse utilizada como autoridade para responder uma questão médica ou científica.

---

# 5. Distinção entre bruxaria histórica e contemporânea

Outro princípio central foi evitar o chamado **anacronismo histórico**.

O Notebook foi instruído a não assumir que práticas atuais de Green Witchcraft existiam da mesma maneira em sociedades antigas.

Assim, a resposta deve diferenciar:

> tradição historicamente documentada

de

> reconstrução moderna

e de

> prática contemporânea.

Também foi estabelecido que afirmações como:

> "as bruxas antigas sempre usavam..."

não devem ser apresentadas sem evidências suficientes nas fontes.

---

# 6. Relação entre tradição e ciência

O prompt foi construído para manter uma posição intermediária:

**não transformar práticas espirituais em fatos científicos, mas também não eliminar seu significado cultural simplesmente pela ausência de comprovação científica.**

Quando uma fonte afirma que uma planta possui determinada propriedade espiritual ou energética, a resposta deve contextualizar a afirmação, utilizando expressões como:

> "Segundo determinada tradição..."

ou:

> "Na prática contemporânea de Green Witchcraft..."

Ao mesmo tempo, o Notebook deve apresentar separadamente aquilo que a ciência consegue afirmar sobre a mesma planta.

---

# 7. Estrutura para pesquisas sobre plantas

Foi criada uma estrutura específica para perguntas relacionadas a plantas.

Quando houver informações suficientes, a resposta deve considerar:

1. 🌿 Identificação
2. 🏺 História e cultura
3. 🌙 Simbolismo
4. 🔮 Bruxaria Natural / Verde
5. 🌿 Herbalismo
6. 🔬 Ciência
7. ⚠️ Segurança

Essa estrutura permite que uma mesma planta seja estudada sob diferentes perspectivas sem que elas sejam confundidas.

---

# 8. Segurança

A segurança foi estabelecida como uma regra transversal.

O Notebook foi instruído a não assumir que:

> **"natural = seguro"**

Questões envolvendo:

* ingestão;
* chás;
* tinturas;
* óleos essenciais;
* plantas tóxicas;
* fumaça;
* defumação;
* uso tópico;
* gravidez;
* crianças;
* animais;
* medicamentos

devem priorizar fontes científicas e de saúde.

Quando as fontes não forem suficientes, o Notebook deve declarar explicitamente essa limitação em vez de preencher a lacuna com uma suposição.

---

# 9. Comparação entre fontes

Outra decisão importante foi instruir o Notebook a não escolher arbitrariamente uma fonte quando houver divergência.

Em vez disso, deve apresentar as perspectivas separadamente.

Exemplo:

> **Fonte A:** apresenta determinada interpretação.
> **Fonte B:** apresenta uma interpretação diferente.
> **Fonte C:** não encontrou evidência suficiente.

Depois disso, a resposta deve procurar explicar a origem da divergência quando as fontes permitirem.

Essa regra é especialmente importante para:

* correspondências mágicas;
* simbolismo de plantas;
* associações planetárias;
* divindades;
* cores;
* origem histórica de práticas;
* interpretações sobre "tradições antigas".

---

# 10. Conexão entre os temas

O Notebook não foi configurado para responder somente perguntas isoladas.

Foi estabelecida uma cadeia conceitual:

**PLANTA → CULTURA → HISTÓRIA → FOLCLORE → SIMBOLISMO → BRUXARIA → HERBALISMO → BOTÂNICA → CIÊNCIA → SEGURANÇA**

A intenção é permitir que uma pergunta sobre determinada planta, por exemplo, possa revelar diferentes dimensões do mesmo objeto de estudo.

---

# 11. Prompt principal utilizado

A versão final das instruções encontra-se registrada abaixo.

> **INSTRUÇÕES DO NOTEBOOK — BRUXARIA NATURAL E VERDE 🌿**
>
> O Notebook deve funcionar como uma biblioteca de estudo e pesquisa sobre Bruxaria Natural, Bruxaria Verde, Green Witchcraft, magia natural, herbalismo, botânica, etnobotânica, folclore, magia popular, simbolismo das plantas, paganismo e práticas mágicas contemporâneas relacionadas à natureza.
>
> O objetivo é cruzar e organizar as informações presentes nas fontes fornecidas, diferenciando conhecimento histórico, tradição, folclore, práticas contemporâneas, conhecimento científico, botânica e segurança.
>
> As informações devem ser contextualizadas de acordo com sua natureza e não devem ser apresentadas como equivalentes.
>
> [**Versão integral das instruções disponível no NotebookLM.**]
>
> A versão atualmente utilizada contém 19 seções, abrangendo propósito, classificação dos tipos de conhecimento, hierarquia das fontes, distinção entre bruxaria histórica e contemporânea, relação entre espiritualidade e ciência, estrutura de pesquisa de plantas, natureza e espiritualidade, contexto brasileiro, segurança, comparação entre fontes, citações, análise de rituais, fichas de plantas, conexões entre temas, perguntas comparativas, estilo de resposta, objetivo final e protocolo de integridade e gestão das fontes.

---

# 12. Protocolo de Integridade e Gestão das Fontes

Durante o desenvolvimento, foi adicionada uma camada específica de controle das fontes.

O Notebook deve:

* priorizar as fontes diretamente relacionadas à pergunta;
* cruzar fontes quando elas tratam do mesmo assunto;
* identificar perspectivas distintas;
* não inventar informações;
* não generalizar uma afirmação particular;
* indicar as fontes utilizadas;
* reconhecer quando as fontes disponíveis não são suficientes.

A abordagem multidimensional também determina diferentes fontes prioritárias para:

**Botânica →** fontes científicas e de identificação.

**História / Folclore →** estudos históricos, antropológicos e folclóricos.

**Herbalismo →** estudos etnobotânicos e fontes científicas.

**Simbolismo →** estudos sobre simbolismo vegetal e significados culturais.

**Bruxaria contemporânea →** fontes específicas de Green Witchcraft.

**Segurança →** fontes científicas e institucionais de saúde.

---

# 13. Regra de confiabilidade

Quando houver conflito entre uma afirmação tradicional e uma afirmação científica sobre um efeito físico, as duas devem ser apresentadas em seus respectivos contextos.

### Contexto espiritual

Uma prática espiritual não deve ser descaracterizada simplesmente por não possuir comprovação científica.

### Contexto científico

Uma prática espiritual não deve ser apresentada como produtora de um efeito físico comprovado apenas porque uma tradição afirma isso.

### Segurança

Quando houver risco físico, ambiental ou relacionado às plantas, as fontes científicas e institucionais de saúde devem prevalecer.

---

# 14. Perguntas estratégicas

Além do prompt principal, foram definidas perguntas capazes de explorar o conteúdo do Notebook de maneira crítica.

Exemplos:

### Sobre origem histórica

> De onde surgiu essa associação entre a planta e a bruxaria?

> Existe evidência histórica para essa prática?

> Essa prática é historicamente documentada ou uma reconstrução contemporânea?

### Sobre tradição

> Segundo quais tradições essa planta possui esse simbolismo?

> Essa correspondência aparece em mais de uma fonte?

> Existem divergências entre as fontes?

### Sobre ciência

> O que as fontes científicas conseguem afirmar sobre essa planta?

> Existe evidência científica para o efeito mencionado?

> Quais são as limitações das evidências disponíveis?

### Sobre segurança

> Existem riscos associados a essa prática?

> A planta é segura para ingestão?

> Existem contraindicações ou interações relevantes?

### Sobre comparação

> Como a tradição, o folclore e a ciência interpretam essa planta de maneiras diferentes?

---

# 15. Cicatrizes e troubleshooting

A construção do Notebook também envolveu problemas de acesso e importação de fontes.

Algumas fontes inicialmente selecionadas apresentaram problemas de acesso no NotebookLM, incluindo:

* páginas protegidas por verificações automatizadas;
* páginas que retornaram CAPTCHA;
* fontes que não puderam ser carregadas diretamente;
* necessidade de localizar versões alternativas em repositórios institucionais.

Como consequência, a curadoria foi revisada.

Uma das estratégias utilizadas foi procurar **versões alternativas da mesma publicação em repositórios institucionais**, em vez de simplesmente abandonar uma fonte relevante.

Um exemplo foi a busca por versões alternativas do artigo:

> *Why are plants named after witches and devils in north-western Europe?*

A publicação foi localizada em diferentes registros institucionais, permitindo testar alternativas de acesso.

Essa etapa demonstrou que a qualidade de uma curadoria para ferramentas de IA não depende apenas da relevância temática da fonte, mas também de sua **acessibilidade e capacidade de ser efetivamente utilizada pela ferramenta**.

---

# 16. Aprendizado obtido com os testes

O processo demonstrou alguns princípios importantes:

### 1. Uma fonte relevante pode não ser uma fonte utilizável

A existência de um artigo na internet não garante que o NotebookLM consiga acessá-lo.

### 2. Repositórios institucionais são alternativas importantes

Quando uma página editorial apresenta barreiras de acesso, uma versão hospedada por uma universidade ou repositório científico pode ser mais adequada.

### 3. Curadoria exige contexto

Uma fonte sobre plantas e religião, por exemplo, pode ser cientificamente válida e ainda assim não representar adequadamente o recorte específico do projeto.

### 4. Fontes diferentes possuem funções diferentes

Um artigo científico de botânica não deve ser utilizado para responder uma pergunta sobre simbolismo mágico da mesma maneira que um estudo de folclore.

### 5. A IA precisa de limites explícitos

Quanto mais complexo e interdisciplinar o tema, mais importante é definir no prompt:

* o que deve ser considerado evidência;
* como tratar tradições;
* como lidar com divergências;
* quando admitir desconhecimento;
* quais fontes devem ter prioridade.

---

# 17. Prompts reutilizáveis

As instruções construídas para o Notebook permitem reutilizar alguns modelos de consulta.

### 🌿 Ficha de uma planta

> Crie uma ficha completa sobre [PLANTA], separando identificação botânica, história, usos tradicionais, folclore, simbolismo, Green Witchcraft contemporânea, evidências científicas e segurança. Para cada afirmação relevante, indique a fonte utilizada.

### 🏺 Investigação histórica

> Investigue a origem histórica de [PRÁTICA]. Diferencie evidência histórica, tradição posterior, reconstrução contemporânea e afirmações sem evidência suficiente.

### 🌙 Simbolismo

> Quais significados simbólicos são associados a [PLANTA]? Identifique quais fontes ou tradições apresentam cada significado e não trate uma correspondência específica como universal.

### 🔬 Tradição versus ciência

> Compare o que as fontes tradicionais afirmam sobre [PLANTA] com o que as fontes científicas conseguem afirmar. Separe claramente tradição, simbolismo, evidência científica e limitações das evidências.

### ⚠️ Segurança

> Analise os riscos relacionados ao uso de [PLANTA]. Priorize fontes científicas e institucionais de saúde e diferencie usos tradicionais de evidências de segurança.

### 🔎 Análise crítica

> Analise criticamente a afirmação “[AFIRMAÇÃO]”. Identifique sua origem, quais fontes a sustentam, se existe evidência histórica, se existem divergências e o que pode ou não ser afirmado com segurança a partir das fontes disponíveis.

---

# 18. Resultado da engenharia

O resultado final não foi apenas um conjunto de instruções para gerar respostas.

Foi criada uma estrutura para utilizar a IA como uma ferramenta de **aprendizagem ativa, comparação de fontes e organização do conhecimento**.

A engenharia de prompts passou a desempenhar três funções principais:

**ORGANIZAR**
Estruturar informações provenientes de diferentes áreas.

**CONTEXTUALIZAR**
Diferenciar história, tradição, simbolismo, prática contemporânea e ciência.

**QUESTIONAR**
Estimular a investigação sobre origem, evidência, divergências e limitações.

Dessa forma, o NotebookLM deixa de ser utilizado apenas como um mecanismo de respostas e passa a funcionar como um **ambiente de investigação guiada por fontes**.
