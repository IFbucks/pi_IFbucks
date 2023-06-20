# Projeto Integrador - IFBucks

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

**Equipe:**

- [Isadora Goedert](https://github.com/isagrt) e
- [Maria Eduarda Nunes Gerotti](github.com/mariagerotti).

# Situação Problema

A Cafeteria IfBucks é um novo estabelecimento de vendas de cafés, doces e salgados que tem feito muito sucesso na cidade de Joinville. O objetivo da cafeteria é ampliar suas vendas para alcançar mais pessoas nessa cidade.

O funcionamento atual do café ocorre da seguinte maneira: 
Quando o cliente chega, ele se dirige ao balcão de atendimento e faz seus pedidos diretamente ao atendente.
 O atendente registra o pedido em uma comanda, que contém o nome do cliente, a mesa em que ele irá se sentar e os produtos que ele pediu.
Após o registro dos itens, o atendente leva a comanda para a cozinha, para que os funcionários possam preparar os produtos. 
Quando o produto está pronto, o garçom leva os itens até a mesa do cliente e entrega a comanda. 
E quando o cliente estiver satisfeito, ele se dirige novamente ao balcão e entrega a comanda para o atendente, a fim de pagar e finalizar o pedido.

O *objetivo* da empresa é *ampliar suas vendas*, logo, é necessária a criação de um software em que sua interface se direcionaria para *três usuários*:

**Cliente**: a interface listará produtos, com opções de adicionar e deletar produtos ao pedido e finalizar compra.

**Barista**: a interface listará os pedidos em aberto e neles visualizar os itens de cada pedido.

**Gerente**: na interface será possível cadastrar novos produtos, deletar produtos, editar produtos, gerar e visualizar relatórios de vendas.

**Como funcionará o estabelecimento após a inserção do software?**

O cliente chega no estabelecimento e logo senta em sua mesa, lá será possível escanear um qr code pelo smartphone para ter acesso ao site de pedidos. 
Nesse site, ele terá de cadastrar seu nome e sua respectiva mesa, e assim, fazer o pedido desejado. 
Após a realização do pedido, ele será enviado para o sistema da cozinha, que irá conter a listagem de pedidos em aberto para que os baristas possam produzir.
 A entrega do produto seria de maneira tradicional, o garçom recebe o pedido no balcão da cozinha e leva para a mesa do cliente. 
Para finalizar o pedido, o cliente, com seu próprio smartphone, poderá ver seu pedido em aberto e nele poderá finalizar sua compra.




# Regras de Negócio

Regras de Negócio:

**1. Registro do Cliente:**

   1.1. O cliente deve fornecer seu nome e número da mesa para registrar-se no sistema e fazer um pedido.

**2. Pedidos dos Clientes:**

   2.1. Os clientes podem adicionar produtos ao seu pedido, especificando a quantidade desejada.

   2.2. Os produtos podem ser removidos do pedido antes de serem finalizados.

   2.3. Um pedido só pode ser finalizado após a seleção de todos os produtos desejados.

   2.4. Após a finalização do pedido, ele é encaminhado para a cozinha para preparação.

**3. Preparação e Entrega dos Pedidos:**
   
   3.1. A cozinha recebe os pedidos em aberto e prepara os produtos conforme solicitado.

   3.2. O garçom recebe os produtos preparados e os entrega na mesa correspondente ao pedido.

**4. Gerenciamento de Produtos:**
   
   4.1. O catálogo de produtos deve ser atualizado regularmente pelo gerente.

   4.2. O gerente tem a responsabilidade de cadastrar novos produtos, especificando seu nome, preço, descrição e outras informações relevantes.

   4.3. O gerente pode editar as informações dos produtos existentes, como nome, preço, descrição, etc.

   4.4. O gerente pode excluir produtos do sistema quando necessário.

**5. Relatórios de Vendas:**

   5.1. O gerente pode gerar relatórios de vendas que fornecem informações sobre as transações realizadas.

**6. Integração com o Site de Pedidos:**

   6.1. O site de pedidos deve permitir que o cliente cadastre seu nome e número da mesa para fazer um pedido.

   6.2. O site de pedidos deve sincronizar os pedidos realizados pelos clientes com o sistema interno da cozinha para que os pedidos possam ser preparados adequadamente.

**7. Experiência do Cliente:**
   
   7.1. O sistema deve proporcionar uma experiência agradável e intuitiva para o cliente, facilitando a navegação, seleção de produtos e finalização da compra.

   7.1. O sistema deve estar disponível durante o horário de funcionamento do estabelecimento, permitindo que os clientes façam pedidos dentro desse período.

# Requisitos Funcionais

**1. Interface do Cliente:**
   
   1.1. O sistema deve exibir uma lista de produtos disponíveis para o cliente.

   1.2. O cliente deve ter a opção de adicionar produtos ao seu pedido.

   1.3. O cliente deve poder remover produtos do seu pedido.

   1.4. O cliente deve ter a opção de finalizar sua compra.

**2. Interface do Barista:**

   2.1. O sistema deve exibir uma lista dos pedidos em aberto para que o barista possa visualizá-los.

**3. Interface do Gerente:**

   3.1. O gerente deve ter a opção de cadastrar novos produtos no sistema.

   3.2. O gerente deve poder excluir produtos existentes do sistema.

   3.3. O gerente deve ter a capacidade de editar as informações dos produtos (como nome, preço, descrição, etc.).

   3.4. O sistema deve permitir que o gerente gere relatórios de vendas.

  # Requisitos Não Funcionais

**1. Usabilidade:**
   
  **RNF001.1.** O software deve ter uma interface de usuário intuitiva e de fácil utilização para os clientes, cozinheiros e gerentes.

   **RNF001.2.** O site de pedidos deve ser responsivo, adaptando-se a diferentes tamanhos de tela de dispositivos móveis.
 
   **RNF001.3.** O sistema deve estar disponível durante o horário de funcionamento do estabelecimento, garantindo acesso contínuo aos usuários.

**2. Segurança:**

   **RNF001.1.** O software deve ter mecanismos de autenticação e autorização para garantir que apenas usuários autorizados possam acessar as funcionalidades adequadas.