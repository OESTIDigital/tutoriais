# Git e Github para Iniciantes 

:octocat:

Esse tutotial tem como objetivo ser um guia para uso do Git e GitHub.

Se você tem alguma sugestão de melhoria para esse texto abra uma [issue](https://github.com/OESTIDigital/tutoriais/issues) ou se preferir você pode enviar um [pull request](https://github.com/OESTIDigital/tutoriais/pulls) com as modificações 🐞.

## Objetivos

- Entender o que é controle de versão.
- Principais comandos do Git.
- Como usar o GitHub.
- Aprender a compartilhar seu código.

## Material complementar

É importante que você consulte outras fontes de informação, nós separamos alguns conteúdos com mais detalhes de como você pode utilizar o Git e GitHub.

#### Livro

- https://www.casadocodigo.com.br/pages/sumario-git-github

### Curso

- http://willianjusten.teachable.com/courses/git-e-github-para-iniciantes
	
### Videos recomendados 

- https://www.youtube.com/watch?v=TReVFOxhh7E
- https://www.youtube.com/watch?v=Fc_UC5SywuU
- https://www.youtube.com/watch?v=Ahv6vPTZJqk
- https://www.youtube.com/watch?v=UMhskLXJuq4
- https://www.youtube.com/watch?v=neDiLHwXSVo
- https://www.youtube.com/watch?v=yNwh0S0S0bU

> Dica: No Youtube você pode aumentar a velocidade de execução do vídeo para 1.5x

### Mitos

- Git e GitHub é dificil.
- Medo de usar linha de comando.
- O que eu estou escrevendo não é bom.

### Motivação

- No seu computador ninguem ve o seu potencial.
- O GitHub é seu portifólio.
- O código não é só seu, compartilhe ele.
- Você pode ajduar muitas pessoas a escreverem software com mais qualidade.

### Compartilhamento de Código

- Contribuindo com projetos open source
- De like em projetos que você gostou e usou
- Escreva código e libere no GitHub
- Crie Gists
- Escreva seus prórpios projetos
- Compartilhe os projetos que você esta usando
- Crie um blog e escreva sobre o que você esta fazendo
- Participe de eventos e ajude a organizar

## Entendendo o Git & GitHub

### Git

Um sistema de controle de versão tem a finalidade de gerenciar modificacoes em arquivos, um arquivo sofre muitas alteraçoes durante o seu uso sendo necessário manter um histórico dessas alteraçoes para posterior manipulação, por exemplo, voltar o aquivo para uma versão especifica. 

No que diz respeito a código é essecial o controle de versao, pois com isso conseguimos vincualar uma documentação das alteracóes, comparar diferentes versoes e saber o que foi alterado e por que, entre outras vantagens. Em projetos de software o controle de versão esta diretametne vonculado ao trabalho em equipe onde muitas pessoas fazem diferentes alteracoes em arquivos, exigindo a mesclagem desse trabalho.

Em um sistema de contrle de versao nos tempo um repositório onde obtemos as versoes do projeto ou de algum arquivo em especifico, a mesclagem desses arquivo pode ocorrer de foram automatica ou no caso de comflitos exige a intervncao manual.

O Git é um sistemas de controle de versão distribuido onde os usuários tem uma cópia dos repositórios em sua maquina, isso permite que você cosiga fazer alteraçoes e commits sem estar necessriamente a um repositório remoto.

Exetem outros sistemas de controle de versão basedos no modelo cliente servidor, como por exemplo o SVN, esse sistemas exigem que você tenha um servidor remoto para poder realizar alteracoes e commits.

Criado em 2005 por Linus Torvals para manter o kernel do Linux, o uso do Git em engenharia de software a Gerencia de Configuracao de Software, onde mantemos informações do que mudou, quando mudou, porque mudou é uma docmunentacao vinculada a versão dos arquivos.

O Git é utilicados por inumeras empresas é saber como utilziar ele é uma habildiade indispensavel para uma carreira bem sucessidade no desenvolvimento de software.

### Instanado o Git

O processo de isntalacao é bem simples, acesse a página https://git-scm.com/downloads escolha o sistemas operacional que voce esta utilizando e sigua as instruções de intralacao.

Eu recomendo fortemente o uso de linha de comandos para trabalhando com o Git, você pode utilizar alguma GUI para complementear o uso da linha de comando, como pode exemplos ver os logs de commit, arvore de commits, diff de commits, etc.

Nesse site, https://git-scm.com/downloads/guis, você pode verificar algumas alternativas para GUI Clientes

Para complementar o estudo faça o [Git Tutorial](https://try.github.io/)

Outras ferramentas alem do Git: SVN; Mercurial; CSV; Bazzar; Microsoft TFS

### GitHub

É um serviço Web utilziar para hospedar repositórios Git, ele tem é uma rede social voltada para desenvolvedores com bastatne influencia na comunidade open Source, surgiu em 2008, e é utilziado por inumeras empresas importantes como: Google; Nasa; Linekdin; Facebook; Twiiter; Contentools; RDStaton; Globo; NetFlix; Spotyfy que possuem projetos hospedados no GitHub.

Exsistem muuitas funcionaldaide que pdoem ser utilizadas pelo desenvolcedores:

- Wiki do projeto
- Colaboradores 
- Issue
- Releases
- Follow
- Whatch 
- Start 

Alem do GitHub temos outras alternaricas como: GitLab; BitBuckets e SourceForge.

O GitHub é muito utilizado para hosedar projetos Open SOurce, logo os seu repositório são publocis, existe a versao paga que permite ter repositórios privados para empresas utilizarem.

Nos precisamos mostrar para o mundo que o nosso código, e para isso nos podemos utilziar o GitHub, se você ainda tem tem uma conta no GitHUb crie uma se tiver dúvidas pode acessar esse video https://www.youtube.com/watch?v=i0TPn0KnqDs 

> Importante: Git não é a mesma coisa que GitHub, Git é o controle de versão, GitHub é um local na Web que você hospeda seus projetos.

### Configurando o Git

A configuracao basica que você precisa fazer é a de usuario e email, aterves de linha de comando digite a seguinte intrução, essas informações serão utilizadas nos commits:

```
git config --global user.name "<Seu Nome>"
git config --global user.email "<Seu Email>"
```

Exemplo:

```
git config --global user.name "Johni Douglas Marangon"
git config --global user.email "johni.douglas.marangon@gmail.com"
```

Você pode listar as suas configurações utilziando o comando `git config --list`. 

Exeistem outras configuraçoes que voc6e pode estar fazendo para melhor o seu ambiente de desenvolvimento, acesse esse (link)[https://git-scm.com/book/tr/v2/Customizing-Git-Git-Configuration] para ver uma lsita completa das configuraçoes do disponiveis.  

Outro comando util é que pdoe ser utilziaro é o `help` você pode listas a ajuda de todos os comandaos digitando `git help` ou obter detalhes de um comando usando `git help [nome do comando ]` como por exemplo: `git help commit`.

### Versionando seu código com o Git

Nao vamos inicializar um repositório cirnado uma pasta com o nome `meu-primeiro-projeto` o objetivo é utilziar essa pasta como exemplo de uso do Git.

```
mkdir meu-primeiro-projeto
cd meu-primeiro-projeto
```

O comando `init` transforam o diretório em um repositório Git. 

```
git init
```

Nosso proejto ainda vazio, mas já podemos verificar a existencia de uma pasta oculta chamda `.git`, nesse pasta ficam os metaados do repositório. Voce nao deve excluir ou altare qualqeur arquivo deses local.

Para rastrear um aquivo nos precisamos crialo dentro do repositório, nesse exeplo nos vamoso criar uma sequencoa de arquivos para demostrat o uso dos comandos e simualr a existenca de um projeto

```
touch index.html
touch anotacoes.txt
mkdir css
touch css/index.css
```

O comando `git status` deve ser utiliar para verificar o estado dos seu arquivos, execeute esse comando no repositório e você vai ter uma saida como essa:

**video**

Observe que o Git esta no falando que os nosso arquvos ainda nao estao sendo raterado, voce precisa executar o comando `git add` para rastreas essse arquivos.

Voce pode executar esse comando de duas formas:

- Adicionado tdoos os arquivos: `git add .`.
- Adicioando alguma arquivo expecifico: `git add <nome do arquivo>`.

**video**

Os arquivos que compoes o nosso projeto já estao sendo rastrados nos precisamo agora gravar as nossas alteraçoes, ou em uma lingaugem mais tecnica *commitar* no repostitório.

Execeute o commando `git commit -m "Incluído os arquvos index.html e index.css"`, o comando `git commit` foi invocado com a opção `-m` que rece como parametro uma mensagem, essa mensagem vai estar vinculada ao log do commit.

Voce tambem pode utilair o comandndo `git commit -am "[menagem do commit]"` esse comando discarta a necessidade de usar o `git add`

### Alterando um arquivo

Voce ao longo do desenvocimento do projeto vai fazendo alteracoes em arquivos ja rastreados, nesse casoso voce deve utilziar os comandos `git add` e `git commit` pra liberar as modificacoes.

**video** 

### Removendo um arquivo

Se voce quiser remover um arquivo do versionando voce pode utilizar o comando `git rm [nome do arquivo]` esse comando não exclui o arquivo do disco, penas remove ele do reasteramento, se voce quiser excuiro arquivo voce podem apenas deletar ele.

**video** 

### Ingorando arquivos

.gitingore 
Proque ignorar arquivos
Esse arquivos e pastas serao ingnorados pelo Git
https://github.com/github/gitignore
https://git-scm.com/docs/gitignore
https://help.github.com/articles/ignoring-files/

## Compartilhando seu código atraves do GitHub

### Documentação


### Apontando seu projeto para o GitHub

No caso `meu-primeiro-projeto` nos inicializamos o respostio Git na maquina local e agora nos precisamos liberar esse projeto no repositorio remoto, nesse caso nos precisamos apontar os dois reposótirios. Para isso nos vamos executar o comando `git remote`.

Antes de executar o comadno voce deve criar um rempostiro no GitHub esse video mostrar como afazer isso, quando o GitHub cria um repositório voce rece uma URL que vai quer permite ligar os dois respositório.

```
git remote add origin <URL do GitHub>
```

Apoos isso nos precismos enviar as apteracoes para o GitHub, o comando `git push` deve ser usado para fazer isso

```
git push origin master
```

Voce precisara informar o usuário e senha do GitHub

**video**

Acesse a URL do proejto no GitHub e veja que as aletarcpes foram enviadas

### Cloando um reposítorio

Voce escontrou um projeto legal e você execeutar ele na sua maquiana, para isso nos vamos coner esse repostitprio atraves do comando `git clone`

```
git clone https://github.com/jonatas/hp12c
```

Despous dissso uma pasta chamada `hp12c` é craido na minha máquina e eu vou ler o `README.md` ou utro arquivo de instruções para toda ro projeto na minha maquina

###  Cloando um reposítorio e subindo alterações no seu GitHub

Nesse caso voce deve clonar o projeto com o comando `git clone` fazer a modificoes commitar as alteracoes e executar o comando `git push`

*video*

##### Fazendo fork de um projeto e criando um pull requests

### Subindo os projetos da faculdade

#### Check list

- [ ] Cirar a psata do projeto
- [ ] Crair o arquivo README.md com detalehs do proejto 
- [ ] Criar o arquivo gitginore
- [ ] Cirar o um repositorio no GitHub para obtera a URL do projeto
- [ ] Execuar os comando do Git para versionar os seus arquivos fontes
	- `git init`
	- `git add .`
	- `git commit` 
	- `git add origin <URL do projeto>`
	- `git push origin master`

*video*
