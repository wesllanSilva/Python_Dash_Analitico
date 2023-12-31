# Python_Dash_Analitico
Projeto em desenvolvimento: PYTHON - DASH - PANDAS - PSYCOPG2

## Arquitetura da aplicação

A aplicação será composta por três camadas:

- Camada de apresentação: Responsável pela interface com o usuário. Será desenvolvida usando a biblioteca Dash.
- Camada de negócios: Responsável pelo processamento dos dados e geração dos gráficos. Será desenvolvida usando a biblioteca pandas.
- Camada de dados: Responsável pela conexão com o banco de dados. Será desenvolvida usando a biblioteca psycopg2.

### Camada de apresentação

A camada de apresentação será responsável por fornecer uma interface amigável para o usuário. Será desenvolvida usando a biblioteca Dash, que fornece uma API fácil de usar para criar dashboards interativos.

A interface da aplicação será composta por dois principais componentes:

Filtros: Permitirão ao usuário filtrar os dados que serão exibidos nos gráficos.
Gráficos: Exibirão os dados filtrados.

### Camada de negócios

A camada de negócios será responsável pelo processamento dos dados e geração dos gráficos. Será desenvolvida usando a biblioteca pandas.

O processamento dos dados consistirá nas seguintes etapas:

- Conectar ao banco de dados PostgreSQL.
- Consultar os dados necessários.
- Filtrar os dados de acordo com as opções selecionadas pelo usuário.
- Gerar os gráficos.

### Camada de dados

A camada de dados será responsável pela conexão com o banco de dados PostgreSQL.
conexão com o banco de dados será feita usando as seguintes informações:

- Nome do servidor: 
- Porta: 
- Usuário: 
- Senha: 

A Exportação em PDF e excel

Para exportar os gráficos em PDF ou excel, será usado o módulo pdfkit para PDF e o módulo xlsxwriter para excel.
