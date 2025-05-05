# Projeto-Conceitual-E-commerce
Projeto Conceitual de Banco de Dados - E-commerce do bootcamp da Dio-suzano.

O desafio proposto: Refine o modelo apresentado acrescentando os seguintes pontos:
Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
Entrega – Possui status e código de rastreio.

Criei entidades separadas para cada cliente( PF e PJ), Criei uma nova entidade de pagamento que está ligada há entidade pedido( 1 pagamento para N pedidos) e para os clientes PF e PJ (1 cliente para N formas de pagamento) visando que 1 cliente pode ter mais de 1 cartão para realizar o pagamento. Entrega, criei uma nova entidade( N entrega para M pedidos).
