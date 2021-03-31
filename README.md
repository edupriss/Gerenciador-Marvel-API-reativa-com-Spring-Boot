DESCRIÇÃO
Nesta sessão vamos desenvolver uma API de gerenciamento de heróis utilizando Spring WebFlux, utilizada por empresas como Netflix e Pivotal, 
junto com a library reativa Reactor que atualmente é mantida pela VmWare. Além disso, usaremos o banco DynamoDb localmente para armazenar nossos 
dados e demonstrarei como realizar testes unitários da sua API com Junit e como gerar documentações simples por meio do Postman e também do Swagger.

# Solução

A aplicação possui:
1. Tela de Login;
2. Tela de Cadastro;
3. Tela de lista de quadrinhos com infinite loading;
4. Tela de descrição do quadrinho, onde apresenta informações mais detalhadas sobre o mesmo,
    e que o usuário poderá adiciona-lo ao carrinho;
5. Tela de Carrinho, onde é apresentado a lista de produtos do Cart;
6. Tela de pagamento simulando uso de cartão de crédito; 
7. Tela de heróis; 
8. Tela de descrição do herói;
9. Tela de perfil;
10. Tela de mudança de senha;
11. Tela de pedidos, onde é apresentado o histórico de compras;
12. Tela de detalhe do pedido;
13. Tela de sobre. 

Os dados dos quadrinhos são recuperados da API: [https://developer.marvel.co](https://developer.marvel.com)

---------------------
## Desenvolvimento 
No desenvolvimento foram utilizados as seguintes ferramentas:  
* Ionic4 (Framework utilizado no desenvolvimento do app)
* Marvel API (Para recuperação dos dados dos quadrinhos e heróis) 
* AngularFire2 Authentication (Para realização do controle de acesso aos dados)
* AngularFire2 Firebase Database (Para realização da persistência dos dados de pedidos)

--------------------

 
 
 
 
