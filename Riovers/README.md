# Riovers

Um Website para uma empresa fictícia de turismo chamada Riovers, aqui é demonstrado
conceitos como Design Responsivo, Código escalável e sustentável, e Performace Web, utilizando
o modelo construccional **BEM**: **B**lock **E**lement **M**odifier e a arquitetura 
**Padrão 7-1**

## Design Responsivo
* Layouts Fluídos
* Media Queries
* Imagens Responsivas
* Unidades Corretas
* Desktop-first vs Mobile-first

## Código Escalável e Sustentável
* Clean-code
* Fácil de entender
* Crescimento
* Reusável
* Como organizar os arquivos
* Como nomear classes
* Como estruturar o HTML

## Performace Web
* Mínimo de requisições HTTP
* Menos código
* Código comprimido
* Imagens comprimidas
* Menos imagens

## BEM
* **Bloco**: Componente que tem significado por si mesmo.
    * **Exemplo**: 

            header
        
* **Elemento**: Parte de um bloco que não tem significado por si só.
    * **Exemplo**:

            header__text-box

    * Elementos tem a nomenclatura com o nome do bloco + __ + nome do elemento.
* **Modificador**: É uma diferente versão de um bloco ou elemento.
    * **Exemplos**: 

            heading_primary--main 

            heading_primary--sub

    * Modificadores tem a nomenclatura com o nome do bloco ou elemento + -- + nome do modificador.

## Padrão 7-1

O **Padrão 7-1** utiliza **7** diretórios para arquivos Sass parciais, e **1** arquivo Sass principal para importar todos os outros arquivos em um arquivo CSS copilado.

### Os 7 diretórios para arquivos Sass parciais.

* **base/**: Definições básicas do projeto
* **components/**: Um arquivo para cada componente do projeto
* **layout/**: Definição do layout geral do projeto
* **pages/**: Definição de estilos para diferentes páginas do projeto
* **themes/**: Definição de diferentes temas para o projeto
* **abstracts/**: Variáveis, mixins e funções que serão utilizadas em outros arquivos.
* **vendors/**: Estilos de bibliotecas e frameworks de terceiros.


## Header

  Primeiro componente visível ao usuário, contém uma imagem de background juntamente com
o nome da empresa, slogan e um botão call to action.

### HTML

### CSS