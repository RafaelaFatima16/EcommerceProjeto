# PF_Ecommerce

---

**Tema do E-commerce:** Venda de produtos diversos

*Nosso E-commerce foi criado com o intuito de ser um local de Venda de produtos.*

Serão necessárias cinco classes:

## Classe Loja

- Atributos: Nome, Endereço e CN
    - Para cadastrar a loja, foi passado informações como o nome da loja, o endereço da loja e seu CNPJ.
    
    
- Métodos: Dicionários de Cliente, Produto e ADMs.

---

## Classe Cliente

- Atributos: Nome, Data de Nascimento, CPF, Endereço e Senha.
- Para cadastrar os clientes, foram passados o nome do cliente, sua data de nascimento, seu CPF, endereço e senha para login.
    
    
- Métodos: Dicionário de Adicionar Produto e a parte de Excluir Produto

## Classe Produto

- Atributos: Nome, Descrição e Valor.
    - A partir dessa classe que os produtos podem ser criados.  
        - Passando informações como o nome do produto, sua descrição e seu valor
    
    

## Classe ADM

- Atributos: User, Senha.
    - São passados user e senha para os ADMs poderem entrar no sistema da loja.
    
    
- Métodos: Cadastrar Cliente, Cadastrar ADM, Cadastrar Produto, Excluir Produto, Excluir Cliente, Excluir ADM, Listar Produtos, Listar Clientes, Listar ADMs.
    - Algumas das funções que o ADM pode executar são essas.
    
    

## Classe Carrinho

- Atributos: Nome, Valor, Descrição.
    - Aqui será armazenado os produtos que serão comprados pelo cliente
    

O projeto é baseado em três interfaces:

- **Tela 1:**
    - 01 → Login ADM
    - 02 → Login Cliente
    
    - A Tela 1 é onde fica o login do usuário e do ADM
    
    
- **Tela 2 (Login ADM):**
    - 01 → Cadastrar Cliente
    - 02 → Cadastrar ADM
    - 03 → Cadastrar Produto
    - 04 → Excluir Produto
    - 05 → Excluir Cliente
    - 06 → Listar Clientes
    - 07 → Listar Produtos
    
    - A Tela 2 é onde fica o menu do ADM, que é acessada, onde mostra as funções que ele pode executar como:
    
        - Cadastrar clientes
        - Cadastrar ADMs 
        - Cadastrar Produtos 
        - Excluir Clientes 
        - Excluir produtos 
        - Listar cliente
        - Listar produto
    
- **Tela 3 (Login Cliente):**
    - 01 → Adicionar Produto
    - 02 → Excluir Produto
    - 03 → Listar Produtos
    - 04 → Ver Carrinho

- A Tela 3 é onde fica o menu do cliente, que é acessada após o login, onde mostra as funções que ele pode executar como:

    - Adicionar um produto ao carrinho
    - Remover produto do carrinho
    - Listar os produtos disponíveis 
    - Ver o carrinho

## Estoque

Armazena todos os produtos criados na loja e quantidade de existente de cada produto.

## Relatório

No Relatório será feito um registro de todas as compras do Cliente e mostradas em uma lista, assim como as vendas da loja que  irá mostrar o registro de todas as vendas realizadas na loja.

----------------------------------------------------------------------------------------------------------------

## Como Funciona?

Para começar nosso código é fundamentado na ideia de que já existe um ADM criado na loja, e a partir desse ADM ele podera criar novas contas de ADMs e de usuários.

**Tela 1**

    Quando se inicializa o código ele mostra a 'Tela 1' , a tela de login, nela há três opções, na primeira opção é onde o login como ADM é realizado, colocando apenas seu user e sua senha. Na segunda opção é onde o login como cliente é realizado, colocando se o CPF e a senha, e a terceira opção é para sair do programa.

**Tela 2**

    Após a realização do login do ADM, visualiza-se a 'Tela 2' onde o é mostrado todas as ações/funções que o ADM pode realizar.

        A opção "Cadastro Cliente" é feito o cadastro dos clientes, criando suas contas na loja, e para criar é pedido informações como:

        - Nome
        - CPF 
        - Idade 
        - Endereço 
        - Senha

        A opção "Cadastrar ADM" é realizada o cadastro de um ADM, criando suas contas na loja, pedindo informações como:

        - User
        - Senha

        A opção "Cadastrar Produto" é realizado o cadastro dos Produtos, criando eles na loja, e para cria-los pede informações como:

        - Nome
        - Descrição
        - Valor
        - Quantidade

        A opção "Excluir Produto" é realizada a exclusão dos produtos da loja.

        A opção "Excluir Cliente" é realizada a exclusão dos clientes do sistema da loja.

        A opção "Listar Cliente" é realizada a listagem dos clientes e exibe as seguintes informações de cada cliente:

        - Nome
        - CPF 
        - Idade 
        - Endereço 
        - Senha

        A opção "Listar Produto" é realizada a listagem dos produtos que o cliente colocou em seu carrinho e exibe as seguintes informações de cada produto
        
        - Nome
        - Descrição 
        - Valor

**Tela 3**

    Após a realização do login do cliente, visualiza-se a 'Tela 3' onde é mostrada todas as funções/ações que o cliente pode realizar.

    A opção "Adicionar Produto" é onde adiciona um produto ao carrinho do cliente, para adicionar o produto é pedido informações como:

    - ID do produto
    - Quantidade

    A opção "Excluir Produto" é realizada a exclusão dos produtos do carrinho do cliente .

    A opção "Listar Produto" é realizada a listagem dos produtos que o cliente colocou em seu carrinho e exibe as seguintes informações de cada produto:
    
    - Nome
    - Descrição 
    - Valor

    A opção "Ver carrinho" é realizada a listagem dos produtos criados e cadastrados na loja, exibindo o nome do produto e a quantidade existente na loja.

**Relatório**

    No Relatório tem duas opções:

    - Compras Clientes
    - Vendas Realizadas

    A opção "Compras Clientes" exibe todas as compras do cliente exibindo os produtos comprados, de forma individual.

    A opção "Vendas Realizadas" exibe todas as compras realizadas na loja, exibindo todos os produtos comprados por cada cliente de forma geral. 
