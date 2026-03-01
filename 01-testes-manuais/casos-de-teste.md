CT-01 – Login com credenciais válidas

Pré-condição: Usuário possui credenciais válidas.
Passos:

1. Acessar https://www.saucedemo.com/
2. Inserir usuário: standard_user
3. Inserir senha: secret_sauce
4. Clicar em Login

Resultado Esperado:
Usuário deve ser redirecionado para a página de produtos.


CT-02 – Login com senha inválida

Pré-condição: Usuário está na tela de login.
Passos:

1. Inserir usuário válido
2. Inserir senha inválida
3. Clicar em Login

Resultado Esperado:
Mensagem de erro deve ser exibida.


CT-03 – Login com campo vazio
Pré-condição: Usuário está na tela de login.
Passos:

1. Deixar o campo "nome do usuário" vazio
2. Deixar o campo "senha" vazio
3. clicar em Login

Resultado Esperado:
Mensagem de erro deve ser exibida se usuário ou senha ou ambos não forem preenchido.


CT-04 – verificar exibição de produtos
Pré-condição: Usuário está na tela de produto.
Passos:

1. Escolha um produto
2. clique sobre a imagem ou sobre o nome do produto


Resultado Esperado:
O usuário será redirecionado para tela de detalhamento do produto


CT-05 – Adicionar produto ao carrinho
Pré-condição: Usuário está na tela de produto ou no detalhamento de um produto 
Passos:

1. clicar em  adicionar ao carrinho


Resultado Esperado:
adicionar o produto escolhido no carrinho e atualizar o carrinho.


CT-06 – Remover produto do carrinho
Pré-condição: Usuário está na tela de produto ou no detalhamento de um produto. 
Passos:

1. clicar em  remover

Resultado Esperado:
remover o produto escolhido do carrinho e atualizar o carrinho.


CT-07 – Acessar carrinho
Pré-condição: Usuário está na tela de produto ou no detalhamento de um produto 
Passos:

1. clicar sobre o icone do carrinho

Resultado Esperado:
O usuário será redirecionado para o seu carrinho


CT-08 – Iniciar checkout
Pré-condição: O usuário está na tela seu carrinho
Passos:

1. clicar em checkout

Resultado Esperado:
O usuário é redirecionado para finalizar compra.


CT-09 – finalizar o checkout
Pré-condição:  Usuário está na tela finalizar compra suas informações.
Passos:

1. usuário insere  nome
2. usuário insere sobrenome
3. usuário insere CEP
4. clica em continuar

Resultado Esperado:
o Usuário será redirecionado para a tela de visão geral da compra.


CT-10 – Finalizar compra
Pré-condição: Usuário está na tela de visão geral da compra.
Passos:

1. confere as informações dos prdutos
2. clica em terminar


Resultado Esperado:
O Sistems emite uma mensgame de agradecimento pela compra.


CT-11 – Realizar logout
Pré-condição: o usuário está logado no sistema.
Passos:

1. o usuário acessa o icone no campo superior esquerdo da tela
2. clica na opção logout


Resultado Esperado:
O usuário é redirecionado para a tela de login.

