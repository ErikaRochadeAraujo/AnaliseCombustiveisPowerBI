# AnaliseCombustiveisPowerBI
Análise de dados públicos de preços de combustíveis de 10 anos


Este trabalho de análise foi desenvolvido como um desafio proposto do curso de Ciência de Dados da Awari.  Critérios do trabalho foram bem livres, como o tema, grau de complexidade, assim como a escolha do banco de dados, ferramentas utilizadas para o desenvolvimento até a geração de relatórios.

## Combustível esta caro?


Um assunto constante nos noticiários, nos dias atuais, é o absurdo do aumento nos postos de combustíveis.

Será que isso realmente é real?

Se é, o quanto eles vem aumentando?

Onde é maior esse aumento? Qual combustível esta mais caro?

O que influenciou no aumento?

Para essa análise, utilizei dados públicos da Série Histórica de Preços de Combustíveis disponibilizados pelo [site do governo da ANP](https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/serie-historica-de-precos-de-combustiveis), que acompanha os preços praticados por revendedores de combustíveis automotivos.

Selecionei um período de 10 anos para criar essa análise e os combustíveis Etanol, Gasolina, GNV e Diesel. Isso me deu um BD com mais de 10M linhas de dados de Regiao, Estado, Municipio, CNPJ da Revenda, Cep, Produto, Data da Coleta, Valor de Venda e Bandeira.

Após alguma limpeza e tratamento dos dados coletados, comecei a criação da visualização dos dados observados no Power BI.

![mmm](https://user-images.githubusercontent.com/54283401/172838840-9405a4a4-5527-42d4-8e21-68e6f3091a90.png)
Página 1: Preço Médio Anual por Estado

Observamos na imagem da página 1 que os dados mostram que o Acre é o estado brasileiro de maior média anual de gasolina.

Podemos escolher demais combustíveis ou/e anos ou/e estados ou/e região do Brasil para observar outras médias. Temos também a informação do máximo e mínimo valor do combustível nessa página.

![aaaaa](https://user-images.githubusercontent.com/54283401/172839200-a492ad24-a0a4-46da-822b-7d686635a31c.png)
Página 2: Preço por Combustível




Na página 2 temos um resumo do comportamento dos combustíveis no gráfico de cima durante os anos. No gráfico abaixo, vemos a partir dos últimos anos houve um distanciamento maior da média e o desvio padrão.

![pp](https://user-images.githubusercontent.com/54283401/172839301-0991c7de-408f-46f9-a610-3a188a39a346.png)
Página 3: Preço Anual por Município




Página 3 conseguimos acompanhar como se comportou cada combustível estudado durante esses 10 anos com a granularidade do município. Inclusive como tem sido o percentual de aumento no decorrer dos anos.

![aaa1](https://user-images.githubusercontent.com/54283401/172839383-f804514e-034b-4410-ac6a-b162c6df1ead.png)
Página 4: Município Mais Caros e Mais Baratos




Página 4 coloco em evidência onde a média de cada combustível é mais cara e mais barata no país.

O gráfico acima mostra, ordenado pela média maior por estado, a cidade mais cara do estado e o valor mais barato do estado naquele ano escolhido.

Nas tabelas abaixo podemos ver claramente essas informações das cidades de médias mais caras e mais baratas do ano selecionado.

![aaa12](https://user-images.githubusercontent.com/54283401/172839561-fe9777c4-beb1-423b-8e0e-7727174ff1c4.png)
Página 5: Relação com o Valor do Dólar e Petróleo




Nesta página 5, tento criar hipóteses para os valores observados, percentuais de aumento no decorrer desses 10 anos, de cada combustível estudado.

Para isso, coloquei o valor desse período do dólar e do barril de petróleo. Tanto os dados brutos em reais como os percentuais deles de aumento entre os anos.

Observei que em 2021 o fator fortemente apresentado, com estes dados, foi o Barril de Petróleo que teve um aumento 40,27%, pois do Diesel foi 27,19%, do Etanol foi 31,96%, da Gasolina foi 27,30% e do GNV foi 18,52%. O valor de crescimento médio do Dólar foi de 4,93%.

É necessário falar também que os dados coletados nesses 10 anos nem sempre retrata a realidade quando observamos a média em determinados locais onde sabemos (por vivência) que há um valor maior do preço do combustível do que em outros locais e isso não ficou expresso nos dados.




