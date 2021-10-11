# Clipping automático
Script que raspa dados de notícia de forma personalizada (por repórter e site), classificando as reportagens por temas de interesse. 

## Sobre este projeto
Este projeto foi feito por Jamile Santana como entrega final do Master em Jornalismo de Dados, Automação e Data Storytelling, do Insper das disciplinas:

**Pensamento Computacional** - preparação do programa -, professor Álvaro Justen;
**Transparência, reprodutibilidade e uso éticos dos dados** - Documentação do projeto, professoras Natália Mazotte e Carla Vieira.

Ele foi pensado a partir da necessidade de coletar e categoricar reportagens produzidas por 10 bolsistas do Programa de Diversidade das Redações da Énois Jornalismo, financiado com recursos do Google News Initiative. 

## Metodologia
O programa [Clipping Automático](https://github.com/jamilesantana/raspadordenoticias) utiliza os serviços Google News para identificar reportagens em sites específicos, produzidos por jornalistas específicos, definidos por meio de parâmetros de busca. É possível personalizar o período da busca por reportagem e incluir mais de um veículo, jornalista ou tema de reportagem. E tudo isso fica disponível numa planilha csv. 

## Por que você vai querer usar esse script?
Porque ele é totalmente personalizável às suas necessidades. Você pode criar uma base de suas próprias produções e classificar as reportagens de acordo com os temais que mais aborda. Com a base é possível fazer relatórios de análise para saber quais veículos mais publicaram conteúdos de determinado repórter, quais assuntos foram mais abordados, além de outras análises. Tudo isso sem precisar coletar os links na mão. =)

## Bibliotecas utilizadas

- [GoogleNews](https://github.com/Iceloof/GoogleNews)- Faz conexão com a API do Google News e cria arquivos XML para RSS
- [Pandas](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_csv.html) - Configura a planilha e transforma em CSV

