# Sumário
1. Visão geral da linguagem de programação Java e da sua plataforma
2. Ambiente de desenvolvimento Ubuntu
3. Ambiente de desenvolvimento Windows
4. Eclipse
5. Intellij

# 1. Visão geral da linguagem de programação Java e da sua plataforma

### 1. História do Java
- linguagem de programação orientada a objetos
- década de 1990: criação pela Sun Microsystems
- 1995: lançamento
- 2008: aquisição pela Oracle
- popularidade: uso na internet (presente em navegadores, programas, jogos, celular, calculadoras etc)

### 2. Características do Java
- interpretada: código compilado para um bytecode e interpretado por uma máquina virtual (Java Virtual Machine - JVM)

### 3. Plataforma x linguagem
- linguagem de programação Java: linguagem convencional da plataforma Java
- plataforma não presa a um sistema operacional ou hardware (programas rodam através de uma máquina virtual, que pode ser emulada)
- lema do java: "write once, runs anywhere"
- Java SE (Standard Edition)
	- base da plataforma
	- classes comuns
- Java EE (Enterprise Edition)
	- des web
- Java ME (Micro Edition)
	- des dispositivos móveis e embarcados (calculadora, modem etc)

### 4. Fases da execução Java
1. Código-fonte (arquivo extensão .java)
2. JDK compila o código-fonte (gera arquivo bytecode com extensão .class)
3. JVM lê o arquivo compilado (.class) e as bibliotecas padrões Java (no JRE)

### 5. JDK x JRE
- JDK (Java Development Kit)
	- kit de desenvolvimento
	- compila código-fonte (.java)
	- cria bytecode (.class)
- JVM (Java Virtual machine)
	- máquina virtual
	- executa o bytecode (.class)
- JRE (Java Runtime Environment)
	- ambiente de execução
	- fornece bibliotecas padrões ao JDK e JVM

### 6. Versões Java
- OpenJDK
	- open source
	- GNU (General Public License)
- OpenJDK LTS
	- suporte de longo prazo
	- cada 4 anos
- JDK Oracle
	- requer licença comercial
	- Contrato de Licença de Código Binário Oracle
