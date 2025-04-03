World Cup Database Project

Este projeto faz parte do curso do freeCodeCamp e envolve a criação e manipulação de um banco de dados PostgreSQL para armazenar e consultar informações sobre jogos da Copa do Mundo.

Estrutura do Projeto

O projeto é dividido em três partes:

Criação do Banco de Dados

Banco de dados: worldcup

Tabelas:

teams: Armazena os times participantes

games: Armazena os jogos disputados, incluindo ano, rodada, times e gols

Inserção de Dados

O script insert_data.sh lê os dados do arquivo games.csv e insere as informações corretamente no banco de dados.

Consultas ao Banco de Dados

O script queries.sh realiza diversas consultas, como:

Número total de gols

Média de gols

Campeões de cada ano

Times que jogaram em rodadas específicas
