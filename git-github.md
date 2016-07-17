Esse tutotial serve como complento e guia para uso do Git e Gihub

Se você tem alguma sugestao de melhoria voce pode abrir uma issue com a sua sugestão ou enviar um pull request com modificaçoes sugeridas.

#### Objetivos

- Entender o que é controle de versão
- Principais comandos do Git
- Subir seu código no GitHub
- Usar linha de comando
- Aprender a compartilhar meu código

#### Material complementar

###### Livro

- https://www.casadocodigo.com.br/pages/sumario-git-github

###### Curso

- http://willianjusten.teachable.com/courses/git-e-github-para-iniciantes
	
###### Videos recomendados 

- https://www.youtube.com/watch?v=TReVFOxhh7E
- https://www.youtube.com/watch?v=Fc_UC5SywuU
- https://www.youtube.com/watch?v=Ahv6vPTZJqk
- https://www.youtube.com/watch?v=UMhskLXJuq4
- https://www.youtube.com/watch?v=neDiLHwXSVo
- https://www.youtube.com/watch?v=yNwh0S0S0bU

> Dica: No Youtube aumente a velocidade para 1.5x

#### Mitos

- Git e GitHub e dificil
- Nao tenha medo de usar linha de comando
- O que eu estou escrevendo não é bom

#### Motivação

- No seu computador ninguem vai ver o seu potencia
- É seu portifólio
- O código não é so seu
- Ajuda muitas pessoas a escreverem sotware com mais qualidade

#### Compartilhamento de Código

- Contribuindo com projetos open source
- Dando like
- Escrevendo código
- Criando Gists
- Escrevendo sobre projetos
- Compartilahndo projetos 

### Entendendo o Git  GitHub

#### Git 

##### O que é controle de versao 

Tem a finaldiade de gerencias modificacoes em arquivos, um arquivo sofre muitas alteraçoes sendo necessário manter um histórico dessas alteraçoes para manipulação, voltar uma versão por exemplo.

O Git é um sistemas de contreole de versão distribuido onde os usuário tem uma cópia do repositório. Isso permite que você cosiga  fazer alteraçoes e commits sem estar necessriamente a um repositório remoto.

Outros sisteas de controle de versão basedos no Modelo Cliente Servidor, como por exemplo o SVN devem exigem que você tenha um servidor remoto para podemo realziar alteracoes e commits.

Criado em 2005 por 	Linus Torvals para manter o kernel do Linux, em engenharia de software associamos o uso do Git e outras ferrametnas de controle de versao a Gerencia de Configuracao de Software, onde mantemos informações do que mudou, quando mudou, porque mudou é uma docmunentacao vinculada a versão dos arquivos.

##### Instanado o Git

O processo de isntalacao é bem simples, acesse a página https://git-scm.com/downloads escolha o sistemas operacional que vocue esta utilizando e sigua s intruções de intralacao 

Eu recomendo formtementeo o uso da linha de comandos para trabalhando com o Git, você pode utilizar alguma GUI para complementear o uso da linha de comenaod, como pode exemplos ver os logs de commit, arvore de commits, diff de commits, etc...	

Nesse site, https://git-scm.com/download/gui/linux, você pode verificar algumas alternativas para GUI Clientes

Para complementar o estudo fazer o (Git Tutorial)[https://try.github.io/] 

Outras ferramentas alem do Git
- SVN
- Mercurial 
- CSV
- Bazzar
- Microsoft TFS

#### GitHub

É um serviço Web utilziar para hospedar projetos que utilizando o Git, ele tem um funcionaldiades semelhantes a uma rede social, porem é voltada para comunidade Open Source, surgiu em 2008, é a rede mais utilziada por desenvolvedores e impresar muito importantes como: Google; Nasa; Linekdin; Facebook; Twiiter; Contentools; RDStaton; Globo; NetFlix; Spotyfy, tem projetos hospedados no GitHub	

Exsistem muuitas funcionaldaide que pdoem ser utilizadas pelo desenvolcedores:

- Wiki do projeto
- Colaboradores 
- Issue
- Milestone
- Releases
- Follow
- Whatch 
- Start 

Alem do GitHub temos outras alternaricas como: GitLab; BitBuckets e SourceForge.

O GitHub é muito utilizado para hosedar projetos Open SOurce, logo os seu repositório são publocis, existe a versao paga que permite ter repositórios privados para empresas utilizarem.

> Importante: Git não é a mesma coisa que GitHub, Git é o controle de versão, GitHub é um local na Web que você hospeda seus projetos.

### Configurando o Git

A configuracao basica que você precisa fazer é a de usuario e email, aterves de linha de comando digite a seguinte intrução:

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

