# Projeto de Análise de Desempenho de Jogadores da NBA 🏀



Este projeto utiliza a NBA API para coletar dados de desempenho de jogadores e equipes da NBA na temporada 2024-25. A análise é focada em jogadores como Nikola Jokić, Jayson Tatum e Giannis Antetokounmpo, mas pode ser facilmente expandida para outros atletas que estão disputando o prêmio de MVP. 

## O projeto inclui:

Cálculos de estatísticas médias e totais

Comparações detalhadas entre jogadores

Visualizações de dados interativas



## Funcionalidades
## 1. Coleta de Dados da NBA API
Estatísticas detalhadas de jogos para jogadores específicos.

Informações sobre equipes e temporadas.
## 2. Análise Estatística
Cálculo de estatísticas médias, totais e comparativas.

Comparação direta entre desempenhos de jogadores.

As estatísticas utilizadas no projeto fornecem informações detalhadas sobre o desempenho dos jogadores em cada partida. Abaixo, segue a explicação de cada uma delas:

| Estatística              | Significado                                                                                                                                                                              |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| MIN (Minutes Played)       | Tempo total que o jogador esteve em quadra durante o jogo, medido em minutos.                                                                                                            |
| FGM (Field Goals Made)     | Número total de cestas de quadra convertidas pelo jogador.                                                                                                                               |
| FGA (Field Goals Attempted) | Número total de tentativas de cestas de quadra realizadas pelo jogador.                                                                                                                  |
| PTS (Points)               | Pontos totais marcados pelo jogador no jogo, incluindo cestas de quadra e lances livres.                                                                                                 |
| REB (Rebounds)             | Número total de rebotes conquistados pelo jogador, tanto ofensivos quanto defensivos.                                                                                                    |
| AST (Assists)              | Total de assistências realizadas pelo jogador, indicando passes que resultaram em pontos.                                                                                                |
| PLUS_MINUS (Plus-Minus)    | Diferença no placar enquanto o jogador esteve em quadra. Um valor positivo indica que a equipe teve um desempenho melhor com ele jogando, enquanto um valor negativo indica o contrário. |

Comparação direta entre desempenhos de jogadores.
## 3. Visualização de Dados
Gráficos interativos para análise de desempenho.

Comparação visual entre jogadores utilizando Seaborn e Matplotlib.
## Requisitos

Python 3.9 ou superior

## Pacotes necessários:
pandas

numpy

matplotlib

seaborn

nba_api
