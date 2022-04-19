<h4 align="center"> 
	🚀 Em construção...  🚧
</h4>

# Branch em equipe
## Objetivo:
Esse projeto é um paralelo com <a href="https://github.com/keelvinreis/conceitos-Git/blob/master/Readme.md">Readme</a> do Conceito Git com 3 pessoas ficticias, trazendo clareza das dúvidas:
* Como é criada a Branch;
*  Como fazer a fusão das ramificações implantando na versão principal;
* Como trabalhar 2 ou + pessoas em 1 codigo;

## Descrição:
Cada dev ira criar e atuar em sua ramificação e no final todo o desenvolvimento irá se unificar a branch principal.

**Obs:** O Css3 já estara pronto para não estender tanto.
 ## Dev's:
 
<img src="./Devs/Caio.png" width="200px"><img src="./Devs/Mari.png" width="200px"><img src="./Devs/Fernanda.png" width="200px">

* Caio - responsavel pela Pagina index.html

* Mari - responsavel pela Pagina produtos.html

 * Fernanda - responsavel pela Pagina contato.html
 
## O projeto:
 _Caio, Mari e Fernanda irão desenvolver um Web Site para uma Barbearia e como já conhecidos do Git e GitHub poderão tranquilamente trabalhar de maneira remota._

 1. *Caio se encarregaria de dar inicio ao repositorio e deixar arquivos base para facilitar.*

* Criou uma pasta `Projeto-Branch` na sua área de trabalho;

* Salvou os aquivos base que havia feito no Vscode nessa Pasta `Projeto-Branch`;

* `Abriu Git bash` c/ botão direito do mouse dentro dessa pasta;

* Iniciou o repositorio `Git init`;

* Enviou todos os arquivos para o repositorio Local `Git add .` e `Git commit -m "Primeira versão"` no ramo principal `Master/Main`;

* Fez a criação do repositorio no GitHub `Projeto-Exemplo-Branch`;

* Fez a conexão do seu repositorio local com o repositorio do Github `Git remote add origin https://github.com/nomeUsuario/repositorioCriado.git`;

* Fez o envio da Branch `Master` para o repositorio do GitHub `Git push origin master` enviando master -> Origin; 

_Okay processo terminado._

## Criando uma Branch:
_Como cada dev esta responsavel por desenvolver paginas web diferentes a melhor pratica como já conhecido é criar outras raficações do que trabalahar na Master onde é localizado o versionamento principal com tudo funicionando._

Cada dev fez a copia para o seu desktop e cada um criou sua branch onde ficavam os seus commits e a cada ajuste no codigo terminado um commit novo.

*Exemplo de como o Caio fez:*

`Git checkout -b Caio-index` -> criou uma ramificação e saiu da master.

`Git add index.html` -> após ter terminado o codigo.

`Git commit -m "Caio | Segunda-Feira: Main e Section elaborados"` -> Commitando na branch criada.

`Git Push origin Caio-index` -> Envio da nova Ramificação para o gitHub.

## Criando uma Branch:
Cada pessoa envolvida no projeto ira clonar o repositorio e fazer o mesmo processo acima e fazendo seus commits em sua ramificação.

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
Proporcionando o trabalho em equipe de maneira basica, cada um em um arquivo com acesso ao repositorio do GitHub.

### obs:
Durante o desenvolvimento do projeto o segundo commit da master foi uma correção;

## Detalhes:
* E cada linha tem 2 pontos, isso significa que tem 2 commits por pessoa;

Cada Branch tem seu nome como na Branch da Fernanda a qual podemos ver :
<p align="center">
<img src="img/fernanda-branch02.png">
<p>

* O nome da ramificação que esta na Origin;

* Os commits criados `Segunda` e de `terça feira` onde foi a sua ultima modificação;

## Fusão das ramificações:



