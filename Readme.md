# Branch em equipe 

## Objetivo: 

Esse projeto é um paralelo com <a href="https://github.com/keelvinreis/conceitos-Git/blob/master/Readme.md">Readme</a> do Conceito Git com 3 pessoas fictícias, trazendo clareza das dúvidas: 

* Como é criada a Branch; 

*  Como fazer a fusão das ramificações implantando na versão principal; 

* Como trabalhar 2 ou + pessoas em 1 código; 

## Descrição: 

Cada dev irá criar e atuar em sua ramificação e no final todo o desenvolvimento irá se unificar a branch principal. 

**Obs:** O Css3 já estará pronto para não estender tanto. 

 ## Dev's: 

<img src="./Devs/Caio.png" width="200px">

<img src="./Devs/Mari.png" width="200px">

<img src="./Devs/Fernanda.png" width="200px"> 

 
* Caio - responsável pela Pagina index.html 

* Mari - responsável pela Pagina produtos.html 

* Fernanda - responsável pela Pagina contato.html 

## O projeto: 

 _Caio, Mari e Fernanda irão desenvolver um Web Site para uma Barbearia e como já conhecidos do Git e GitHub poderão tranquilamente trabalhar de maneira remota._ 

 1. *Caio se encarregaria de dar início ao repositório e deixar arquivos base para facilitar.* 

* Criou uma pasta `Projeto-Branch` na sua área de trabalho; 

* Salvou os arquivos base que havia feito no Vscode nessa Pasta `Projeto-Branch`; 

* `Abriu Git bash` c/ botão direito do mouse dentro dessa pasta; 

* Iniciou o repositório `Git init`; 

* Enviou todos os arquivos para o repositório Local `Git add .` e `Git commit -m "Primeira versão"` no ramo principal `Master/Main`; 

* Fez a criação do repositório no GitHub `Projeto-Exemplo-Branch`; 

* Fez a conexão do seu repositório local com o repositório do Github `Git remote add origin https://github.com/nomeUsuario/repositorioCriado.git`; 

* Fez o envio da Branch `Master` para o repositório do GitHub `Git push origin master` enviando master -> Origin;  

_Okay processo terminado._ 

## Criando uma Branch: 

_Como cada dev esta responsável por desenvolver páginas web diferentes a melhor pratica como já conhecido é criar outras ramificações do que trabalhar na Master onde é localizado o versionamento principal com tudo funcionando._ 

Cada dev fez a cópia para o seu desktop e cada um criou sua branch onde ficavam os seus commits e a cada ajuste no código terminado um commit novo. 

*Exemplo de como o Caio fez:* 

`Git checkout -b Caio-index` -> criou uma ramificação e saiu da master. 

`Git add index.html` -> após ter terminado o código. 

`Git commit -m "Caio | Segunda-Feira: Main e Section elaborados"` -> Commitando na branch criada. 

`Git Push origin Caio-index` -> Envio da nova Ramificação para o gitHub. 

## Criando uma Branch: 

Cada pessoa envolvida no projeto irá clonar o repositório e fazer o mesmo processo acima e fazendo seus commits em sua ramificação. 

Como aconteceu nesse projeto: 

<p align="center"> 

<img src="img/Branch01.png"> 

<p> 

## Trabalhando com 2 ou + pessoas: 

*Perceba que cada linha tem uma cor, cada uma dessas ramificações são pessoas participantes do projeto:* 

* Rosa-Fernanda; 

* Verde-Mari; 

* Laranja-Caio; 

* Azul-Master; 

De maneira clara, cada pessoa fez: 

 `Git Clone`  

`Git checkout -b [Nome da branch]` 

`Git Commit` 

Proporcionando o trabalho em equipe de maneira básica, cada um em um arquivo com acesso ao repositório do GitHub. 

### obs: 

Durante o desenvolvimento do projeto o segundo commit da master foi uma correção; 

## Detalhes: 

* E cada linha tem 2 pontos, isso significa que tem 2 commits por pessoa; 

Cada Branch tem seu nome como na Branch da Fernanda a qual podemos ver: 

<p align="center"> 

<img src="img/fernanda-branch02.png"> 

<p> 

* O nome da ramificação que está na Origin; 

* Os commits criados `Segunda` e de `terça feira` onde foi a sua última modificação; 

## Fusão das ramificações: 


Para se trazer o desenvolvimento de cada Dev para a versão de produção principal precisamos usar o `Git merge` 

### O que é o Merge: 

<p align="center"> 

Mesclagem é o jeito do Git de unificar um histórico bifurcado. O comando git merge permite que você pegue as linhas de desenvolvimento independentes criadas pelo git branch e as integre em uma ramificação única. 

<p> 

**Exemplo real aplicado nesse Projeto:** 

Temos esse grafo de commits com linhas independentes: 

<p align="center"> 

<img src="img/Branch01.png"> 

<p> 

Quando queremos unificar linhas individuais á versão principal `Master -> mesclar -> com a Fernanda` 

* `Git merge Fernanda-contato` -> cria um novo commit na master com os dados da Fernanda. 

* `Git merge Mari-produtos` -> cria um novo commit na master com os dados herdados da Fernanda e atualizando somente o `produtos.html`. 

* `Git merge Caio-index` -> cria um novo commit na master com os dados herdados da Fernanda e Mari atualizando somente o `index.html` 

Transformando visualmente e deixando o nosso trabalho dessa forma: 

<img src="img/git-merge.png"> 

### Analise do Grafo : 

Todos os pontos foram ligados a cada `git merge`. 

1. **Caio (Branch: Rosa):** 

 _Seus commits herdaram a primeira versão, logo após fez 2 commits 'Segunda'&'Terça' e fusão com o Merge gerando um novo Commit herdando todos os outros._ 

2. **Mari (Branch: Verde):** 

 _Seus commits herdaram o commit criado após primeira versão, logo após ela fez 2 commits 'Segunda'&'Terça' e fusão com o Merge gerando um novo Commit herdando o commit da Fernanda e toda master anterior._ 

3. **Fernanda (Branch: Laranja):** 

 _Seus commits herdaram o commit criado após primeira versão, logo após ela fez 2 commits 'Segunda'&'Terça' e fusão com o Merge gerando um novo Commit._ 