# Criando um Dashboard integrando SQL

Este projeto tem como objetivo usar uma base de dados SQL como fonte de dados de um relatório em power BI
O relatório em si não é o objetivo principal do projeto mas sim a extração de dados e a modelagem.

## Estrutura do Projeto

1. **Importação e transformação dos Dados:** - gerar o banco de dados usando o código da professora 
https://github.com/julianazanelatto/mysql_sql_database_specialist/tree/main/M%C3%B3dulo%203/curso2
- conectar o banco de dados ao power bi
- limpeza de dados e modificação de colunas complexas no power query
	- remoção de colunas redundantes
	- remoção da coluna Bdate
	- combinar nome e sobrenome em Employee (deletar colunas originais)
	- mudança de formatos para valores monetários
	- coluna de endereço em Employee separada em numero, rua, cidade, estado usando funções de texto (Text.) 
	- tabela employee atualizada com a adição dos nomes de depto inclusos.
	- mesclar depto e dept loc em Projects e Dept_loc. A combinação Dno + deptloc é única
	- mesclar Employee com Employee para adicionar o nome do Gerente na tabela Employee
- entendimento dos valores nulos
- modelagem dos dados no power bi
2. **Criação de Visualizações:** Foram utilizadas algumas vizualizações para verificar a validade do modelo.

## Tecnologias Utilizadas

- **SQL:** Criação do database.
- **Power Query:** Transformação dos dados.
- **Power BI:** Utilizado para criação de medidas e visuais.

## Resultado Final

Um relatório simples, que comprova a funcionalidade do modelo.

## Contribuição

Este projeto foi desenvolvido como parte de um exercício educacional. Fique à vontade para sugerir melhorias ou utilizar como base para seus próprios projetos.

