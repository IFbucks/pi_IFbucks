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

RN001-Contagem diária de produtos em estoque e produção de produtos em falta.

RN002-Contabilidade de todos os produtos vendidos diariamente, com registro de ganhos e gastos.

RN003-Controle de estoque para garantir que os produtos não acabem.
Contabilidade detalhada dos gastos de cada produto vendido.

RN004-Gerenciamento de estoque para garantir que os produtos frescos sejam usados antes de expirar.

RN005-A parte do software direcionada aos clientes deve permitir comandos básicos de compra.

RN006-Manter um registro preciso de todas as entradas e saídas do estoque.

RN007-Estar ciente dos custos envolvidos na produção de cada produto e dos preços de venda.

RN008-Manter um nível adequado de estoque de cada produto para evitar a falta de estoque.

RN009-Certificar-se de que o software atenda às necessidades da empresa, aumentando a eficiência e os lucros.

RN0010-Garantir que o software seja fácil de usar pelos funcionários e clientes.


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
  RNF001:
   O software deve possuir uma interface intuitiva e de fácil utilização, tanto para os funcionários quanto para os clientes.

  RNF002:

  2.1 O sistema deve ser capaz de lidar com um alto volume de pedidos e transações, garantindo uma resposta rápida e sem atrasos.

  2.2 Os relatórios e cálculos financeiros devem ser processados de forma eficiente para evitar atrasos nas operações diárias.

  RNF003:
  
  O software deve ser estável e confiável, evitando falhas e interrupções que possam afetar o funcionamento da cafeteria e o atendimento aos clientes.

  RNF004: 

  O acesso ao sistema deve ser controlado, com diferentes níveis de permissões para funcionários e o dono da empresa.

  RNF005: Compatibilidade:

  5.1 O software deve ser compatível com diferentes dispositivos e sistemas operacionais, permitindo seu uso em computadores, tablets e smartphones.

  5.2 Deve suportar diferentes navegadores da web para garantir uma experiência consistente para os clientes que utilizam o sistema de compra online.