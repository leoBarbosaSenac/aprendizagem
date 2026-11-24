# Primeira aula: Introdução à programação, VS Code e HTML
------------------------------------------------------------------------

# 1. O que é programação?

Programar é escrever instruções para que o computador execute
determinadas tarefas.

O computador não entende nossas intenções. Precisamos explicar o que
queremos que ele faça por meio de instruções escritas em uma linguagem
que ele consiga interpretar ou executar.

Pense em uma receita de bolo: ela apresenta uma sequência de passos que
devem ser seguidos para chegar a um resultado. Um programa funciona de
maneira parecida: contém instruções organizadas para realizar uma
tarefa.

### Exemplos de coisas feitas com programação

-   Sites e lojas virtuais.
-   Aplicativos de celular.
-   Jogos.
-   Sistemas de bancos e escolas.
-   Aplicações utilizadas em empresas.
-   Programas que automatizam tarefas.

### Um exemplo simples

Imagine que queremos criar um programa que mostre uma mensagem na tela:

``` text
Mostre a mensagem "Olá, mundo!"
```

Essa é a ideia básica da programação: fornecer instruções para obter um
resultado.

Ao longo do curso, vamos aprender diferentes linguagens e ferramentas
para criar nossos próprios sistemas.

# 2. O que é uma IDE?

Para escrever programas, precisamos de um lugar onde possamos criar e
editar nossos arquivos de código.

Uma **IDE** (*Integrated Development Environment*, ou Ambiente de
Desenvolvimento Integrado) é uma ferramenta que reúne recursos para
ajudar no desenvolvimento de programas. Dependendo da ferramenta, ela
pode oferecer:

-   Editor para escrever código.
-   Organização dos arquivos do projeto.
-   Recursos para identificar erros.
-   Terminal para executar comandos.
-   Ferramentas para testar e depurar programas.

## Vamos utilizar o Visual Studio Code


O **Visual Studio Code**, também conhecido como **VS Code**, é um editor
de código muito utilizado por profissionais de desenvolvimento.

Tecnicamente, ele é um editor de código extensível, e não uma IDE
completa tradicional. Porém, com suas extensões e ferramentas, oferece
muitos recursos de um ambiente de desenvolvimento.

<img src="https://images-eds-ssl.xboxlive.com/image?url=4rt9.lXDC4H_93laV1_eHHFT949fUipzkiFOBH3fAiZZUCdYojwUyX2aTonS1aIwMrx6NUIsHfUHSLzjGJFxxj7kCzMIlSC20SNjaJf9GmESvWFqgy6FNrwzWSIu2lzePyWSz8zg09RAX43OFexidzEE3_7l3auaKk4w9ktJdqg-&format=source" width="400">

### Conhecendo o VS Code

Ao abrir o programa, encontramos algumas áreas importantes:

-   **Barra lateral:** permite acessar arquivos, pesquisar no projeto e
    gerenciar extensões.
-   **Explorador de arquivos:** mostra as pastas e os arquivos do
    projeto.
-   **Editor:** área central onde escrevemos nosso código.
-   **Terminal:** permite executar comandos sem sair do VS Code.
-   **Barra de status:** apresenta informações sobre o arquivo e o
    editor.

Não precisamos conhecer todas essas ferramentas agora. Vamos começar
criando nossos primeiros arquivos.

## 2.1. Criando nossa primeira pasta de projeto

Organizar os arquivos desde o começo é uma boa prática.

1.  Crie uma pasta no computador chamada `primeiro-projeto`.
2.  Abra o Visual Studio Code.
3.  Clique em **File (Arquivo) \> Open Folder (Abrir Pasta)**.
4.  Selecione a pasta `primeiro-projeto`.
5.  Confirme a abertura da pasta.

A pasta aparecerá no Explorador de arquivos, na lateral esquerda.

## 2.2. Criando um arquivo

1.  No Explorador de arquivos, clique no botão de novo arquivo.
2.  Digite o nome `index.html`.
3.  Pressione Enter.
4.  O arquivo será aberto na área de edição.