*[JDK release notes](https://www.oracle.com/java/technologies/javase/jdk-relnotes-index.html)

### 7. IDE
- ambiente de desenvolvimento integrado
- software
- ferramentas comuns de desenvolvimento
- interface gráfica do usuário (GUI)
- JDK faz parte do funcionamento das IDE's (ex.: Intellij, Eclipse, Netbeans etc)
- Eclipse: suporta Java e outras linguagens, feito em java e modelo open source
- Intellij IDEA: escrito em java, edição da comunidade licenciada Apache 2 e edição comercial proprietária

# 2. Ambiente de desenvolvimento Ubuntu

## 2.1 Instalação JDK e Git no Ubuntu

Repositório Curso DIO Dominando IDEs Java - Camila Cavalcanti

[Instalação JDK](https://github.com/cami-la/curso-dio-dominando-ides-java#-%EF%B8%8F-ubuntu:~:text=%F0%9F%94%BA,Instala%C3%A7%C3%A3o%20OpenJDK)

[Instalação Git](https://github.com/cami-la/curso-dio-dominando-ides-java#-%EF%B8%8F-ubuntu:~:text=./idea.sh-,%F0%9F%94%BA,Instala%C3%A7%C3%A3o%20Git,-%F0%9F%94%B8)

## 2.2 Instalação Intellij e Eclipse no Ubuntu

Repositório Curso DIO Dominando IDEs Java - Camila Cavalcanti

[Instalação Intellij IDEA Community](https://github.com/cami-la/curso-dio-dominando-ides-java#-%EF%B8%8F-ubuntu:~:text=IDE%20no%20Dock-,%F0%9F%94%BA,Instala%C3%A7%C3%A3o%20IntelliJ%20IDEA%20Community,-%F0%9F%94%B8)

**Adicionar atalho**: barra superior - "tools", "create desktop entry", selecionar "create the entry for all users"

[Instalação Eclipse](https://github.com/cami-la/curso-dio-dominando-ides-java#-%EF%B8%8F-ubuntu:~:text=Cr%C3%A9ditos%3A%20DevSuperior-,%F0%9F%94%BA,Instala%C3%A7%C3%A3o%20Eclipse,-%F0%9F%94%B8)

# 3. Ambiente de desenvolvimento Windows

## 3.1 Instalação JDK e Git no Windows

Repositório Curso DIO Dominando IDEs Java - Camila Cavalcanti

[Instalação JDK Zulu](https://github.com/cami-la/curso-dio-dominando-ides-java#-%EF%B8%8F-ubuntu:~:text=WINDOWS-,%F0%9F%94%BA,Instala%C3%A7%C3%A3o%20JDK%20Zulu,-Aqui%20no%20windows)

[Instalação Git](https://github.com/cami-la/curso-dio-dominando-ides-java#-%EF%B8%8F-ubuntu:~:text=pronta%20para%20uso!-,%F0%9F%94%BA,Instala%C3%A7%C3%A3o%20Git,-%F0%9F%94%B9)

## 3.2 Instalação Intellij e Eclipse no Windows

Repositório Curso DIO Dominando IDEs Java - Camila Cavalcanti

[Instalação IntelliJ](https://github.com/cami-la/curso-dio-dominando-ides-java#-%EF%B8%8F-ubuntu:~:text=WINDOWS-,%F0%9F%94%BA,Instala%C3%A7%C3%A3o%20JDK%20Zulu,-Aqui%20no%20windows)

[Instalação Eclipse](https://github.com/cami-la/curso-dio-dominando-ides-java#-%EF%B8%8F-ubuntu:~:text=pronta%20para%20uso!-,%F0%9F%94%BA,Instala%C3%A7%C3%A3o%20Git,-%F0%9F%94%B9)

# 4. Eclipse

## 4.1 Criando seu primeiro projeto com Eclipse

[Eclipse documentation](https://www.eclipse.org/documentation/)

## 4.2 Atalhos

- alt+setas cima/baixo (selecionar linhas e mover)
- alt+shift+x e j (executar programa em java)
- ctrl+3 (menu)
	- perspectives (mudar perspectiva da IDE)
		- ex.: git, debug, java
	- constructor (gerar construtores)
	- getters (gerar getters e setters)
	- equals (gerar hashcode and equals)
	- tostring (gerar toString)
- ctrl+alt+setas (duplicar linhas acima ou abaixo)
- ctrl+espaço (lista de propostas de templates)
	- selecionar + enter
	- ex.:
		- main (public static void main)
		- sysout (System.out.println)
		- new (gerar objeto) ex.: Scanner
- ctrl+n (gerar projeto, classe etc)
- ctrl+shift+c (comentar bloco)
- ctrl+shift+f (formatar código)
- ctrl+shift+o (importar classe)
- ctrl+shift+t (open type - buscar item - ex.: classes criadas)
- ctrl+shift+w (fechar todas as abas)
- ctrl+w (fechar aba)
- package+F2 (mudar o nome do package)

## 4.3 Git e GitHub

[Git documentation](https://git-scm.com/docs)

[GitHub documentation](https://docs.github.com/pt)

## 4.4 Debug

- 2 cliques lateral esquerda (antes do nº da linha)
- mouse dir (janela do código) + "debug as" java; ou
- alt+shift+d e J
- switch (perspective)
- F5 (step into - entra no método)
- F6 (step over)
- F7 (step return - sair do método)
- F8 (resume)
- ctrl+F2 (terminate)

## 4.5 Últimas observações sobre Eclipse

- importar projeto (file\import...\"project"\existing projects into workspace)
- build path

# 5. Intellij

## 5.1 Criando seu primeiro projeto com IntelliJ

**Customize**
- cor
- fonte

**Plugins**
- key promoter

**Criar projeto**
- new project
- java
- next
- prj name (primeiro-programa-intellij)
- create

**Projeto**
- src
- criar pacote
- alt+insert
- package (br.com.dio)
- criar classe
- alt+insert
- java class
- class (PrimeiroPrograma)

**Código**
- main + ctrl+espaço + enter (public static void main)
- sout + ctrl+espaço + enter (Syste.out.println)
- print (Hello world!)
- ctrl+shift+F10 (add config e executar)
- declarar variáveis a (5) e b (3)
- print (a + b)
- shift+F10 (executar)

**Novo pacote**
- br.com.dio
- alt+insert
- package (br.com.dio.model)
- model
- alt+insert
- java class
- class (Gato)

**Classe Gato**
- class Gato (nome, cor, idade)
- janela do código
- alt+insert
- constructor (selecionar tudo)
- alt+insert
- getters n setters (selecionar tudo)
- alt+insert
- equals n hashcode\fields equals(todos)\fields hash (todos)\non null (nenhum)
- alt+insert
- toString (selecionar tudo)

**Classe principal**
- ctrl+shift+barra (comentar bloco criado anteriormente)
- Gato gato = new Gato();
- selecionar "Gato" + alt+enter (importar classe)
- sout + ctrl+espaço + enter
- print (gato)
- shift+F10
- ctrl+y (apaga linha)

**Fechar projeto**
- file\close project

## 5.2 Mais atalhos e versionamento

**Atalhos**
- shift+F6 (altera classe - PrimeiroProgramaJava)
- shift+f12 (apenas editor de texto)
- ctrl+alt+L (organiza código)
- ctrl+b (selecionado classe - ir até classe)
- ctrl+d (duplicar linha)
- ctrl+F4 (fechar abas)
- ctrl+n (buscar classes)
- ctrl+y (deleta linha)
- ctrl+shift+seta cima/baixo (mover linha)
- [Basef Lista de atalhos Intellij](http://www.basef.com.br/index.php/Atalhos_do_IntelliJ_Idea)
- [JetBrains Lista de atalhos Intellij](https://www.jetbrains.com/help/idea/mastering-keyboard-shortcuts.html)

**Novo repositório**
- GitHub
- nome (teste-curso-dio-ides-java-intellij)
- copiar link
- intellij
- vcs\enable version...\Git
- ctrl+k (commit)
- selecionar tudo
- commit n push
- define remote (nome+url)
- push tags (all)
- push (login via github)

**Nova classe na classe principal**
- class Livro(){} (nome e pags)
- alt+insert
- constructor
- alt+insert
- getters n setters
- alt+insert
- tostring
- Livro Livro1 = new Livro("nome", 300);
- commit+push

## 5.3 Debug

**Comandos Debug**
- breakpoint (clique esq lateral esq da linha)
- clique dir (debug)
- ctrl+F2 (stop)
- ctrl+F5 (return)
- F7 (step into)
- alt+shift+F7 (force step into)
- F8 (step over)
- shift+F8 (step out)
- F9 (resume)
- alt+F9 (run to cursor)

**Editar projeto**
- file\project structure; ou
- ctrl+alt+shift+S

## 5.4 Plugins

**Adicionar plugins**
- file\settings\plugins
- rainbow brackets (chaves coloridas)
- nyan progress bar (barra de carregamento colorida(?))
- git tool box (mensagens de commit)
- key promoter x (sugestão de atalho)
- one dark theme (não precisa reiniciar)

## 5.5 Outra opção de IDE: Visual Studio Code