# Data Analysis With Google Sheets

Este repositório contém um projeto, desenvolvido para o curso Profissão Analista de Dados da EBAC, que pretende realizar a análise de uma Planilha sobre Operações no Mercado de Ações.



Para tanto, usou-se como ferramenta as \*\*Planilhas Google (Google Sheets)\*\*. 



Dentre os processos realizados no arquivo original, podemos citar:

Análise Exploratória dos dados (EDA);

visualização dos dados: criando gráficos que possibilitam um entendimento facilitado dos dados.



## Sobre os dados do arquivo original:

O arquivo original, “operacoes_mercado_acoes”, contém 2001 registros, referentes a operações realizadas no mercado de ações.



Dentre os tipos de campos existentes, temos a seguinte disposição:

**código do cliente:** tipo numérico, identificador único de cada cliente

**nome cliente:** tipo texto

**email cliente:** tipo automático

**operação:** tipo texto, mostra se a operação foi compra ou venda

**stiker:** tipo automático, mostra o STIKER da ação

**preço:** tipo numérico (moeda)

**data:** tipo numérico (data), mostra a data da operação



## Para a Análise Exploratória:

Foi criada uma cópia da planilha original e renomeada para "graficos_mercado_acoes" ([acesse aqui](https://docs.google.com/spreadsheets/d/17cfPgpSSOo_jNBb2YJ-j9WEDKeropZ8obQ47WsdRQH8/edit?usp=sharing)), em seguida cada coluna foi alterada para corresponder ao melhor tipo para o seu conteúdo. Depois foram criadas algumas abas que agrupam dados com base em um tópico, usando algumas funções para extrair esses dados dos dados originais.



Aba “estatística” contém alguns dados estatísticos básicos, como Soma do Preço (valor total em operações), Mínimo, Máximo, Média, Mediana, e Moda.



Aba “cliente” foi feita para mostrar o Perfil do Cliente baseado em certas condições. Basta digitar o email do cliente que deseja visualizar e o Perfil, assim como outros dados serão preenchidos automaticamente.

<img src="/img/mercado_acoes_cliente.gif">



Aba “tendencia_temporal” contém dados referentes ao histórico das informações, como “Operações 2023” (que mostra o total das operações desse ano), “Previsão dez” (que faz uma previsão das operações que poderão ser feitas em dezembro), “Valor real de dezembro”, e o histórico das operações feitas mês-a-mês em 2023.

Aba “compra_venda” tem uma tabela com o agrupamento das quantidades e valores das operações separadas por tipo (compra e venda).



Aba “cliente_compra_venda” mostra outra tabela com o agrupamento das operações de compra e venda por cliente.



Aba “cliente_lucro_prejuizo” mostra outra tabela com os agrupamentos das operações de cada cliente por Stiker. Nessa aba temos também alguns filtros que permitem ao usuário filtrar os dados por cliente e/ou por Stiker, e também uma mensagem fixada para o resultado do Lucro da cliente que a atividade pedia.

<img src="/img/mercado_acoes_filtros.gif">



## Para a visualização dos dados temos a última aba:

Aba “gráficos” contém 6 gráficos feitos para facilitar a visualização dos dados, como: gráfico de “Preço Mínimo e Máximo do Mercado”, “Operações por Mês 2023”, “Distribuição das operações por quantidade” (mostra quantas operações foram feitas do tipo compra ou venda), “10 clientes com maior valor em compras” (mostra o email dos 10 clientes que mais fizeram operações do tipo “compra”), etc.

<img src="/img/graficos-preco-min-max.png">



Por fim, com base nessa análise básica já podemos ter uma ideia de algumas informações que poderiam nortear as próximas ações que essa Financeira Fictícia poderia tomar, como:

- os melhores clientes (ou aqueles que mais operam);

- o Perfil majoritário de seus clientes;

- se seus clientes perdem mais do que ganham nas operações (oportunidade de negócio, como talvez algum material educativo).