O nome `index.html` é bastante utilizado como arquivo principal de uma
página ou site.

A extensão `.html` identifica que esse arquivo contém código HTML.

------------------------------------------------------------------------

# 3. O que é HTML?

HTML significa **HyperText Markup Language** (Linguagem de Marcação de
Hipertexto).

É a linguagem utilizada para estruturar o conteúdo de páginas da
internet.

Com HTML, indicamos ao navegador quais elementos fazem parte da página,
como:

-   Títulos.
-   Parágrafos.
-   Imagens.
-   Links.
-   Listas.
-   Tabelas.
-   Formulários.

O HTML não é uma linguagem de programação tradicional. Ele é uma
linguagem de marcação: utilizamos elementos e tags para organizar e
identificar os conteúdos.

## 3.1. O que é CSS?

CSS significa **Cascading Style Sheets** (Folhas de Estilo em Cascata).

Enquanto o HTML organiza o conteúdo, o CSS define a aparência visual da
página.

Com CSS, podemos configurar:

-   Cores.
-   Fontes.
-   Tamanhos.
-   Espaçamentos.
-   Bordas.
-   Posicionamento dos elementos.
-   Adaptação da página para diferentes tamanhos de tela.

### HTML e CSS trabalham juntos

Imagine uma casa:

-   **HTML:** define a estrutura da casa, como paredes, portas e
    janelas.
-   **CSS:** define sua aparência, como cores, revestimentos e
    decoração.

Nesta primeira aula, vamos trabalhar somente com HTML. O CSS será
estudado em uma próxima aula.

------------------------------------------------------------------------

# 4. Nosso primeiro HTML

Abra o arquivo `index.html` que criamos e escreva o código abaixo:

``` html
<!DOCTYPE html>
<html>
    <head>
        <title>Minha primeira página</title>
    </head>

    <body>
        <h1>Olá, mundo!</h1>
        <p>Esta é minha primeira página HTML.</p>
    </body>
</html>
```

Salve o arquivo usando `Ctrl + S`.

Agora, abra a pasta do projeto no computador e dê dois cliques no
arquivo `index.html`. Ele deverá abrir no navegador.

Você acabou de criar sua primeira página HTML!

## 4.1. Entendendo a estrutura

Vamos compreender o que cada parte do código representa.

### `<!DOCTYPE html>`

Informa ao navegador que estamos utilizando a versão atual do HTML, o
HTML5.

### `<html>`

É o elemento principal do documento. Todo o conteúdo da página fica
dentro dele.

### `<head>`

Contém informações sobre a página que não são exibidas diretamente como
conteúdo principal.

Mais adiante, vamos conhecer outras informações que podem ficar nessa
área.

### `<title>`

Define o título da página, que aparece na aba do navegador.

### `<body>`

Contém os elementos que serão apresentados visualmente na página.

É dentro do `body` que vamos colocar títulos, textos, imagens, links e
outros conteúdos.

### `<h1>`

Representa o título principal da página.

### `<p>`

Representa um parágrafo de texto.

------------------------------------------------------------------------

# 5. O que são tags HTML?

As tags são utilizadas para identificar e organizar os elementos de uma
página HTML.

Normalmente, uma tag possui uma abertura e um fechamento:

``` html
<p>Este é um parágrafo.</p>
```

Observe:

-   `<p>`: tag de abertura.
-   `Este é um parágrafo.`: conteúdo.
-   `</p>`: tag de fechamento.

A barra `/` indica o fechamento da tag.

O conjunto formado pela tag de abertura, pelo conteúdo e pela tag de
fechamento é um elemento HTML.

## 5.1. Tags podem ficar dentro de outras tags

É comum colocar elementos HTML dentro de outros elementos. Isso é
chamado de aninhamento.

``` html
<body>
    <h1>Minha página</h1>

    <p>
        Estou aprendendo <strong>HTML</strong>.
    </p>
</body>
```

Nesse exemplo, o elemento `strong` está dentro do parágrafo.

É importante fechar as tags na ordem correta em que foram abertas.

