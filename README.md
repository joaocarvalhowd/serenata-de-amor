# Serenata de amor
> Combater a corrupção de forma massiva e eficaz.

*:uk: [Jump to the English version](README-en.md)*

A ideia de automatizar a análise de contas públicas é inédita: engajar a população para treinar nossa plataforma na análise e revisão de contas. Após esse estágio inicial a automatização potencializa análise de dados em volumes inéditos, aumentando a chance de acharmos furos e corruptos.

Em outras palavras, a plataforma de Machine Learning convida a população a ensiná-la, aprende com isso, e expande os métodos massivamente. Em paralelo a produção de conteúdo e uma interface amigável para explorar os dados expandirão o acesso a informação. Ao massificarmos a análise do que é feito com dinheiro público e a exposição dessas análises de forma aberta, toda a sociedade terá argumentos para pressionar políticos e exigir que dinheiro desviado seja devolvido aos cofres públicos.

Em segundo plano esse movimento ajuda a criar uma imagem mais transparente sobre a atuação política de parlamentares, fazendo com que todos tenhamos mais parâmetros na hora de decidir quem leva nosso voto nas próximas eleições.

## Lista de Dados Públicos e Estratégias para Coleta em Massa

### Scraping de dados
| Informação | Motivo | Estratégia |
|------------|--------|------------|
| [Cota para Exercício da Atividade Parlamentar](http://www.camara.gov.br/cota-parlamentar/) (Deputados Federais) | Listar gastos de deputados federais | Scraping de dados |
| [Cota para Exercício da Atividade Parlamentar](http://www25.senado.leg.br/web/transparencia/sen/) (Senadores) | Listar gastos de senadores | Scraping de dados |
| [Estimativa do alugel de imóveis](ftp://ftp.ibge.gov.br/Contas_Nacionais/Sistema_de_Contas_Nacionais/Notas_Metodologicas_2010/06_aluguel.pdf) | Comparar o preço em notas fiscais com o valor do metro quadrado na área. | Scraping de dados de [estudo do IBGE](http://seriesestatisticas.ibge.gov.br/series.aspx?vcodigo=PRECO415). |

### API
| Informação | Motivo | Estratégia |
|------------|--------|------------|
| [Facebook Graph API](https://developers.facebook.com/docs/graph-api) | Identificar se duas pessoas se conhecem |  _Pendente_: [API mostra apenas amigos com o mesmo _app_ instalado](https://developers.facebook.com/docs/graph-api/reference/user/friends/).
| [Consulta de CNPJ na Receita Federal](http://www.receita.fazenda.gov.br/pessoajuridica/cnpj/cnpjreva/cnpjreva_solicitacao.asp) | Levantar informações sobre onde foi gasto o dinheiro público | Captcha. (testar [API “alternativa” sem captcha](http://receitaws.com.br) e estudar viabilidade) |
| [Google Street View](https://developers.google.com/maps/documentation/streetview/) | Identificar se o endereço é comercial ou residencial | API |

## Contribuindo
Para contribuir baste seguir nosso **[guia da contribuição](CONTRIBUTING.md)**.
