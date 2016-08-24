# Introdução

Durante o período de formação superior no Brasil, muitos alunos *sofrem*
para elaborar e entregar uma monografia, como requisito para conclusão
dos estudos. Uma parte desse sofrimento está associada à formatação da
monografia (no software de editoração) em conformidade com as normas
da Associação Brasileira de Normas Técnicas (ABNT). 

O público nacional atualmente possui notadamente duas alternativas
para formatação de trabalhos acadêmicos: (1) Utilização de um editor
de texto rico (como o Microsoft Word ou Libre Office) ou (2)
Utilização do Latex. Embora o Latex possua uma *curva de aprendizado
maior*, a produção de trabalhos acadêmicos com um editor de texto rico
exige conhecimentos avançados da ferramenta (tais como utilização de
estilos, geração de sumário e gerência de referências) ou esforço de
edição muito grande para formatações manuais de todas as seções do
trabalho.

As linguagens de marcação de texto (*lightweight markup language*)
surgiram, em diferentes contextos, como alternativas para elaboração e
formatação de textos. Essas linguagens possibilitam os usuários
redigirem em arquivos somente texto (*plain text*), com uma curva de
aprendizado menor do que o Latex.


## Motivação

A motivação desse trabalho consiste em ofertar uma nova alternativa
para elaboração de trabalhos acadêmicos (monografia, dissertação ou
tese) utilizando uma linguagem de marcação de texto, elaborada com o
propósito de facilitar os alunos a redigirem e formatarem seus
trabalhos em conformidade com as Normas da ABNT.

## Objetivos

### Objetivo Geral

Esse trabalho objetiva *propor* e *avaliar* um sistema que utiliza
uma linguagem de marcação de texto especializada para a produção de
trabalhos acadêmicos em conformidades com as normas da ABNT.

### Objetivos Específicos

- Avaliar a utilização de uma linguagem de marcação de texto na
  produção de monografias;
  
- Avaliar a utilização de formulários PDF para edição
  e configuração de conteúdos específicos dos trabalhos acadêmicos.


## Método

Um método de avaliação de um sistema pode ocorrer em três dimensões:
a) com ou sem o envolvimento ativo dos usuários, b) com ou sem o
sistema em execução e c) com ou sem um contexto realístico de
utilização. Além disso, seus os requisitos de avaliação mais comuns
são: validade analítica, escopo, confiança, produtividade, usabilidade
e capacidade de aprendê-lo \cite{blandfordann}.

<!-- Tese: elaborar uma metodologia para avaliar sistemas para 
produção de trabalhos acadêmicos.

Ver: Chapter 4
Ann Blandford and Thomas Green
Methodological Development -->

Essa pesquisa utilizará uma avaliação *com* envolvimento ativo dos
usuários, *com* sistema em execução e *sem* um contexto realístico. O
método de avaliação empregado, utilizando o *Cognitive Dimensions of
Notations framework*, está descrito no Capítulo 5, junto com a
descrição do experimento.

<!-- Essa pesquisa utiliza filosofia Pragmática
\cite[easterbrook2008selecting], ao escolher o método de pesquisa que
melhor convém ao pesquisador para solucionar o problema em que se
depara. -->

O contexto da pesquisa contempla apenas usuários com nível superior
*incompleto* ou *completo*, que tiveram contato com as normas da ABNT
durante sua formação. 

## Estrutura da Dissertação

Esta proposta está dividida da seguinte forma:

- Capítulo 2: Apresenta a fundamentação teórica, abordando assuntos necessários para o
desenvolvimento do trabalho;
- Capítulo 3: Apresenta um trabalho relacionado sobre adaptação da
  linguagem Markdown para um contexto científico;
- Capítulo 4: Apresenta a proposta de dissertação;
- Capítulo 5: Apresenta a proposta do experimento;
- Capítulo 6: Cronograma de atividades para atingir os objetivos.

# Fundamentação Teórica

A fundamentação teórica do trabalho consiste nas normas da ABNT,
biblioteca para elaboração de textos com as normas da