## 5.2. Títulos: `h1` até `h6`

O HTML possui seis níveis de títulos:

``` html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Título de seção</h3>
<h4>Outro nível de título</h4>
<h5>Título de menor importância</h5>
<h6>Menor nível de título</h6>
```

O `h1` representa o título de maior importância, enquanto o `h6`
representa o de menor importância.

Essas tags não devem ser escolhidas apenas pelo tamanho visual. Elas
indicam a hierarquia e a importância dos títulos no conteúdo.

## 5.3. Parágrafos: `p`

Utilizamos a tag `p` para escrever parágrafos:

``` html
<p>Meu nome é Ana.</p>

<p>Estou aprendendo desenvolvimento de sistemas.</p>
```

Cada parágrafo é um elemento independente.

## 5.4. Quebra de linha: `br`

A tag `br` insere uma quebra de linha:

``` html
<p>
    Primeiro texto.<br>
    Segundo texto em outra linha.
</p>
```

Diferentemente da maioria das tags que vimos, `br` não precisa de uma
tag de fechamento.

Use `br` quando a quebra de linha fizer parte do conteúdo, e não para
criar grandes espaços entre elementos.

## 5.5. Destaque de texto: `strong` e `em`

Podemos indicar que uma parte do texto tem maior importância ou ênfase.

``` html
<p>Este conteúdo é <strong>muito importante</strong>.</p>

<p>Este conteúdo merece <em>ênfase</em>.</p>
```

-   `strong`: indica importância.
-   `em`: indica ênfase.

Os navegadores normalmente apresentam esses elementos em negrito e
itálico, respectivamente.

## 5.6. Listas

O HTML permite criar listas ordenadas e não ordenadas.

### Lista não ordenada: `ul`

Utilizada quando a ordem dos itens não é importante. Normalmente aparece
com marcadores.

``` html
<h2>Meus hobbies</h2>

<ul>
    <li>Jogar videogame</li>
    <li>Assistir filmes</li>
    <li>Ler livros</li>
</ul>
```

### Lista ordenada: `ol`

Utilizada quando os itens seguem uma sequência ou ordem.

``` html
<h2>Passos para estudar</h2>

<ol>
    <li>Abrir o material da aula</li>
    <li>Ler o conteúdo</li>
    <li>Praticar os exemplos</li>
</ol>
```

A tag `li` representa cada item da lista.

## 5.7. Links: `a`

A tag `a` cria links para outras páginas ou endereços da internet.

``` html
<a href="https://www.google.com">Acessar o Google</a>
```

Observe o atributo `href`. Ele indica o endereço para onde o link levará
o usuário.

# 6. Atributos HTML

Algumas tags podem receber informações adicionais chamadas
**atributos**.

Os atributos são escritos na tag de abertura e geralmente possuem um
nome e um valor.

Exemplo:

``` html
<a href="https://www.google.com">Google</a>
```

Nesse caso:

-   `href` é o nome do atributo.
-   `https://www.google.com` é o valor do atributo.

Outro exemplo:

``` html
<p title="Uma informação adicional">Passe o mouse sobre este texto.</p>
```

O atributo `title` fornece uma informação adicional que normalmente
aparece quando o usuário posiciona o mouse sobre o elemento.

# 7. Imagens: `img`

A tag `img` permite inserir imagens na página.

``` html
<img src="https://placehold.co/300x200" alt="Imagem de exemplo">
```

Observe os atributos:

-   `src`: indica o caminho ou endereço da imagem.
-   `alt`: fornece uma descrição textual da imagem.

A tag `img` não possui fechamento.

O atributo `alt` é importante para acessibilidade e também ajuda quando
a imagem não pode ser carregada.

## 7.1. Usando uma imagem salva no projeto

Também podemos utilizar imagens armazenadas no computador.

Organize a pasta desta maneira:

``` text
primeiro-projeto/
├── index.html
└── imagens/
    └── foto.jpg
```

O código para exibir a imagem será:

``` html
<img src="imagens/foto.jpg" alt="Descrição da fotografia">
```

