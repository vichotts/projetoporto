# projetoporto

# 1 - Consulta de CEP 
Vou tentar explicar um pouco do meu pensamento, como não tive muito tempo, pois hoje eu tive muitas reuniões. Pensei no começo em consumir a API dos Correios para verificar os CEPs, porém como não tive tempo hábil.
Preferi mockar os dados do cliente em um GET, e fiz uns ENUMs ao invés de buscar de um banco, para testarem podem mudar o enum na classe ServiceConserto aonde coloquei as regras de negócio.
E devolvi com hardcode se o CEP está ápto para o conserto ou não.

# 2 - Orçamento do conserto

Os dados que gravei pelo repository, coloquei no Banco de Dados H2 que é em memória, o login é "sa" e não tem senha, se precisarem essas informações estão na aaplication.properties.
Eu gravei alguns dados no banco e mockei alguns fiz essas mescla para tentar ganhar tempo, no meu service eu coloquei Orcamento como parametro e tipo de retorno pois não consegui converter de Request para Response.Custos, frete e total, foram mockados e as outras você passa por parâmetro gravando no banco Marca, modelo e Defeito(que vem de um Enum também).
Tentei ganhar tempo nesse também, não consegui chegar no objetivo, mas creio que consegui um caminho.


