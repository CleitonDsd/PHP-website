# Avaliação de PWII

## 📝 Descrição da Atividade

Nesta atividade de **Programação Web II (PWII)**, os alunos deverão desenvolver a interface e a lógica de uma aplicação básica com páginas em PHP, utilizando conexão com banco de dados e estilização via CSS.

## 🎯 Objetivos

- Na página `home.php` , realizar a estilização da tela utilizando CSS para melhorar a aparência.
- Deverá ser desenvolvido um menu
- Adicionar um **link no menu** que leve para a tela de **cadastro de produtos**.
- Criar a tela `cadastro-produto.html` com um **formulário de cadastro de produtos e estilizar a tela**.
- Criar o script de cadastro no `cadastro-produto.php` para inserir os dados do **formulário de cadastro de produtos**
- Implementar a **inserção dos dados no banco de dados** via PHP.

---

## 📄 Estrutura esperada

### `home.php`
- Deve conter um **menu de navegação** com, no mínimo:
  - Link para a própria `home.php`
  - Link para `cadastro-produto.php`
- A página deve estar **estilizada** com CSS (externo).
  
### `cadastro-produto.php`
- Formulário com os seguintes campos:
  - Nome do produto
  - Marca
  - Preço
  - Descrição
- Um botão para **salvar o produto** no banco de dados.
- Exibição de mensagem de sucesso ou erro.

---

## 🗄️ Banco de Dados

Você deverá criar a tabela `produtos` com os seguintes atributos:

    id 
    nome
    marca
    preco
    descricao 
    quantidade
    categoria 
    caminho do produto 
    data_cadastro 
    ativo

