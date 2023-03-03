# HYPERATIVA_TESTE_SR
Teste prático para empresa Hyperativa

Teste realizado onde alguns pontos de boas práticas não foram observadas por ser um teste rápido.

Portanto não realizei validações de campos, principalmente o do arquivo em lote onde não fiz o controle de lote e simplesmente criei uma tabela com id e numero do cartão para validações.

Também não criei mensagens de retorno amigáveis.

No caso do lote ainda fiz uma mensagem das linhas do lote que não foram incluídas, porém não informei o motivo.

Agora quando estou escrevendo, lembrei que não tratei a inserção simples e se for incluído o mesmo cartão ele irá gerar erro, já que a tabela tem uma unique key no numero do cart;ão.

Outro ponto é que criei a tabela através da EntityFramework e a Unique key pelo banco.

Sobre a parte que pediu para gera com uma quantidade muito grande de dados, teria que saber qual seria a Volumetria e quais as regras gerais e se fosse o caso poderia usar um Bulk Insert.

Gerei um documento de Evidencia de Testes para que fosse mais fácil a avaliação de vocês.

Desde já agradeço a oportunidade de participar da seleção e de ter que me recordar em como fazer um Web API, pois o meu ultimo foi a 4 anos quando estava fazendo o projeto do microcrédito do Itaú-Unibanco.