## Normas da ABNT para trabalhos acadêmicos ##

As normas da ABNT que normatizam como cada elemento dos trabalhos
acadêmcios trabalhos são as seguintes:

-   ABNT NBR 14724, Informação e documentação - Trabalhos acadêmicos -
    Apresentação;

-   ABNT NBR 6023, Informação e documentação - Referências - Elaboração;

-   ABNT NBR 6024, Informação e documentação - Numeração progressiva das
    seções de um documento escrito - Apresentação;

-   ABNT NBR 6027, Informação e documentação - Sumário - Apresentação;

-   ABNT NBR 6028, Informação e documentação - Resumo - Procedimento;

-   ABNT NBR 6034, Informação e documentação - Índice - Apresentação;

-   ABNT NBR 10520, Informação e documentação - Citações em documentos -
    Apresentação;

-   ABNT NBR 12225, Informação e documentação - Lombada - Apresentação;

-   Código de Catalogação Anglo-Americano. 2. ed. rev. 2002. São Paulo:
    FEBAB, 2004.

-   IBGE. Normas de apresentação tabular. 3. ed. Rio de Janeiro, 1993.

A seguir serão destacadas as regras a elementos relevantes a essa
pesquisa.

### Ilustrações

Segundo a ABNT NBR 14724(:2011), ao inserir uma ilustração no texto,
deveremos:

-   Obrigatoriamente, adicionar na parte superior (a) o tipo da
    ilustração (Figura, Quadro, Tabela, etc.), (b) um travessão como
    separador, e (c) um título para a ilustração. (Regra de
    apresentação);

-   Obrigatoriamente adicionar na parte inferior, a fonte da imagem,
    mesmo que seja do próprio autor. (Regra de apresentação);

-   Opicionalmente notas explicativas e legendas também podem ser
    adicionadas na parte inferior. (Regra de apresentação);

-   Obrigatoriamente, referenciar a ilustração no texto, o mais
    próximo possível. (Regra de utilização).

### Guias ou manuais conflitantes com as Normas da ABNT

Provavelmente devido as normas da ABNT possuírem direitos autorais (e
serem comercializadas), muitas instituições produzem guias próprios para
auxiliarem os alunos na formatação dos trabalhos. Percebemos que os
guias apresentam informações adicionais (tais como tamanho ou tipo da
fonte de determinados elementos) que direcionam os alunos a uma
implementação das normas, mas que não são exigências delas.

Os alunos, sem conhecerem as normas, passam a confiar que os guias

Também é possível encontrar manuais tais como
\cite{joelma_marques_da_silva_normas_2012} e \cite{conselheiro_lafaiete_manual_2016}
que apresentam instruções conflitantes com as normas.

> A identificação da figura deve estar localizada em sua parte inferior,
> em letras maiúsculas, em tamanho 10, alinhada à margem lateral
> esquerda do texto, contendo \[...\]
>
> A fonte de onde foram extraídas as informações deve ser colocada
> abaixo do título da figura, precedida dos seguintes itens \[...\]

## abnTeX2 ##



<!-- A escolha de qual ambiente utilizar varia de acordo com gosto, a área
do trabalho e afinidade do aluno (e do orientado) com as ferramentas. -->

Em
ambos sistemas são possíveis elaborar modelos de documentos com estilos
de formatação, previamente configurados, para atender aos requisitos
das Normas da ABNT para trabalhos acadêmicos. 

As coordenações de
cursos costumam disponibilizar para os alunos tais modelos.




costuma utilizar o Word, mas uma parcela menor opta pelo Latex, que
possui uma curva de aprendizado maior. As linguagens de marcações de
texto, como o Markdown e similares, surgem como alternativas para
simplificar a complexidade de formatação de textos.

Essas linguagens de marcação de texto alegam serem mais
ágeis\footnote{Comparado ao Latex.} para composição de textos, mas não
encontramos na literatura estudos empíricos para suportar essa
afirmação, especialmente para formatação com as normas da ABNT.

