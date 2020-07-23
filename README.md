  <h1 align="center">
    <a href="https://git-scm.com/">
      <img src="https://git-scm.com/images/logo@2x.png">
    </a>
  </h1>
  <h3 align="center">Comandos básicos</h3> </br>
  
***
## <a name="indice">Índice</a>
  1. [O que é o GIT ?](#o-que-e-git)
  2. [Instalando o GIT](#instalacao)
  3. [Configurando o GIT](#configurando)
  4. [Comandos básicos](#comandos-basicos)
  5. [Rastreando versões anteriores](#rastreando-versoes-anteriores)
  6. [Branchs / Ramificações](#ramificacoes)
  7. [Clonando repositórios](#clonando-repositorios)
  8. [Atualizando repositorio local](#atualizando-repositorio-local)
  
***

## <a name="o-que-e-git">1. O que é GIT ?</a>  
  O git é um sistema de gerenciamento de versões que armazena todas as mudanças realizadas em um projeto.  
  Com ele é possível recuperar versões anteriores desse projeto, que se enviado para um repositório remoto, 
  nesse caso, o GitHub, sua equipe poderá trabalhar junto nesse projeto.
  <br/><br/>[Voltar ao índice](#indice)

## <a name="instalacao">2. Instalando o GIT</a>
  Para começar a utilizar o GIT é necessário instalá-lo em sua máquina local, acessando o próprio site
  da ferramenta na seção de downloads.
  <br/><br/>
  [https://git-scm.com/downloads](https://git-scm.com/downloads)
  <br/><br/>[Voltar ao índice](#indice)
  
## <a name="configurando">3. Configurando o GIT</a>  
  Clicando com o botão direito do mouse dentro do projeto criado, selecione a opção `git bash here` como ilustrado
  na imagem abaixo.
  
  <p align="center">
    <img src="" alt="right mouse button click">
  </p>
  
  Após clicar, abrirá uma janela do git bash, então 2 comandos precisam ser executados uma única vez, sendo eles:
  - `git config --global user.name "Digite seu nome aqui"`
  - `git config --global user.email "Digite seu email aqui"`
  
  Com isso, seu nome e email já estarão configurados na sua máquina, e todos os commits que você realizar aparecerá essas
  informações para confirmar que foi você quem fez tais alterações, esse comando será abordado em seguida.
  <br/><br/>[Voltar ao índice](#indice)
  
## <a name="comandos-basicos">4. Comandos básicos</a>
  Alguns comandos essenciais para se trabalhar com versionamento são:
  - **git init**: Esse comando inicia uma pasta oculta com o nome de .git, com isso, se torna possível versionar o projeto
    localmente com o git.
    
  - **git add \<nomeArquivo.extensao\>**: O git add adiciona as alterações realizadas no projeto e as coloca em uma espécie de
    caixa/container, que irá guardar todas essas mudanças até que elas sejam "confirmadas". Digitando \* ao final do comando, fará
    com que todos os arquivos que possuem alguma alteração sejam adicionados nesse "container".
    
  - **git reset HEAD**: Comando utilizado para retirar essas mudanças adicionadas através do **git add**, caso alguma alteração
    tenha sido adicionada de forma equivocada.
  
  - **git status**: Este comando realiza a "consulta" e retorna o status atual do projeto, como por exemplo, se algum arquivo foi
    alterado e não executou o comando git add, se ja estão, entre outras informações.
  
  - **git commit -m "Comentário"**: O git commit é o comando que realiza a "confirmação" dessas mudanças adicionadas com o **git add**,
  passando junto um comentário para melhor entendimento do que foi alterado. Esse comando envia essas alterações para a pasta .git, e
  salvando-as com um código hash, único para aquele commit.
  
  - **git log**: É o comando que realiza a busca e mostra quem, quando e os comentários de todos os commits realizados até o momento no
    projeto, sendo possível também ver o código de cada commit.
    
    Imagem para ilustrar os comandos passados.
    
    <p align="center">
      <img src="" alt="comandos básicos">
    </p>
  
  <br/><br/>[Voltar ao índice](#indice)
  
## <a name="rastreando-versoes-anteriores">5. Rastreando versões anteriores</a>
  <br/><br/>[Voltar ao índice](#indice)
  
## <a name="ramificacoes">6. Branchs / Ramificações</a>
  <br/><br/>[Voltar ao índice](#indice)
  
## <a name="clonando-repositorios">7. Clonando repositórios</a>
  <br/><br/>[Voltar ao índice](#indice)
  
## <a name="atualizando-repositorio-local">8. Atualizando repositorio local</a>
  <br/><br/>[Voltar ao índice](#indice)
