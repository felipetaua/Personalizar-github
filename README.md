<h1 align="center"> Como criar e personalizar o Readme dos seus projetos </h1>

:wink: Neste artigo você aprenderá como personalizar o readme dos seus projetos no github. <br>

Mais o que seria README (ou leia-me)? Bem, é um arquivo com extensão .md, 
ou seja ele é escrito em Markdown Syntax que é uma sintaxe usada para padronizar e facilitar a formatação de texto na web.


##  :bulb: Porque é importante? 
Bem, depois de desenvolver seu projeto e subir no  github você vai documentar o seu trabalho para que quem visite seu repositório saiba do que se trata.
E podemos fazer isso por meio do README, que é o primeiro arquivo a ser visto, ou seja, é a porta de entrada para o seu projeto! 
- :rocket: Além disso, algumas pessoas utilizam o perfil GitHub como portfólio, se esse for o seu caso, é interessante apostar em arquivos README para deixar seus projetos mais atrativos até mesmo para recrutadores.
<br>

## Alguns exemplos do que ter no README
- Título e Imagem de capa;
- Badges;
- Índice;
- Descrição do Projeto;
- Status do Projeto;
- Funcionalidades e Demonstração da Aplicação;
- Acesso ao Projeto;
- Tecnologias utilizadas;
- Pessoas Contribuidoras;
- Pessoas Desenvolvedoras do Projeto;
- Licença.


## :pushpin: Título e Imagem de capa:
Você pode colocá-lo dessa maneira:

```Markdown
# Título 
```
<br>
Ou, caso queira colocar ele centralizado, você pode utilizar tags do HTML que funcionam normalmente, dessa forma:

```HTML
<h1 align="center"> Seu título aqui </h1>
```
>Obs: Feito isso, caso queira, você pode fazer uma capa ou logo do projeto para colocar após o título. 
<br>

## :pushpin: Badges:
Seus objetivos são indicar o estado atual do projeto, licença (caso tenha), versões, dependências, testes, dentre outros.
Caso queira fazer suas badges, você pode utilizar o [Shields.io](https://shields.io/), ele fornece na página principal diversos exemplos de Badges e, 
além disso, nele você pode colar o link do seu repositório do GitHub na caixa de texto inicial, assim automaticamente ele irá sugerir algumas Badges 
para você utilizar no seu projeto, fornecendo o link da Badge para copiar e colar no seu README.

Exemplo: 

![status](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

Caso queira deixar centralizado, pode utilizar a tag align do HTML também, dessa forma:

```HTML
<p align="center"><img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/></p>
```
<br>

## :pushpin: Índice: 
O GitHub gera automaticamente um índice para arquivos README, tendo como base os títulos de seção. Para visualizá-lo, selecione o ícone de menu no canto superior 
esquerdo do arquivo. É uma ferramenta excelente para navegar pelo documento, pois redireciona o usuário para o tópico selecionado.
Entretanto, caso você tenha interesse em fazer seu próprio índice para ser visualizado no arquivo, também é possível fazer em Markdown.
Exemplo:

```Markdown
## Índice 
* [Título e Imagem de capa](#Título-e-Imagem-de-capa)
* [Badges](#badges)
* [Índice](#índice)
* [Descrição do Projeto](#descrição-do-projeto)
* [Status do Projeto](#status-do-Projeto)
* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Pessoas Contribuidoras](#pessoas-contribuidoras)
* [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras)
* [Licença](#licença)* [Conclusão](#conclusão)
```
<br>

## :pushpin: Descrição do Projeto:
Como é um objetivo do arquivo README descrever o projeto, é legal que você apresente logo após o título ou imagem de capa e/ou Badges caso tenha, uma breve explicação do seu projeto com seu objetivo principal.
<br>

## :pushpin: Status do Projeto:
Caso você opte por não utilizar Badges sobre o status do projeto, é interessante que você coloque essa informação no próprio texto mesmo. 
Exemplo:

```Markdown
> :construction: Projeto em construção :construction:
```

Caso queira centralizar:

```HTML
<h4 align="center">    
 :construction:  Projeto em construção  :construction:
</h4>
```

>Nesse exemplo foi utilizado o emoji :construction:, mas você pode utilizar em qualquer lugar do arquivo, como antes dos subtítulos. Nesse [Gist do Rafael Xavier de Souza](https://gist.github.com/rxaviers/7360908), você pode encontrar uma variedade de emojis para utilizar no seu README e deixá-lo mais descontraído.

<br>

## :pushpin: Funcionalidades e Demonstração da Aplicação:
Você pode listar as funcionalidades do seu projeto para facilitar o entendimento do usuário. 

Para isso, você pode fazer dessa maneira:
```Markdown
# :hammer: Funcionalidades do projeto
- `Funcionalidade 1`: descrição da funcionalidade 1
- `Funcionalidade 2`: descrição da funcionalidade 2
- `Funcionalidade 2a`: descrição da funcionalidade 2a relacionada à funcionalidade 2
- `Funcionalidade 3`: descrição da funcionalidade 3
```

Além disso, se for possível, é interessante apresentar as funcionalidades com um exemplo visual do projeto, como gif, imagens ou vídeo.
>Obs.: Lembrando que o procedimento para colocar gif é o mesmo adotado para imagens e você pode gravar gifs com gravadores de tela, como o [Acethinker](https://www.acethinker.com/).
<br>

## :pushpin: Acesso ao projeto:
Caso o seu projeto esteja no ar com algum serviço de hospedagem, você pode disponibilizar o link para o mesmo. Caso contrário, você pode apostar em gifs e imagens, 
como citado anteriormente, bem como indicar como o usuário pode baixar o projeto, abrir e executar.

Isso pode ser feito em Markdown:

```Markdown
## 📁 Acesso ao projeto
**Indique como é possível baixar ou acessar o código fonte do projeto, seja projeto inicial ou final**
## 🛠️ Abrir e rodar o projeto
**Apresente as instruções necessárias para abrir e executar o projeto**
```
<br>

## :pushpin: Tecnologias utilizadas:
Você também pode citar as tecnologias utilizadas no projeto, é uma ótima forma de demonstrar o que você anda estudando nesse mar que é a tecnologia.

![readme](https://user-images.githubusercontent.com/100203503/167860481-9f2cb8bf-2bc2-4454-a8d7-9c7c26dd5f4a.png)

<br>

Ou colocar os ícones das tecnologias utilizadas: 

![docmreadme PNG](https://user-images.githubusercontent.com/100203503/167860788-72093b39-19bd-40f7-991b-6ef9188128cf.png)

<br>

## :pushpin: Pessoas Contribuidoras: 
Caso o seu projeto tenha contribuidores, é bacana adicionar eles no README. Um exemplo fantástico disso é o Docusaurus, onde se tem as fotos de todos
os contribuidores e um link para outro documento markdown com recados importantes para quem deseja contribuir também.
<br>

## :pushpin: Pessoas Desenvolvedoras do Projeto:
E agora entra você! É importante que você coloque sua foto também, caso não goste de fotos, vale o user padrão do GitHub ou fazer seu próprio Octocat. Além disso,
você pode linkar seu usuário, para caso algum usuário queira entrar em contato ou reportar algo.

```HTML
# Autores
| [<img src="https://avatars.githubusercontent.com/u/37356058?v=4" width=115><br><sub>Camila Fernanda Alves</sub>](https://github.com/camilafernanda) |  [<img src="https://avatars.githubusercontent.com/u/30351153?v=4" width=115><br><sub>Guilherme Lima</sub>](https://github.com/guilhermeonrails) |  [<img src="https://avatars.githubusercontent.com/u/8989346?v=4" width=115><br><sub>Alex Felipe</sub>](https://github.com/alexfelipe) |
| :---: | :---: | :---: |
```

<br>

## :pushpin: Licença:
Geralmente, os repositórios públicos no GitHub são utilizados para compartilhar softwares de código aberto. Porém, para que um repositório seja realmente de código 
aberto, ele precisa ter uma licença dando aos outros usuários a liberdade de usar, alterar e distribuir o software.
Portanto, caso seu repositório tenha uma licença, é essencial que você coloque ela no seu README. 

![licenciareadme](https://user-images.githubusercontent.com/100203503/167861625-7edfe705-2ee2-456d-9744-de94dcc59941.png)

<br>

## :pencil: Documentação e informação extra:
- https://gist.github.com/reginadiana/e044fe93ed81aa04a10361cb841c0409
- https://github.com/othneildrew/Best-README-Template
- https://www.alura.com.br/artigos/escrever-bom-readme
- https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open

## 🧰 Recursos úteis

Você pode encontrar algumas dessas ideias na ferramenta [README Creator](https://readmecreator.herokuapp.com/), site simples que reúne alguns recursos úteis para criação de READMEs de projetos, assim como para perfis. Após preencher os campos adequados e explorar os recursos, ele gerará um README no formato HTML/MD que você poderá continuar editando e adaptando.

<!--  Title -->
<div align="center">  
  <h1>
      <img height="30" src="https://emojis.slackmojis.com/emojis/images/1600706728/10521/meow_code.gif?1600706728">
          Hello World! I'm Tauã Felipe
      <img height="30" src="https://emojis.slackmojis.com/emojis/images/1600706728/10521/meow_code.gif?1600706728">
  </h1>
</div>
<!-- /Title -->

<!--  Git Stats -->
<div align="center">
  <a href="https://github.com/felipetaua">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=felipetaua&title_color=c9d1d9&icon_color=c9d1d9&text_color=c9d1d9&bg_color=0d1117&border_color=c9d1d9&show_icons=true&include_all_commits=true&count_private=true"/>
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=felipetaua&layout=compact&title_color=c9d1d9&icon_color=c9d1d9&text_color=c9d1d9&bg_color=0d1117&border_color=c9d1d9%22"/>
  </a>
</div>
<!-- /Git Stats -->
<br>
<!--  Skills -->
<div align="center" >
    <a href="#">
        <img alt="React" src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAF">
        <img alt="React Native" src="https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB">
        <img alt="Expo" src="https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37">
        <img alt="Node.js" src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white">
        <img alt="Redux" src="https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white">
        <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
        <img alt="Python" src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white">
        <img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white">
        <img alt="C#" src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white">
        <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
        <img alt="CSS" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
        <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white">
        <img alt="MySQL" src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white">
        <img alt="Firebase" src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase">
    </a>
</div>
<!-- /Skills -->

<!--  Contacts -->
<h1 align="center">Where to find me <img height="33" src="https://emojis.slackmojis.com/emojis/images/1619053233/32375/knuddels_spy.gif?1619053233"></h1>

<div align="center">
    <a href="https://api.whatsapp.com/send/?phone=5511989247421&text=Olá%2C+vi+o+seu+GitHub+e+queria+conversar+com+você%21&type=phone_number&app_absent=0" target="_blank"><img alt="Logo WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"></a>
    <a href="https://www.linkedin.com/in/felipetaua" target="_blank"><img alt="Logo Linkedin" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
    <a href="https://t.me/felipetaua" target="_blank"><img alt="Telegram Logo" src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"></a>
    <a href="mailto:taua.felipee@live.com" target="_blank"><img alt="Gmail Logo" src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
</div>
<!-- /Contacts -->

> BY: Juvenal Culino

> Conteúdo feito para ajudar novos usuários à personalizar seus githubs
## Header
```

# Titulo 
ou
<h1 align="center"> Titulo </h1>

## Descrição do Projeto
<p align="justify"> Escrever descrição, que ficará com texto justificado </p>

A tag align é usada para alinhar os elementos e assume left por padrão.
```
<img src="https://github.com/juvenalculino/imagens/blob/master/img/header.png">



# Como adicionar badges
#### [>>> Repositório com os logos <<<](https://simpleicons.org)


![Badge](https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT)
<img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/>
<img src="https://img.shields.io/static/v1?label=Netlify&message=deploy&color=blue&style=for-the-badge&logo=netlify"/>
<img src="http://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
<img src="http://img.shields.io/static/v1?label=Ruby&message=2.6.3&color=red&style=for-the-badge&logo=ruby"/>
<img src="http://img.shields.io/static/v1?label=Ruby%20On%20Rails%20&message=6.0.2.2&color=red&style=for-the-badge&logo=ruby"/>
<img src="http://img.shields.io/static/v1?label=TESTES&message=%3E100&color=GREEN&style=for-the-badge"/>
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge"/>
<img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge"/>


```
Podemos fazer isso a partir de uma URL como esta:
https://img.shields.io/static/v1?label=<LABEL>&message=<MESSAGE>&color=<COLOR>&style=<STYLE>&logo=<LOGO>
<img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/>
<img src="https://img.shields.io/static/v1?label=Netlify&message=deploy&color=blue&style=for-the-badge&logo=netlify"/>
<img src="http://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
<img src="http://img.shields.io/static/v1?label=Ruby&message=2.6.3&color=red&style=for-the-badge&logo=ruby"/>
<img src="http://img.shields.io/static/v1?label=Ruby%20On%20Rails%20&message=6.0.2.2&color=red&style=for-the-badge&logo=ruby"/>
<img src="http://img.shields.io/static/v1?label=TESTES&message=%3E100&color=GREEN&style=for-the-badge"/>
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge"/>
<img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge"/>

Onde cada parâmetro significa:

LABEL texto do campo esquerdo
MESSAGE texto do campo direto
COLOR cor do campo direito (as opções podem ser encontradas no site)
STYLE estilo do badge inteiro. Podemos ter: plastic, flat, for-the-badge, social ou flat-square.
LOGO logo do campo esquerdo

Como exemplo, vou escolher os seguintes parâmetros:

LABEL como react
MESSAGE como framework
COLOR como blue
STYLE como for-the-badge
LOGO como REACT

Podemos colocar ele no README assim:
<img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/>

ou ainda:
![Badge](https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT)
```


# Ênfase
<img src="https://github.com/juvenalculino/imagens/blob/master/img/enfase.png">


# Lista Ordenada
<img src="https://github.com/juvenalculino/imagens/blob/master/img/listaordenada.png">


# Lista Não Ordenada
<img src="https://github.com/juvenalculino/imagens/blob/master/img/listanaoirdenada.png">


# Links
<img src="https://github.com/juvenalculino/imagens/blob/master/img/links.png">


# Quotes
<img src="https://github.com/juvenalculino/imagens/blob/master/img/quotes.png">


# TaskLists
<img src="https://github.com/juvenalculino/imagens/blob/master/img/tasklist.png">


# Código
<img src="https://github.com/juvenalculino/imagens/blob/master/img/codigo.png">

# Tabelas
<img src="https://github.com/juvenalculino/imagens/blob/master/img/tabelas.png">


# Imagens ou Gifs
<img src="https://github.com/juvenalculino/imagens/blob/master/img/imagensougif.gif">

### OU

<img src="https://github.com/juvenalculino/imagens/blob/master/img/imgougif2.png">


# Emojis
#### [>>> Repositório com emojis <<<](https://gist.github.com/rxaviers/7360908)

## O que a plataforma é capaz de fazer :checkered_flag:
```
:trophy: Gerar PDF do certificado com as informações preenchidas no formulário para cada participantes para envio de e-mail 

:trophy: Check-list de participantes, permitindo selecionar quem irá receber os certificados 

:trophy: Permite que o organizador do evento escreva sua assinatura digital dentro da plataforma
```
:trophy: Gerar PDF do certificado com as informações preenchidas no formulário para cada participantes para envio de e-mail 

:trophy: Check-list de participantes, permitindo selecionar quem irá receber os certificados 

:trophy: Permite que o organizador do evento escreva sua assinatura digital dentro da plataforma


# Status do projeto
```
> Status do Projeto: Concluido :heavy_check_mark:

> Status do Projeto: Em desenvolvimento :warning:
```
> Status do Projeto: Concluido :heavy_check_mark:

> Status do Projeto: Em desenvolvimento :warning:


# Deploy da aplicação
> Se for possível subir a aplicação com Netlify ou outras plataformas que permitem com que as pessoas acessem o seu projeto sem ter o trabalho de rodar em suas maquinas é ótimo, isso poupa tempo e paciência. Se tiver, coloque na documentação:

```
## Deploy da Aplicação com Netlify: :dash:

/* Aqui estamos usando a tag Quotes do markdown*/

> https://certificates-for-everyone-womakerscode.netlify.app/
```
## Deploy da Aplicação com Netlify: :dash:

/* Aqui estamos usando a tag Quotes do markdown*/

> https://certificates-for-everyone-womakerscode.netlify.app/


# Destaques para os contribuidores
```

Quando fizer aquele projeto em grupo ou receber alguma Pull Request como contribuição destaque-os. Uma coisa bem bacana aqui é misturar imagens com tabelas:

[<img src="https://avatars2.githubusercontent.com/u/46378210?s=400&u=071f7791bb03f8e102d835bdb9c2f0d3d24e8a34&v=" width=115 > <br> <sub> Diana Regina </sub>](https://github.com/Diana-ops) |
| :---: | 

Confuso? Calma que eu explico.

Dentro de || temos uma tag html <img>, nela foi definido o link e o tamanho da imagem com src e width. Aqui foi inserido o avatar do dev.

Depois temos a tag <br>, que faz uma quebra de linha com o próximo elemento colocando-o em baixo da imagem.

Dentro de <sub> colocamos o nome dele.

Em seguida, juntamos a imagem e o nome dentro de [] seguido do link do github em ()

Por fim, os elementos são organizados em uma 'micro tabela', obtendo como resultado algo parecido com:

Para inserir mais devs, basta adicionais mais colunas.

```
[<img src="https://avatars2.githubusercontent.com/u/46378210?s=400&u=071f7791bb03f8e102d835bdb9c2f0d3d24e8a34&v=" width=115 > <br> <sub> Diana Regina </sub>](https://github.com/Diana-ops) |
| :---: | 


# Tabela de conteúdo

```
Fechando com chave de ouro
Ufa, depois de ter mais esse trabalhão escrevendo a documentação podemos fazer uma lista de conteúdos (como se fosse um sumário) lá no começo do README.md que irá ajudar o visitante a ir direto ao tópico que ele quer.
### Tabela de Conteúdos
   * [Nome do tópico visivel](#nome-do-tópico)
   * [Nome do tópico visivel](https://www.google.com/)

### Nome do Tópico
⚠️ Para referenciar o tópico substitua letras maiúsculas por minusculas
⚠️ Caso o tópico tenha traços, ponto de interrogação e exclamação escreva como se não tivesse, pois o markdown não consegue encontrar.
⚠️ Caso o tópico esteja acompanhado de um emoji, escreva-o ignorando o simbolo ::
```
### Tabela de Conteúdos
   * [Nome do tópico visivel](https://github.com/juvenalculino/Cursos-Em-Andamento/edit/master/Git-Github/Aula%2007/README.md)


# Personalizar Perfil página inicial

## Primeiro passo

#### * Criar um repositório com o seu nome de usuário

<img src="https://github.com/juvenalculino/imagens/blob/master/img/Criar-novo-Repositório-1.png">

## Segundo passo

#### * Criar um arquivo README.md e aplicar todas as dicas anteriores

<img src="https://github.com/juvenalculino/imagens/blob/master/img/segundopasso.png">

## BY: Juvenal Culino


### Ferramentas extra
- https://readme.so/pt
- https://www.readme-templates.com/
- https://github.com/Ileriayo/markdown-badges

