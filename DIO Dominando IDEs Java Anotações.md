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

## 4.2 Atalhos

## 4.3 Git e GitHub

## 4.4 Debug

## 4.5 Últimas observações sobre Eclipse

# 5. Intellij

## 5.1 Criando seu primeiro projeto com IntelliJ

## 5.2 Mais atalhos e versionamento

## 5.3 Debug

## 5.4 Plugins

## 5.5 Outra opção de IDE: Visual Studio Code