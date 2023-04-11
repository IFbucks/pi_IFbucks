# Projeto Integrador - IFBucks

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

**Equipe:**

- [Maria Eduarda Nunes Gerotti](github.com/mariagerotti) e
- [Isadora Goedert](https://github.com/isagrt).

# Situação Problema

A cafeteria Amor Doce, uma nova empresa de vendas de doces e cafés e que vem crescendo gradativamente nos últimos tempos. E com a vinda de aplicativos de delivery, o Sr. Lysandre, dono da empresa, decidiu implementar nosso software para além de otimizar o processo de pedidos (pela quantidade de pedidos crescente), aumentar seus lucros.

Como rotina diária, os funionários fazem a contagem de produtos existentes em estoque, se por um acaso não estiver estes produtos em estoque, é enviado um funcionário para produzir esses produtos. Com a abertura do estabelecimento, o funcionamento ocorre normalmente, com o atendimento dos clientes e produzi-los. Após o fechamento, são contabilizados todos os produtos que foram vendidos no dia, datando ganhos e gastos.

A empresa, mesmo com a contratação de novos funcionários na área de atendimento e cozinha, a empresa convive com diversos problemas com as vendas de produtos, em relação a estocagem, controle de gastos e entradas e saidas dos produtos dos estoques e atendimento ao cliente. O software seria dividido em uma parte administrativa, voltado aos funcionários e o dono da empresa, onde eles devem contabilizar os gastos de cada produtos, estocagem e ganhos de venda. E outra parte, será direcionada ao cliente, com comandos básicos de compra.

![Ciclo da Venda](docs/ciclo_da_venda.webp "Ciclo da Venda")

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

/_O site de venda de cafés é um e-commerce que oferece uma variedade de cafés para compra online. O software utilizado no site é dividido em duas partes: a parte administrativa e a parte do cliente. Na parte administrativa, os funcionários e o dono da empresa têm acesso a ferramentas para contabilizar gastos, estoques e ganhos de vendas. Já na parte do cliente, existem comandos básicos de compra, onde os clientes podem escolher entre os produtos oferecidos e finalizar a compra. Todo produto vendido é contabilizado e registrado no sistema, incluindo ganhos e gastos diários._/


# Regras de Negócio

RN001-Contagem diária de produtos em estoque e produção de produtos em falta.

RN002-Atendimento ao cliente é uma prioridade máxima.
Contabilidade de todos os produtos vendidos diariamente, com registro de ganhos e gastos.

RN003-Controle de estoque para garantir que os produtos não acabem.
Contabilidade detalhada dos gastos de cada produto vendido.
Administração da empresa é responsável por garantir o controle adequado do estoque e dos gastos.

RN004-Gerenciamento de estoque para garantir que os produtos frescos sejam usados antes de expirar.

RN005-A parte do software direcionada aos clientes deve permitir comandos básicos de compra.

RN006-Garantir que o estoque de produtos e os recursos da empresa sejam utilizados de forma eficiente.

RN007-Manter um registro preciso de todas as entradas e saídas do estoque.
Garantir que haja pessoal suficiente para atender às demandas dos clientes.

RN008-Estar ciente dos custos envolvidos na produção de cada produto e dos preços de venda.

RN009-Manter um nível adequado de estoque de cada produto para evitar a falta de estoque.

RN0010-Certificar-se de que o software atenda às necessidades da empresa, aumentando a eficiência e os lucros.

RN0011-Garantir que o software seja fácil de usar pelos funcionários e clientes.
