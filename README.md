# projetoporto

Vou tentar explicar um pouco do meu pensamento, como não tive muito tempo, pois hoje eu tive muitas reuniões. Pensei no começo em consumir a API dos Correios para verificar os CEPs, porém como não tive tempo hábil.
Preferi mockar os dados do cliente em um GET, e fiz uns ENUMs ao invés de buscar de um banco, para testarem podem mudar o enum na classe ServiceConserto aonde coloquei as regras de negócio.
E devolvi com hardcode se o CEP está ápto para o conserto ou não.