O surgimento do pacote Abntex\footnote{http://www.abntex.net.br}
auxiliou na popularização da utilização do Latex para trabalhos
acadêmicos no Brasil, ao fornecer estilos e comandos em conformidades
com as normas da ABNT, mas o equivalente ainda não aconteceu com as
linguagens de marcação. Não encontramos iniciativas que foram capazes
de escrever e formatar, com sucesso, monografias em Markdown no país.

O *Design* simplista do Markdown impõe algumas
limitações\footnote{Sintaxe original do Markdown
  \href{https://daringfireball.net/projects/markdown/syntax}.}, uma
delas é impossibilitar adicionar, simultaneamente, as legendas e
fontes das Figuras ou Tabelas, exigência das normas da ABNT.





O abnTeX2, evolução do abnTeX (*ABsurd Norms for TeX*), é
uma iniciativa livre que apresenta um conjunto de pacotes para produção
de documentos escritos me Latex. Além configurações de estilos em
conformidade com as normas da ABNT, o pacote contém modelos para tipos
de documentos, tais como Monografia, Artigos e Livro etc.

As universidades costumam disponibilizar modificações dos modelos
abnTeX2 para os alunos que desejam realizar os trabalhos de conclusão de
curso no Latex.

## Linguagens de marcação de texto ##

As linguagens de marcação de texto[^1] são linguagens que realizaram
marcações no texto de forma simples, de fácil leitura/escrita para o
usuário. Elas costumam serem utilizadas para composição de mensagens na
internet, ou geração de textos.

### Markdown

Markdown é uma linguagem de marcação de texto simples que dispensa o uso
de palavras chaves \cite{pandoc}. Sua origem foi inspirada na escrita de
e-mails e seu propósito original era exclusivamente *escrever para
Web* (geração de código HTML). Sua filosofia é que o formato do
texto escrito possua uma formatação visual similar à apresentação do
documento final (página HTML).

Várias ferramentas possuem implementações próprias do Markdown,
expandindo o formato original para contemplar novos recursos e
contextos, uma dessas ferramenta é a Pandoc.

#### Pandoc

A arquitetura da ferramenta Pandoc permite converter arquivos em
diferentes formatos.[^2] O usuário pode escolher quais extensões do
Markdown deseja utilizar[^3]. A Figura \ref{fig:rmarkdown} apresenta um
subconjunto da linguagem.

\begin{figure}[htb]
\caption{\label{fig:rmarkdown}Subconjunto da sintaxe do Markdown}
\begin{center}
\includegraphics[width=0.70000\textwidth]{imagens/Rmarkdown.png}
\end{center}
\legend{Fonte: \url{https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf}}
\end{figure}

Ela possui um módulo de geração de código (relacionado à sintaxe da
linguagem) e outro para configuração do modelo de documento onde o
código gerado será inserido. De forma simplória podemos dizer que 
*o modelo contém as configurações de estilo do documento*, e
*o conteúdo é gerado a partir texto escrito com a sintaxe
Markdown*.

#### YAML

As configurações dos modelos são realizadas através de uma sintaxe de
configuração de modelos. O usuário deve atribuir os valores das
variáveis no formato YAML[^4], em um arquivo separado ou dentro do
próprio texto através da criação de um bloco de configuração YAML.

\begin{figure}[htb]
\caption{\label{fig:yaml}Exemplo de um bloco configuração no formato YAML}
\begin{center}
\includegraphics[width=0.70000\textwidth]{imagens/yaml.png}
\end{center}
\legend{Fonte: autor}
\end{figure}


O formato YAML é *tipado* e *razoavelmente
permissivo* \cite{yamlv12}. O fato de ser tipado facilita o
desenvolvimento de aplicações, pois as variáveis são retornadas com o
tipo apropriado, sem necessidade do desenvolvedor realizar um
*parse* manual. No código na Figura \ref{fig:yaml} as
variáveis *title*, *abstract* e
*date* retornariam valores do tipo *String*,
*String* e *Inteiro* respectivamente. O tipo
da variável *author* é um pouco mais complexo, ele é
*Hash* de *Lista* de *Hash* -
isto é necessário para possibilitar informar o nome e a filiação de mais
de um autor.

A permissividade auxilia o usuário, pois permite inserir valores 
*String* sem aspas, como nas variáveis *title* e
 *fontsize*. No entanto, caso deseje-se preencher um
*String* com o caracter “:”, será necessário inserir todo o
valor entre aspas, como o valor da variável *abstract*.

A *indentação* também é considerada, caso não houvesse os
espaços antes da variável *affiliation* ela não estaria
relacionada a  *author*.

#### Inclusão de imagens no markdown (Pandoc)

A notação para inserir imagens no Markdown é simples, sendo de fácil
entendimento e utilização (Código Fonte \[code:imagem1\]). Se uma imagem
for grande demais, é possível alterar os atributos de resolução da
imagem em um editor de imagem externo.

Mas na prática, se desejamos redimensionar a imagem (sem alterá-la)
precisamos utilizar os recursos avançados do formato (ver Código Fonte
\[code:imagem1\]). Não há notação para inclusão da Fonte da imagem ou
Notas adicionais.

Também não há notação para referenciar a imagem no texto, apesar da
existência do atributo *id*.

### Docbook

O Docbook é um formato XML de produção de livros, criado pela editora
O’Reilly, especializada na produção e comercialização de livros
técnicos. O formato possui diversas versões que determinam todos os
aspectos do livro \cite{docbook-guide}. Estão disponibilizadas várias
ferramentas para converter o documento para apresentação em outros
formatos.[^5]

Na versão 5.0, o formato possui mais de 350 *tags* para
contemplar escrita dos livros e todos seus elementos: prefácio,
prêambulo, resumo, dedicatória, capítulo, glossário, sinópse, índice
remissivo, exemplos, quadros (notas, informações, atenção), códigos
fontes, etc. Com ele é possível configurar uma formatação de
apresentação uniforme para todos os elementos.

A complexidade dessas *tags* motivou a criação de uma
linguagem mais simples, mas que fosse capaz de aproveitar todas as
ferramentas compatíveis com formato DocBook: a Asciidoc.

### Asciidoc

A linguagem Asciidoc foi concebida para agilizar a produção de livros
técnicos no formato DocBook.[^6] Em vez de escrever o livro em XML, o
autor poderia utilizar a sintaxe do Asciidoc e exportar um arquivo em
conformidade com o padrão DocBook \cite{asciidoc}.

O Asciidoc possui sintaxe para criar vários elementos de um livro
compatível com o padrão Docbook, inclusive aceita inclusão de código
DocBook puro.

Suporta inclusão de arquivos externos, inclusive realizando
transformações automáticas através de filtros. É possível, por exemplo,
incluir o código fonte de um arquivo ou invocar um comando do sistema e
incluir seu resultado.

É expansível através da instalações de filtros. Existe filtros para
geração de QRCode, de diagramas UML, de partitura, etc.

A sintaxe de criação de tabelas permite mesclar células, configurar o
alingamento de colunas (ou de células individualmente), cabeçalho e
rodapé. É possível inclusão de dados externos, como um arquivo de texto
separado por vírgulas.

É possível referenciar automaticamente quase todos os elementos, tais
como: images, tabelas, capítulos, seções, códigos, quadros, etc.

Embora Asciidoc seja uma linguagem mais expressiva que Markdown, ela
exige que o usário conheça uma sintaxe maior de simbolos, os
significados e grafias de alguns termos em inglês (tais como: 
*image, table, witdh, footnote, preface*).

## Formulários em PDF ##

O formato PDF foi criado pela Adobe, mas atualmente é um formato aberto
mantido pela ISO. Além de textos e imagens, o formato permite a adição
de botões, *formulários*, áudio, vídeo e lógica de negócios
\cite{adobe-pdf}.

Através formulários é possível solicitar ao usuário, através de uma
interface amigável, informações que podem ser salvas e posteriormente
acessadas.

## ABNTFÁCIL ##

Existe um software nacional que implementa uma linguagem de marcação
própria, concebida especialmente para elaborar e formatar os trabalhos
acadêmicos em conformidade com as normas da ABNT.[^7]

O software mescla a utilização de uma linguagem de marcação com
configurações inseridas através de formulários. O processo de compilação
utiliza macros do MS-Word, que geram os documentos com a formatação
configurada.

Todas as *tags* são em português; algumas inspiradas nas
normas da ABNT: cap (Capítulo), QDR (Quadro), TAB (Tabela), sc01 (Seção
de nível 1), sc02(Seção de nível 2), int (Introdução), NRP (Nota de
rodapé), ctd (Citação direta). Outras foram inspiradas na nomenclatura
que o MS-Word utilizada para os recursos: mci (marcadores de itens –
lista não ordenada), mcl (marcadores com letras – lista ordenada com
letras), mcn (marcador de número – lista ordenada por números).

## Design de Liguagens para usabilidade ##

No estudo sobre a usabilidade de linguagens, as ferramentas de suporte à
linguagem exercem influências. \cite{green1989} apresenta uma pesquisa em que
foi criado um sistema cujo as entradas eram instruções da linguagem
Pascal, por comandos de voz (o propósto do sistema era possibilitar
decifientes físicos programarem). No entanto, o sistema permitia apenas
entradas válidas. Uma decisão do design do sistema causou uma limitação
na utilização da linguagem, pois exigia um esforço cognitivo enorme do
usuário para programar nesse ambiente.

O Design de uma linguagem deve levar em consideração aspectos de
usabilidade. Quem desejar implemetar uma nova linguagens encontrará
recomendações sobre o tema em \cite{pane1996}, \cite{green1989} e \cite{green1998}. O
desginer deverá ponderar sobre diversos aspectos da linguagem, entre
eles:

**Dependências explícitas ou impícitas**: A configuração de estilos em
cascata propaga as configurações do pais para os seus descendentes,
gerando uma dependência. Alterações em estilos pais podem causar
drásticas consequências no documento inteiro.

**Viscosidade**: Relativo a quanto uma linguagem resiste a alterações
locais. Por exemplo, em um texto com numeração de Figuras, a adição de
uma nova Figura no início do texto pode necessitar várias alterações.

**Compromisso prematuro**: O sistema pode proporcionar que o usuário
realize ações de acordo com fluxo natural de instruções que a mente (do
usuário) produz. O extremo contra exemplo seria a necessidade de
informar o texto numa ordem específica, como no caso do sistema de
reconhecimento de voz de Pascal apresentado anteriormente.

Cognitive Dimensions of Notations framework

## Dimensões cognitivas de notações ##

O framework de dimensões cognitivas de notações (*Cognitive
Dimensions of Notations framework*), foi desenvolvido para
assistir designers de sistemas de notações e informações para avaliar o
impacto que o design terá sobre os usuários desses sistemas
\cite{Blackwell2001}.

O objetivo do *framework* é ele proporcionar discussões para que o
Designer possa compreender as consequências cognitivas de suas
decisões. O *framework* não tem o propósito de guiar o desenvolvimento
de novas notações, e também não oferece critérios de *design* que
devem ser seguidos \cite{green1996usability}.

Nas seções seguintes são descritas as dimensões cognitivas apresentes
no *framework*.

Viscosity: resistance to change. A viscous system needs many user
actions to accomplish one goal. Changing all headings to upper-case may
need one action per heading. (Environments containing suitable
abstractions can reduce viscosity.) We distinguish repetition viscosity,
many actions of the same type, from knock-on viscosity, where further
actions are required to restore consistency.

Visibility: ability to view components easily. Systems that bury
information in encapsulations reduce visibility. Since examples are
important for problem- solving, such systems are to be deprecated for
exploratory activities; likewise, if consistency of transcription is to
be maintained, high visibility may be needed.

Premature commitment: constraints on the order of doing things.
Self-explanatory. Examples: being forced to declare identifiers too
soon; choosing a search path down a decision tree; having to select your
cutlery before you choose your food.

Hidden dependencies: important links between entities are not visible.

If one entity cites another entity, which in turn cites a third,
changing the value of the third entity may have unexpected
repercussions. Examples: cells of spreadsheets; style definitions in
Word; complex class hierarchies; HTML links. There are sometimes actions
that cause dependencies to get frozen – e.g. soft figure numbering can
be frozen when changing platforms; these interactions with changes over
time are still problematic in the framework.

Role-expressiveness: the purpose of an entity is readily inferred.
Role-expressive notations make it easy to discover why the programmer or
composer has built the structure in a particular way; in other notations
each entity looks much the same and discovering their relationships is
difficult. Assessing role-expressiveness requires a reasonable
conjecture about cognitive representations (see the Prolog analysis
below) but does not require the analyst to develop his/her own cognitive
model or analysis.

Error-proneness: the notation invites mistakes and the system gives
little protection. Enough is known about the cognitive psychology of
slips and errors to predict that certain notations will invite them.
Prevention (e.g. check digits, declarations of identifiers, etc) can
redeem the problem.

Abstraction: types and availability of abstraction mechanisms.
Abstractions (redefinitions) change the underlying notation. Macros,
data structures, global find-and-replace commands, quick-dial telephone
codes, and word-processor styles are all abstractions. Some are
persistent, some are transient. Abstractions, if the user is allowed to
modify them, always require an abstraction manager – a redefinition
sub-device. It will sometimes have its own notation and environment
(e.g. the Word style sheet manager) but not always (for example, a class
hierarchy can be built in a conventional text editor). Systems that
allow many abstractions are potentially difficult to learn.

Secondary notation: extra information in means other than formal syntax.
Users often need to record things that have not been anticipated by the
notation designer. Rather than anticipating every possible user
requirement, many systems support secondary notations that can be used
however the user likes. One example is comments in a programming
language, another is the use of colours or format choices to indicate
information additional to the content of text.

Closeness of mapping: closeness of representation to domain. How closely
related is the notation to the result it is describing?

Consistency: similar semantics are expressed in similar syntactic forms.
Users often infer the structure of information artefacts from patterns
in notation. If similar information is obscured by presenting it in
different ways, usability is compromised.

Diffuseness: verbosity of language. Some notations can be annoyingly
long-winded, or occupy too much valuable “real-estate” within a display
area. Big icons and long words reduce the available working area.

Hard mental operations: high demand on cognitive resources. A notation
can make things complex or difficult to work out in your head, by making
inordinate demands on working memory, or requiring deeply nested goal
structures.

Provisionality: degree of commitment to actions or marks. Premature
commitment refers to hard constraints on the order of doing things, but
whether ot not hard constraints exist, it can be useful to make
provisional actions – recording potential design options, sketching, or
playing “what-if” games.

Progressive evaluation: work-to-date can be checked at any time.
Evaluation is an important part of the design process, and notational
systems can facilitate evaluation by allowing users to stop in the
middle to check work so far, find out how much progress has been made,
or check what stage in the work they are up to. A major advantage of
interpreted programming environments such as BASIC is that users can try
out partially-completed versions of the product program, perhaps leaving
type information or declarations incomplete.

### Abstração ###




### Estudos empíricos

Os estudos sobre usabilidades de linguagens avançaram no área de
Linguagens de Programação. Kaijanaho propõe uma metodologia de design de
linguagens baseada em evidências, através da utilização de pesquisas
secundárias e avaliação das análises. \cite{@kaijano15}

Não temos conhecimento sobre estudos empíricos com linguagens de
marcação de texto, mas alguns princípios de linguagem de programação
podem ser utilizados.

## Considerações Finais ##

Na fundamentação teórica apresentamos as normas da ABNT, as regras para
utilizar ilustrações e a biblioteca abnTeX2, que possibilita compor
textos em com conformidade com as normas.

Em seguida apresentamos duas linguagens de marcação de texto: Markdown e
Asciidoc, com seu contexto de criação e suas limitações.

A ferramenta Pandoc, que implementa a linguagem Markdown, utiliza-se de
modelos Latex para geração de arquivos PDFs. Muitas configurações são
inseridas pelo usuário através de arquivos ou blocos no formato YAML,
que possui uma sintaxe bastante expressiva, mas um pouco complexa. A
sintaxe de inserção de imagens e tabelas não permite incluir a notas
explicativas ou informar a fonte da imagem.

O formato de arquivo PDF, bastante utilizado para publicação de texto,
também permite a inserção e extração de dados através do recurso de
formulários.

O sistema comercial ABNTFácil implementou uma linguagem de marcação
especializada para o público nacional, em que mesclou conceitos das
normas da ABNT com recursos do Word.

O Design de uma linguagem necessita de reflexões cognitivas de como
usuário irá interagir com ela através de um sistema. O ideal é que as
decisões da criação da linguagem estejam associadas a estudos empíricos.

# Trabalhos Relacionados

## R Markdown: linguagem para reprodutibilidade de pesquisas científicas ##

A linguagem R Markdown, suportada pela ferramenta RStudio, apresenta uma
variação da linguagem Markdown com o propósito de facilitar a 
*reprodutibilidade* de pesquisas científicas.

A *replicação* de uma pesquisa consiste em executar toda a
análise estatística novamente, gerar gráficos ou tabelas e incorporá-los
no documento final, no mesmo ambiente de trabalho. A
*reprodução* da pesquisa consiste em outro pesquisador ser
capaz de reproduzir os mesmos resultados em um ambiente de trabalho
diferente \cite{Gandrud2015}.

O R Markdown é essencialmente Markdown, mas possibilita a inserção de
blocos de instruções na linguagem R para realização de tratamentos
estatísticos (geração de gráficos, tabelas, etc.), que são executadas
em uma etapa anterior a compilação do documento.  Os pesquisadores que
desejam reproduzir uma pesquisa podem inspecionar as instruções
estatísticas e reproduzir os resultados, geralmente com acesso aos
mesmos dados da pesquisa.

## Análise de interfaces de softwares para composição de músicas e efeitos sonoros

Uma análise de interfaces utilizando o Framework de Dimensões
cognitivas foi realizada em \cite{Bellingham2014}. Nesse trabalho o
álvo da pesquisa eram interfaces de softwares de composição musical,
utilizando algoritmos parametrizados. O trabalho analisa diversas
interfaces, que incluem linguagens de programação visual, linguagens
de programação orientadas a textos, e softwares que solicitam dados do
usuário.

As análises das interfaces foram realizadas sem o envolvimento ativo
de usuários (utiliza opinião de *expert*), com execução dos sistemas e
em contextos não realísticos. A análise contemplou todas as 14
dimensões do *framework* de Dimensões Cognitivas.

### Discussão

A linguagem Makdown já foi extendida para contemplar

O surgumento de R Markdown mostra que a linguagem Markdown já foi
extendida para proporcionar produção de documentos acadêmicos
*e* reprodutibilidade de pesquisa.

A linguagem de marcação de texto Markdown não é expressiva o sufuciente
para atender as exigências das normas da ABNT para elaboração de
trabalhos acadêmicos.

A utilização da ferramenta Pandoc para formatação de um trabalho
acadêmico com as normas da ABNT requer a criação de um novo modelo (no
formato Latex, com estilos apropriados) que possa ser configurado
através das variáveis, especificadas nos blocos YAML pelo usuário final.






## Análise de usabilidade de ambientes de programação visual

O *framework* de Dimensões Cognitivas foi utilizado para avaliar
dois ambientes de programação visual em \cite{green1996usability}. 

## Avaliação de linguagem de programação utilizando o framework de Dimensões Cognitivas ##



## Considerações Finais ##

Nossa pesquisa busca criar uma nova linguagem para um contexto similar:
produção de textos acadêmicos nacionais (trabalhos de final de curso
como monografias).

[^1]: Tradução nossa do inglês *Lightweight markup
    language*.

[^2]: Atualmente possibilita ler os formatos Markdown, CommonMark, PHP
    Markdown Extra, GitHub-Flavored Markdown, reStructuredText, HTML,
    LaTeX, MediaWiki markup, TWiki markup, Haddock markup, OPML, Emacs
    Org mode, DocBook, txt2tags, EPUB, ODT e Word docx. Além desses
    formatos, a ferramenta também permite outros formatos de saída.

[^3]: Por exemplo, atualmente existem quatro opções de sintaxe para
    Tabelas

[^4]: Geralmente incluídas no início do documento

[^5]: O DBLatex é uma ferramenta livre que converte o texto em docbook
    para Latex e PDF.

[^6]: Formato XML, criado pela editora O’Reilly Media para editoração de
    livros: <http://www.docbook.org>.

[^7]: O software ABNTFÁCIL é comercializado através do site
    <http://abntfacil.com.br>.

# Proposta de dissertação #

Conforme descrito na Seção 1.2, o objetivo deste trabalho é <span>
*propor*</span> e <span>*validar a eficácia*</span> de uma linguagem de
marcação de texto especializada para a produção de trabalhos acadêmicos
em conformidades com as normas da ABNT.. Para alcançar este objetivo, os
seguintes passos serão seguidos:

-   Configuração de um modelo Latex parametrizado para utilização com a
    ferramenta Pandoc para geração de monografias com a formatação
    segundo as regras da ABNT.

-   Experimento de substituição de arquivo de configuração YAML por
    arquivo PDF com formulário.

-   Design de uma linguagem baseada em Markdown para possibilitar
    inclusão da Fonte das ilustrações, em conformidade com a ABNT.

-   Realização do experimento com grupo de usuários utilizando Latex e
    outro utilizando a linguagem criada.

-   Adicionar funcionalidade à linguagem para possibilitar incluir uma
    referência bibliográfica em qualquer lugar do documento.

-   Realização de teste de usabilidade referente à
    funcionalidade adicionada.

# Proposta de Avaliação Experimental #

## Proposta de Experimento ##

Serão conduzidos três experimentos:

-   Teste de eficácia da linguagem de marcação de texto.

-   Teste de eficácia da utilização de arquivos PDFs com formulários em
    substituição de arquivos de configuração no formato YAML.

-   Teste de usabilidade da funcionalidade *permitir inserir
    referencial teórico próximo da citação*.

### Plano do Experimento

Perguntas da pesquisa:

-   Pergunta 1: A troca de utilização do ambiente Latex por um ambiente
    com linguagem de marcação de texto (LMT) fará com que usuários
    formatem uma monografia em menos tempo?

-   Pergunta 2: A utilização de documentos PDF com formulários
    possibilita usuários realizar configurações com menos tempo e erros
    do que a configuração com arquivos no formato YAML?

-   Pergunta 3: Em textos científicos em que as referências são
    apresentadas no final do texto, os usuários gostarão da
    funcionalidade de poder redigir o texto da entrada de uma referência
    em qualquer lugar do documento?

Para responder as perguntas 1 e 2 serão realizados experimentos <span>
*t-test*</span> com no mínimo 40 participantes em cada grupo.

Hipóteses nulas:

-   HN1: A troca de utilização do ambiente Latex por um ambiente com
    linguagem de marcação de texto (LMT) não apresentará diferenças
    significativas em relação ao tempo de formatação de uma monografia.

-   HN2: A utilização de documentos PDF com formulários usuários não
    apresenta diferença significativa de tempo ou quantidade de erros em
    relação à utilização de arquivos no formato YAML.

A terceira pergunta será respondida através de análise qualitativa,
apresentando o percentual de usuários que gostaram e buscando
identificar o perfil deles.

### Planejamento de Execução

Os experimentos serão realizados com usuários de nível de instrução
superior incompleto ou superior.


# Conclusão e Cronograma #

![image](images/cronograma.png){width="100.00000%"}
