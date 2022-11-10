# Desafio de projeto - Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE

Para este projeto, aplico os conceitos de modelagem de banco de dados vistos anteriormente na seção Bancos de Dados SQL e NoSql do bootcamp Geração Tech Unimed-BH - Ciência de Dados. Neste desafio, modelei um banco para o contexto de Ordens de Serviço, de Universidade e de E-commerce. Para o caso do E-commerce, tive como desafio terminar a modelagem utilizando os requisitos dados pela instrutora.

# Contexto: 
venda de produtos.

# Objetivo:

Refinar o modelo acrescentando os seguintes pontos:

. **Cliente PJ e PF - Uma conta pode ser PJ ou PF, mas não pode ter as duas informações:** Como os requisitos não informam se deve haver alguma característica particular ao cliente se ele for PJ ou PF, adicionei um atributo chamado tipo_conta para a entidade Cliente para informar se o cliente é PF ou PJ. Caso houvesse alguma particularização, eu criaria as subclasses Pessoa Física e Pessoa Juridica para a classe Cliente, cada uma dessas contendo atributos relacionados às suas particularidades.

. **Pagamento – Pode ter cadastrado mais de uma forma de pagamento:** Criei uma entidade nova chamada Pagamento, que contém atributos relacionados aos dados de cartões de crédito que podem ser persistidos.

. **Entrega – Possui status e código de rastreio:** Criei uma nova entidade chamada entrega que contém os atributos de status e rastreio, além de outros relacionados às datas de saída e entrega, e também de transportadora.

[Link do diagrama a ser refinado](https://github.com/casjunior93/DIO---Refinando-um-Projeto-Conceitual-de-Banco-de-Dados-E-COMMERCE/raw/main/E-commerce/diagrama-e-commerce-aula.png)

[Link do diagrama refinado](https://github.com/casjunior93/DIO---Refinando-um-Projeto-Conceitual-de-Banco-de-Dados-E-COMMERCE/raw/main/E-commerce/diagrama-e-commerce-aula-refinado.png)