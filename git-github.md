# Git e Github para Iniciantes 

:octocat:

Esse tutotial tem como objetivo ser um guia para uso do Git e GitHub.

Se você tem alguma sugestão de melhoria para esse texto abra uma [issue](https://github.com/OESTIDigital/tutoriais/issues) ou se preferir você pode enviar um [pull request](https://github.com/OESTIDigital/tutoriais/pulls) com as modificações 🐞.

## Objetivos

- Entender o que é controle de versão
- Principais comandos do Git
- Como usar o GitHub
- Aprender a compartilhar seu código

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

- Git e GitHub é dificil
- Medo de usar linha de comando
- O que eu estou escrevendo não é bom

### Motivação

- No seu computador ninguém ve o seu potencial
- O GitHub é seu portifólio
- O código não é só seu, compartilhe ele.
- Você pode ajduar muitas pessoas a escreverem software com mais qualidade

### Compartilhamento de Código

- Contribuindo com projetos open source
- De like em projetos que você gostou e usou
- Escreva código e libere no GitHub
- Crie Gists
- Escreva seus prórpios projetos
- Compartilhe os projetos que você esta usando (em redes sociais, converse com amigos, escreva sobre eles)
- Crie um blog e escreva sobre o que você esta fazendo
- Participe de eventos e ajude a organizar

## Entendendo o Git & GitHub

### Sistema de Controle de Versão

Um sistema de controle de versão tem a finalidade de gerenciar modificacoes em arquivos, um arquivo sofre muitas alteraçoes durante o seu uso sendo necessário manter um histórico dessas alteraçoes para posterior manipulação, por exemplo, voltar o aquivo para uma versão especifica. 

No que diz respeito a código é essecial o controle de versao, pois com isso conseguimos vincualar uma documentação das alteracoes, comparar diferentes versoes e saber o que foi alterado e por que, entre outras vantagens. Em projetos de software o controle de versão esta diretamente vinculado ao trabalho em equipe onde muitas pessoas fazem diferentes alterações em arquivos, exigindo a mesclarem desse trabalho, a mesclarem desses arquivo pode ocorrer de foram automática ou no caso de conflitos exige a intervenção manual.

Em um sistema de controle de versao nos temos um repositório onde obtemos as versões do projeto ou de algum arquivo em especifico.

### Git

O Git é um sistemas de controle de versão distribuído onde os usuários tem uma cópia dos repositórios em sua maquina, isso permite que você consiga fazer alterações e commits sem estar necessariamente ligado a um repositório remoto.

Sistemas de controle de versão baseados no modelo cliente servidor, como por exemplo o SVN exigem que você tenha um servidor remoto para poder realizar alterações e commits.

O Git é utilizado por inúmeras empresas é saber como utilizar ele é uma habilidade indispensável para uma carreira bem sucedidada no desenvolvedor de software.

### Instanado o Git

O processo de instalação é bem simples, acesse a página https://git-scm.com/downloads escolha o sistemas operacional que você esta utilizando e siga as instruções de instalação.

Eu recomendo fortemente o uso de linha de comandos para trabalhar com o Git, você pode utilizar alguma GUI para complementar o uso da linha de comando, como por exemplos ver os logs de commit, arvore de commits, diff de commits, etc.

Nesse site, https://git-scm.com/downloads/guis, você pode verificar algumas alternativas para clientes GUI.

Para complementar o estudo faça o [Git Tutorial](https://try.github.io/)

Outras ferramentas alem do Git: [SVN](https://subversion.apache.org/); [Mercurial](https://www.mercurial-scm.org/); [CSV](www.nongnu.org/cvs/); [Bazzar](bazaar.canonical.com/); [Microsoft TFS](https://www.visualstudio.com/pt-br/products/tfs-overview-vs.aspx).

### GitHub

É um serviço Web utilizado para hospedar repositórios Git - é um repositório remoto - ele também é uma rede social voltada para desenvolvedores com bastante influencia na comunidade open source, surgiu em 2008, e é utilizado por inúmeras empresas importantes como: Google; Nasa; Linekdin; Facebook; Twiiter; Contentools; RDStaton; Globo; NetFlix; Spotyfy que possuem projetos hospedados no GitHub.

> Um repositorio remoto pode ficar na nuvem ou em outa máquina

O GitHub é muito utilizado para hosedar projetos open source, logo os seu repositório são publocis, existe a versao paga que permite ter repositórios privados para empresas utilizarem.

Exsistem muuitas funcionaldaide que pdoem ser utilizadas pelo desenvolcedores:

- Wiki do projeto
- Colaboradores
- Issue
- Releases
- Follow
- Whatch
- Start
- GitHub Pages

Nos precisamos mostrar para o mundo que o nosso código, e para isso nos podemos utilziar o GitHub, se você ainda tem tem uma conta no GitHUb crie uma se tiver dúvidas pode acessar esse video https://www.youtube.com/watch?v=i0TPn0KnqDs 

> Importante: Git não é a mesma coisa que GitHub, Git é o controle de versão, GitHub é um local na Web que você hospeda seus projetos.

Alem do GitHub temos outras alternaricas como: [GitLab](https://about.gitlab.com/); [BitBucket](https://bitbucket.org/) e [SourceForge](https://sourceforge.net/).

### Configurando o Git

A configuração básica que você precisa fazer é a de usuário e email, através de linha de comando digite a seguinte instrução, essas informações serão utilizadas nos commits:

```
git config --global user.name "<Seu Nome>"
git config --global user.email "<Seu Email>"
```

Exemplo:

```
git config --global user.name "Johni Douglas Marangon"
git config --global user.email "johni.douglas.marangon@gmail.com"
```

Você pode listar as suas configurações utilizando o comando `git config --list`. 

Existem outras configurações que você pode estar fazendo para melhor o seu ambiente de desenvolvimento, acesse esse (link)[https://git-scm.com/book/tr/v2/Customizing-Git-Git-Configuration] para ver uma lista completa das configurações do disponíveis.  

[Video](https://www.youtube.com/watch?v=MU9zOq-cpU8)

Outro comando útil que você pode utilizar é o `help` você pode listar a ajuda de todos os comandos digitando `git help` ou obter detalhes de um comando usando `git help [nome do comando ]` como por exemplo: `git help commit`.

### Versionando seu código com o Git

Nós vamos inicializar um repositório criando uma pasta com o nome `sistema-biblioteca` o objetivo é utilizar essa pasta como exemplo de uso do Git.

```
mkdir sistema-biblioteca
cd sistema-biblioteca
```

O comando `init` transforam o diretório em um repositório Git. 

```
git init
```

Nosso projeto ainda está vazio, mas já podemos verificar a existência de uma pasta oculta chamada `.git`, nesse pasta ficam os metadados do repositório. Você não deve excluir ou alterar qualquer arquivo desse local.

Para rastrear aquivos nos precisamos criar eles dentro do repositório, como abaixo:

```
touch index.html
touch anotacoes.txt
mkdir css
touch css/index.css
```

O comando `git status` deve ser utilizado para verificar o estado dos seus arquivos, execute esse comando no repositório e você vai ter uma saída como essa:

[Video](https://www.youtube.com/watch?v=zydxys3KVy4)

Observe que o Git esta no falando que os nossos arquivos ainda não estão sendo rastreados, você precisa executar o comando `git add` para rastrear esse arquivos.

Você pode executar esse comando de duas formas:

- Adicionado todos os arquivos: `git add .`.
- Adicionado alguma arquivo especifico: `git add <nome do arquivo>`.

[Video](https://www.youtube.com/watch?v=zQMmWx2_hf0)

Os arquivos que compõem o nosso projeto já estão sendo rastreados nos precisamos agora gravar as nossas alterações, ou em uma linguagem mais técnica *commitar* no repositório local.

Execute o comando `git commit -m "Incluído os arquivos index.html e index.css"`, o comando `git commit` foi invocado com a opção `-m` que recebe como parâmetro uma mensagem, essa mensagem vai estar vinculada ao log do commit.

[Video](https://www.youtube.com/watch?v=I4-nBkRjGkc)

Você também pode utilizar o comando `git commit -am "[menagem do commit]"` esse comando evita a necessidade de usar o `git add`

> Utilize o comando `git log` para ver o log de commits.

**video** 

### Alterando um arquivo

Ao longo do desenvolvimento do projeto vai fazendo alterações em arquivos já rastreados, nesse caso você deve utilizar os comandos `git add` e `git commit` pra liberar as modificações.

**video** 

### Removendo um arquivo

Se você quiser remover um arquivo do verssionamento você pode utilizar o comando `git rm [nome do arquivo]` esse comando não exclui o arquivo do disco, penas remove ele do reastreamento, para remover do disco o arquivo apenas delete ele.

**video** 

### Ingorando arquivos

Existem aquivos que não fazem sentido serem versionados, por exemplo arquivos compilados, de IDEs, ou temporários. O Git tem um macanismo que permite ignorar esse arquivos e pastas. Para isso basta criar um aquivo chamado `.gitingore`. e colocar dentro dele o que deve ser ignorado.

```
anotacoes.txt
*.exe
eclipse/
```

Mais informações sobre o `gitingore`:

- https://github.com/github/gitignore
- https://git-scm.com/docs/gitignore
- https://help.github.com/articles/ignoring-files/

## Compartilhando seu código através do GitHub

### Documentação

O arquivo `README.md` é muito importante e deve sempre existir em um projeto, ele fica na raiz do proejto e pode possuir informações como:

- instruções sobre configuração;
- instruções sobre instalação;
- instruções sobre como operar o programa;
- créditos e agradecimentos;
- changelog: relato de mudanças.

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
- [ ] Executar o seguinte comandos para subir os aquivos no GitHub
	- `git add origin <URL do projeto>`
	- `git push origin master`

*video*
