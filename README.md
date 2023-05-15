# BdLojaC
## Requisitos
1. [Node.js](https://nodejs.org/en/) versão 16.13 ou superior
2. Yarn versão 1.22 ou superior. Basta executar o seguinte comando após ter o Node.js instalado:
`npm install --global yarn`
4. [PostgreSQL](https://www.postgresql.org/) (12 ou superior) e [pgAdmin](https://www.pgadmin.org/download/) (4 ou superior)
5. [Power BI](https://powerbi.microsoft.com/pt-br/desktop/)

## Instruções
1. Tendo os requisitos acima, acesse a pasta raiz do projeto e utilize o Yarn para instalação das dependências
`yarn`
2. Edite o arquivo .env com seu usuário e senha
3. Importe o schema do banco de dados no PostgreSQL com `yarn prisma db push`
4. Execute os seguinte comando para acessar ao prisma cliente `yarn prisma studio`
