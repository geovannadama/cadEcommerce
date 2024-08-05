# CadEcommerce
Atividade avaliativa com o intuito dos alunos criarem juntamente com o professor as partes que precisavam ser feitas para completar o projeto CadEcommerce, para assim podermos adicionar marcas e categorias em nosso banco de dados.

## Funcionalidades 

- Cadastro de Produtos : Permite adicionar produtos ao sistema.
- Cadastro de marcas : Permite adicionar marcas ao sistema. 
- Cadastro de categorias : Permite adicionar categorias ao sistema.
- Visualização do carrinho : Mostra os produtos adicionados ao carrinho.

## Estrutura do projeto

O projeto se organiza com os seguintes arquivos principais:

- carrinho.php
- categoria.php
- index.php
- insere-categoria.php
- insere-marca.php
- insere-produto.php
- marca.php
- pedido.php
- produtos.php

## Páginas

### Exibe os produtos disponiveis na loja
![img](imagens/produtos.png)

### Exibe os produtos adicionados ao carrinho   
![img](imagens/pedido.png)

### Cadastra novas marcas ao banco de dados 
![img](imagens/marca.png)

### Cadastra novas categorias ao banco de dados 
![img](imagens/categoria.png)

### Cadastrar Produtos 
![img](imagens/cprodutos.png)

## Métodos PhP

 ### include_once 
 "include_once ('controller/conexao.php')"
  Utilizado em casos em que o mesmo arquivo pode ser incluído e valiado mais de uma vez durante uma execução de um script em particular.

- require_once : A expressão require_once é idêntica a require exceto que o PHP verificará se o arquivo já foi incluído, e em caso afirmativo, não o incluirá novamente.

### if else
if(mysqli_affected_rows($mysqli)  != 0){
echo "
}else{
    echo " }
 Permite executar alguns comandos se uma condição for verdadeira e outros se ela for falsa.

### include 
include('controller/conexao.php');
 Inclui e avalia o arquivo informado
 while 
 Usado para executar as declarações aninhadas repetidamente, enquanto a expressão do while forem avaliadas como verdadeiras .

- die : Serve para indicar ao php que finalize a interpretação do script.

