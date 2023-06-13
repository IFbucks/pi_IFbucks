# Projeto Integrador - IFBucks

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

**Equipe:**

- [Maria Eduarda Nunes Gerotti](github.com/mariagerotti) e
- [Isadora Goedert](https://github.com/isagrt).

# Situação Problema

A Cafeteria IfBucks é um novo estabelecimento de vendas de doces e salgados que tem feito muito sucesso na cidade de Joinville. O objetivo da cafeteria é ampliar suas vendas para alcançar mais pessoas nessa cidade.

O funcionamento do café ocorre da seguinte maneira: Quando o cliente chega, ele se dirige ao balcão de atendimento e faz seus pedidos diretamente ao atendente. O atendente registra o pedido em uma comanda, que contém o nome do cliente, a mesa em que o cliente vai se sentar e os produtos que ele pediu. Após o registro dos itens, o atendente leva a comanda para a cozinha, para que os funcionários possam preparar os produtos. Quando o produto está pronto, o garçom leva os itens até a mesa do cliente e entrega a comanda. E quando o cliente estiver satisfeito, ele se dirige novamente ao balcão e entrega a comanda para o atendente, a fim de finalizar o pedido.

A empresa, mesmo com a contratação de novos funcionários na área de atendimento e cozinha, a empresa convive com diversos problemas com as vendas de produtos, em relação a estocagem, controle de gastos e entradas e saidas dos produtos dos estoques e atendimento ao cliente. O software seria dividido em uma parte administrativa, voltado aos funcionários e o dono da empresa, onde eles devem contabilizar os gastos de cada produtos, estocagem e ganhos de venda. E outra parte, será direcionada ao cliente, com comandos básicos de compra.



Descrevem o que acontece atualmente na empresa em um contexto global,
abordando o funcionamento da empresa como um todo, não apenas os “problemas” que lá ocorrem.

Sabendo disso, seu papel é **detalhar o funcionamento da empresa escolhida na
atualidade, ou seja, antes de seu novo software**, usando como base a situação que passamos, mas aprofundando os detalhes de como as coisas acontecem.

- Pesquise sobre empresas do ramo escolhido
  para entender como funcionam;
- Aproveite seus conhecimentos previamente adquiridos na área da empresa que escolheu, se houver;
- Simule uma situação real. Lembre-se que são
  propostas com empresas fictícias, sendo assim,
  você terá que tomar certas decisões sobre como
  a empresa funciona em relação às coisas que
  não estão definidas no documento base (por
  exemplo, no caso da padaria, dizemos que seu
  Genival contratou mais funcionários, mas saber
  quantos e o que fazem pode ser relevante para o software), então tente “visualizar” a
  empresa funcionando, como se você estivesse lá acompanhando o dia-a-dia;

Seguindo essas dicas, você deve ser capaz de descrever o dia-a-dia da empresa selecionada. E para ajudar na organização do texto, indicamos uma abordagem em 3 etapas:

- **Introdução**: comece com um parágrafo apresentando a empresa (nome, o que faz, tempo de existência, o dono, funcionários,
  etc);
- **Situação-problema**: Aborde em detalhes como a empresa funciona, procurando seguir uma
  ordem lógica dos acontecimentos e organizando parágrafos diferentes para cada coisa
  diferente que for explicar (como faria em uma redação);
- **Conclusão**: tenha um parágrafo de conclusão focando nos problemas que você notou dentro da situação problema analisada e aponte brevemente como um software poderia
  ajudar a resolvê-los.

_O site de venda de cafés é um e-commerce que oferece uma variedade de cafés para compra online. O software utilizado no site é dividido em duas partes: a parte administrativa e a parte do cliente. Na parte administrativa, os funcionários e o dono da empresa têm acesso a ferramentas para contabilizar gastos, estoques e ganhos de vendas. Já na parte do cliente, existem comandos básicos de compra, onde os clientes podem escolher entre os produtos oferecidos e finalizar a compra. Todo produto vendido é contabilizado e registrado no sistema, incluindo ganhos e gastos diários._


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
**Entrada**:

  RF001: Sistema de Gerenciamento de Estoque

  1.1 Registrar as entradas de produtos no estoque, seja por compra ou produção interna.

  1.2 Permitir a contagem diária dos produtos existentes em estoque pelos funcionários.

  1.3 Registrar a quantidade disponível de cada produto no estoque.

  1.4 Alertar automaticamente quando um produto estiver com estoque baixo ou esgotado.
  
  1.5 Gerar relatórios de estoque para análise e tomada de decisões.

**Processamento:**

  RF002: Controle de Produção de Produtos

  2.1 Registrar a necessidade de produção de produtos quando estes não estiverem disponíveis em estoque.

  2.2 Acompanhar o status da produção dos produtos e notificar quando estiverem prontos para serem adicionados ao estoque.

  2.3 Permitir o registro dos gastos com a compra de ingredientes e materiais necessários para a produção dos produtos.
  
  RF003: Parte Administrativa do Software

  3.1 Permitir acesso restrito aos funcionários e ao dono da empresa.
  
  RF004: Parte do Cliente do Software (App)

  4.1 Permitir aos clientes visualizar o cardápio dos produtos disponíveis para compra.

  4.2 Calcular automaticamente o valor total do pedido do cliente.

  4.3 Registrar os pedidos dos clientes para posterior preparação e entrega.
  

**Saída:**

  RF006: Saída e Controle de Lucros
  6.1 Registrar as saídas de produtos do estoque devido às vendas realizadas.

  6.2 Atualizar automaticamente o estoque com base nas saídas de produtos realizadas.

  6.3 Calcular o lucro diário com base nas vendas e nos gastos registrados.


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