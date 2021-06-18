# Boas vindas ao repositório do projeto TryBeer!

😁

O projeto em si é super divertido! Você vai criar uma plataforma de delivery de cerveja. 🍻

Para facilitar o entendimento, dá para dividirmos a aplicação em três partes:

- Front-end do **cliente**, onde nossos clientes vão comprar cerveja;

- Front-end do **admin**, onde o estabelecimento controlará os pedidos feitos;

- API, que será compartilhada entre cliente e admin.


### Requisitos Gerais

- Os `endpoints` da API devem ser criados utilizando o padrão REST;

- O back-end deve utilizar o banco de dados `MySQL`;

- O back-end deve ser construído seguindo o padrão arquitetural `MSC`;

## Lista de requisitos

### 1 - Crie uma página de login

O que será verificado:
```
- Será validado que é possível acessar a home

- Será validado que a tela login contém os atributos descritos no protótipo

- Será validado que não é possível fazer login com um email inválido

- Será validado que não é possível fazer login com uma senha em branco

- Será validado que não é possível fazer login com uma senha com menos de 6 caracteres

- Será validado que é possível fazer login com um cliente e ser redirecionado para tela de cliente

- Será validado que é possível fazer login com um admin e ser redirecionado para tela de admin

- Será validado que é possível clicar no botão "Ainda não tenho conta" e ser redirecionado para tela de registro
```

### 2 - Crie uma página de registro de usuários

O que será verificado:
```
- Será validado que é possível acessar a tela de registro

- Será validado que contém os atributos descritos no protótipo

- Será validado que não é possível fazer o registro com um nome com menos de 12 letras

- Será validado que não é possível fazer o registro com um nome com caracteres especiais

- Será validado que não é possível fazer o registro com um nome com números

- Será validado que não é possível fazer login com um email inválido

- Será validado que não é possível fazer login com um email já existente

- Será validado que não é possível fazer login com uma senha em branco

- Será validado que não é possível fazer login com uma senha com menos de 6 caracteres

- Será validado que é possível fazer cadastro de um admin com sucesso e ser redirecionado para tela do admin

- Será validado que é possível fazer cadastro de um cliente com sucesso e ser redirecionado para tela do cliente
```

### Cliente

### 3 - Crie o menu top e o menu side bar

O que será verificado:
```
- Será validado que os atributos do top menu devem ser mostrados confome protótipos

- Será validado que ao clicar no componente hamburguer o sidebar deve ficar visível

- Será validado que os atributos do side menu devem ser mostrados confome protótipos

- Será validado que ao clicar no botão "produtos" será redirecionado para tela de produtos

- Será validado que ao clicar no botão "meus pedidos" será redirecionado para tela de meus pedidos

- Será validado que ao clicar no botão "meu perfil" será redirecionado para tela de meu perfil

- Será validado que ao clicar no botão "sair" será redirecionado para tela home
```

### 4 - Criar tela de perfil do cliente

O que será verificado:
```
- Será validado que é possível acessar a tela de perfil do cliente

- Será validado que contém os atributos descritos no protótipo

- Será validado que campo email está como readonly

- Será validado que o botão salvar fique desabilitado caso não altere o nome

- Será validado que o botão salvar fique habilitado caso altere o nome

- Será validado que é possível alterar o nome com sucesso
```

### 5 - Criar Tela de Produtos

O que será verificado:
```
- Será validado que existe um produto na tela de produtos

- Será validado que existe todos os produtos na tela de produtos

- Será validado que é possíve clicar no botão "+" e atualizar o produto para 1

- Será validado que é possível clicar no botão "-"e atualizar o produto para 0

- Será validado que não é possível clicar no botão "-" e atualizar o produto para menor que zero

- Será validado que é possível visualizar o botão "Ver Carrinho"

- Será validado que é possível atualizar o valor do carrinho ao adicionar um produto

- Será validado que é possível atualizar o valor do carrinho ao remover um produto

- Será validado que ao atualizar a tela continuará na tela de produtos e carrinho com o mesmo valor

- Será validado que é possível adicionar um produto e clicar no botão "Ver Carrinho" e ser redirecionado para tela de carrinho

- Será validado que o botão "Ver Carrinho" fique desabilitado caso não adicione nenhum produto

- Será validado que não é possível acessar a tela de produtos sem estar logado e será redirecionado para tela de login

```
---

