# Projeto Cadastro de produtos

Esse é meu primeiro projeto feito com Python utilizando o Tkinter junto com o SQLITE

Esse projeto consiste um sistema de cadastro de produtos, nele é possivel cadastrar produtos com nome, descrição e preço, com opção de filtar a lista de produtos por nome e descrição, também podendo excluir produtos após serem cadastrados.

O projeto foi criado utilizando-se da linguagem Python, com o uso do pacote Tkinter junto com o módulo Pyodbc, o banco de dados utlizado foi o SQLite3. Como o projeto envolve um sistema de criação de conta, o primeiro passo foi a criação de um banco de dados em SQLite.

Essas são as telas do projeto:

### *tela_login:*

Nela é feito o processo de login e também permite a criação de um novo login;

<img src="fotos_sistema\tela_login.png">

### *criar_login:*

Permite a criação de um novo login.

<img src="fotos_sistema\tela_criar_usuario.png">

### *tela_princiapl:*

Nessa janela é mostrado a lista de produtos já cadastrados, também aparece os botões para cadastrar ou excluir produtos.

<img src="fotos_sistema\tela_principal.png">

 O usuário pode editar o produto dando dois clicks no produto que queira editar. Na parte de cima da tela são as barras de filtragem para encontrar o produto desejado.

### *cadastrar_produto:*

Nessa janela o usuário faz o cadastro do produto, colocando seu Nome, Descrição e preço.

<img src="fotos_sistema\tela_cadastrar_produtos.png">

### *Banco de Dados:*

Para administrar o site, foram criadas duas tabelas no banco de dados: Usuarios e Produtos

Em Usuario, estão os dados de todos os usuários ja cadastrados no sitema

Em produtos, estão os dados de todos os produtos adicionados pelo usuário

*Observação:* este projeto foi feito acompanhando o curso Python SQL aprenda como Criar um Programa com Banco de Dados criado por Direto ao ponto