O caminho informado em `src` deve corresponder ao local e ao nome do
arquivo.

------------------------------------------------------------------------

# 8. Comentários no HTML

Comentários são anotações escritas no código que não aparecem como
conteúdo da página.

Eles podem ajudar a explicar ou organizar partes do documento.

``` html
<!-- Este é um comentário HTML -->

<h1>Minha página</h1>
```

O navegador ignora o comentário ao exibir a página.

No VS Code, também podemos utilizar o atalho `Ctrl + ;` para inserir ou
alternar um comentário HTML quando o arquivo está sendo editado.

------------------------------------------------------------------------

# 9. Organizando nossa página

Agora que conhecemos algumas tags, vamos criar uma página um pouco mais
completa.

Substitua o conteúdo do arquivo `index.html` pelo exemplo abaixo:

``` html
<!DOCTYPE html>
<html>
    <head>
        <title>Sobre mim</title>
    </head>

    <body>
        <h1>Sobre mim</h1>

        <h2>Quem sou eu?</h2>

        <p>
            Meu nome é Ana e estou aprendendo
            desenvolvimento de sistemas.
        </p>

        <h2>Meus interesses</h2>

        <ul>
            <li>Tecnologia</li>
            <li>Música</li>
            <li>Jogos</li>
        </ul>

        <h2>Meu objetivo</h2>

        <p>
            Quero aprender a criar sites e sistemas.
        </p>

        <a href="https://www.google.com">Conhecer o Google</a>
    </body>
</html>
```

Salve o arquivo e atualize a página no navegador.

Observe como o HTML organiza os conteúdos. Ainda não estamos trabalhando
com cores, fontes ou posicionamento. Por enquanto, nosso objetivo é
construir a estrutura da página.

------------------------------------------------------------------------

# 10. Atividade prática: Minha primeira página

Agora é sua vez!

Crie uma página HTML apresentando você. Utilize o que aprendemos durante
a aula.

Sua página deverá conter:

1.  Um título principal com seu nome.
2.  Um subtítulo para apresentar quem você é.
3.  Um parágrafo falando um pouco sobre você.
4.  Um subtítulo para apresentar seus hobbies ou interesses.
5.  Uma lista não ordenada com pelo menos três hobbies ou interesses.
6.  Um subtítulo para falar sobre seus objetivos profissionais.
7.  Um parágrafo explicando o que você espera aprender no curso.
8.  Um link para um site de sua preferência.
9.  Uma imagem relacionada a você ou a algum de seus interesses.

**Atenção:** organize os elementos utilizando as tags corretas. Não
coloque todo o conteúdo em um único parágrafo e lembre-se de utilizar os
títulos de maneira hierárquica.

## Desafio extra

Crie uma segunda página chamada `contato.html`.

Nela, coloque:

-   Um título escrito "Contato".
-   Um parágrafo de apresentação.
-   Um link para voltar à página principal.

Para voltar à página principal, utilize:

``` html
<a href="index.html">Voltar para o início</a>
```

------------------------------------------------------------------------

# 11. O que aprendemos?

Nesta aula, conhecemos os primeiros conceitos do desenvolvimento web:

  -----------------------------------------------------------------------
  Conceito                            Para que serve?
  ----------------------------------- -----------------------------------
  Programação                         Criar instruções para o computador
                                      executar tarefas.

  IDE                                 Reunir ferramentas que auxiliam no
                                      desenvolvimento de software.

  VS Code                             Editar e organizar arquivos de
                                      código.

  HTML                                Estruturar o conteúdo de uma
                                      página.

  CSS                                 Definir a aparência visual de uma
                                      página.

  Tags                                Identificar e organizar elementos
                                      HTML.

  Atributos                           Fornecer informações adicionais aos
                                      elementos.
  -----------------------------------------------------------------------

Hoje, nosso foco foi aprender a estruturar uma página com HTML. Na
próxima etapa, vamos conhecer o CSS e começar a trabalhar com a
aparência visual dos nossos sites.