### Requisitos Entrega 2

### 6 - Criar Tela de Checkout

O que será verificado:
```
- Será validado que é possível acessar a tela de checkout

- Será validado que contém atributos descritos no protótipo

- Será validado que é possível ver que o produto tem quantidade, nome e valor total do produto

- Será validado que é possível a lista mostrar o valor total do carrinho

- Será validado que é possível fazer refresh da tela e os dados continuarem na tela

- Será validado que é possível excluir um produto no checkout

- Será validado que ao excluir os produtos aparecerá uma mensagem na tela de:
  `Não há produtos no carrinho` como na imagem abaixo:

- Será validado que é possível o botão finalizar pedido ficar habilitado apenas quando tiver produto maior que zero e rua e numero preenchidos]**

- Será validado que é possível fazer a compra de um produto e ao finalizar ver a mensagem de sucesso e ser redirecionado para tela de produtos

- Será validado que ao fazer a compra com sucesso a mensagem de sucesso "Compra realizada com sucesso!" irá aparecer na tela.

- Será validado que não é possível acessar o checkout sem estar logado e será redirecionado para tela de login
```

### 7 - Criar Tela de Meus Pedidos

- Será validado que é possível acessar a tela de meus pedidos

- Será validado que contém os atributos descritos no protótipo

- Será validado que é possível ver que o produto tem quantidade, nome, valor total e a data da compra

- Será validado que é possível clicar no card e ser redirecionado para tela do detalhe do produto

- Será validado que não é possível acessar a tela de meus pedidos sem estar logado e será redirecionado para tela de login
```

### 8 - Criar Tela de Detalhes Pedidos

O que será verificado:
```
- Será validado que é possível acessar a tela do detalhe do pedido

- Será validado que contém os atributos descritos no protótipo

- Será validado que é possível ver que tem numero do pedido e a data da compra

- Será validado que é possível ver que o produto tem quantidade, nome e valor total do produto

- Será validado que é possível ver o valor total do pedido

- Será validado que não é possível acessar a tela de meus pedidos sem estar logado e será redirecionado para tela de login
```

### Administrador

### 9 - Criar menu side bar para Administrador

O que será verificado:
```
- Será validado que o sidebar devem ser mostrados, conforme protótipos

- Será validado que ao clicar no menu meus pedidos será redirecionado para tela de meus pedidos'

- Será validado que ao clicar no menu Perfil será redirecionado para tela de Perfil

- Será validado que ao clicar no menu sair será redirecionado para tela home
```

### 10 - Criar tela de perfil de Administrador

O que será verificado:
```
- Será validado que é possível acessar a tela do perfil do administrador

- Será validado que a tela de perfil contém os atributos descritos no protótipo

- Será validado que a tela de perfil contém o email e nome do administrador

- Será validado que não é possível acessar a tela sem estar autenticado e ser redirecionado para tela de login
```

### 11 - Criar tela de pedidos de admin

O que será verificado:
```
- Será validado que é possível acessar a tela do pedidos do administrador

- Será validado que a tela de pedidos contém os atributos descritos no protótipo

- Será validado que os dados do card estão corretos

- Será validado que é possível clicar no card do produto e ser redirecionado para tela de detalhes do produto
```

### 12 - Criar tela de Detalhes de admin

O que será verificado:
```
- Será validado que é possível acessar a tela do detalhe do pedido do administrador

- Será validado que contém os atributos descritos no protótipo

- Será validado que o pedido contém nome e status do pedido

- Será validado que o pedido contém todos os detalhes do pedido

- Será validado que o pedido com status pendente irá apresentar na tela o botão "Marcar como entregue"

- Será validado que o pedido ao marcar como entregue o status mude para entregue" e o botão nao esteja mais visível

- Será validado que o pedido ao marcar como entregue o status mude para entregue" na tela de pedidos admin

- Será validado que o status do pedido fica marcado como entregue como na imagem abaixo:

