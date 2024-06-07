## Relatório de Análise Exploratória da Plataforma Steam

#### Introdução
Steam é um software de gestão de direitos digitais criado pela Valve Corporation, usado para distribuição digital de jogos e aplicativos. O cliente Steam oferece automação de atualização de jogos, armazenamento em nuvem, recursos de comunidade como mensagens diretas e um mercado virtual colecionável. É a maior plataforma de distribuição digital de jogos de computador.
by [wikipedia](https://pt.wikipedia.org/wiki/Steam).

<img src="https://i.imgur.com/JI55WIw.png" alt="Image" width="10%" style="display: block; margin: 0 auto;">

#### Metodologia
Os dados usados foram disponibilizados no site [kaggle](https://www.kaggle.com/datasets/amanbarthwal/steam-store-data/code) e consistem em informações sobre diferentes jogos, incluindo o ID, título, data de lançamento, gêneros, categorias, desenvolvedor, editora, preço com desconto, disponibilidade de DLC, classificação etária, descrição do aplicativo, suporte para Windows, Mac e Linux, prêmios recebidos, avaliação geral.

Utilizamos as seguintes etapas metodológicas:
- Limpeza dos Dados
- Análise Descritiva.
- Análise Exploratória

Este arquivo terá como foco os resultados, mas você pode acessar todo o processo de exploração [Aqui](https://github.com/NonakaVal/steam/blob/main/main.ipynb).

#### Resultados.

1. Predominância de Jogos Independentes de Ação.
Os jogos independentes de ação são a grande maioria dos gêneros de jogos desenvolvidos na Steam. Isso se deve à facilidade de distribuição proporcionada pela plataforma, que garante aos produtores independentes uma maneira fácil de publicar e vender seus jogos.

2. Proporção de Jogos Single Player vs Multiplayer
- **Single Player:** 87%
- **Multiplayer:** 13%
A baixa proporção de jogos multiplayer é esperada, pois esses jogos exigem maior investimento em infraestrutura para hospedagem e manutenção de servidores.

 3. Importância da Plataforma Steam
- **Desenvolvedores Independentes:** A Steam continua sendo um canal essencial.
- **Grandes Empresas:** Empresas como Square Enix mantêm sua relevância com lançamentos de RPG e ação.
- **Competitividade:** Empresas buscam inovação e reconhecimento através de premiações e altas avaliações dos jogadores.

4. Crescimento Anual de Lançamentos
A quantidade de jogos lançados na Steam aumenta em aproximadamente 104,10% a cada ano.
![Imgur](https://i.imgur.com/Cxd0k8b.png)

5. Principais Gêneros de Jogos na Plataforma
![Imgur](https://i.imgur.com/q1GWBKR.png)
[![Imgur](https://i.imgur.com/WHRTBMH.png)
6. Premiações Recebidas por Diferentes  Gêneros.
![Imgur](https://i.imgur.com/I6gEAV9.png)

7. Principais Empresas por Número de Jogos Lançados e Avaliações Médias

| Empresa                      | Jogos Lançados | Avaliação Média | Principais Gêneros        | Destaques                           |
| ---------------------------- | -------------- | --------------- | ------------------------- | ----------------------------------- |
| **Choice of Games**          | 122            | 74,89%          | RPG, Indie, Adventure     | RPG (33,06%), Indie (32,25%)        |
| **Laush Dmitriy Sergeevich** | 103            | 82,12%          | Casual, Indie, Adventure  | Casual (31,07%), Indie (30,58%)     |
| **Sokpop Collective**        | 87             | 73,83%          | Indie, Casual, Simulation | Indie (35,63%), Casual (28,74%)     |
| **Square Enix**              | 80             | 75,59%          | RPG, Action, Adventure    | RPG (35,86%), Action (33,21%)       |
| **Dnovel**                   | 74             | 87,80%          | Action, Adventure, Indie  | Action (42,98%), Adventure (39,19%) |
|                              |                |                 |                           |                                     |

8. Desenvolvedores com Maiores Médias de Percentual de Desconto

| Desenvolvedor             | Percentual Médio de Desconto |
| ------------------------- | ---------------------------- |
| **CAPCOM Co., Ltd.**      | 1,48%                        |
| **Respawn**               | 1,24%                        |
| **Bethesda Game Studios** | 0,91%                        |
| **Rockstar North**        | 0,57%                        |
| **Ubisoft Montreal**      | 0,52%                        |

9. Jogos com Maior Quantidade de Avaliações

| Jogo                               | Gêneros                                                | Total de Avaliações |
| ---------------------------------- | ------------------------------------------------------ | ------------------- |
| **Counter-Strike 2**               | Action, Free to Play                                   | 8.062.218           |
| **PUBG: BATTLEGROUNDS**            | Action, Adventure, Massively Multiplayer, Free to Play | 2.361.734           |
| **Dota 2**                         | Action, Strategy, Free to Play                         | 2.243.112           |
| **Grand Theft Auto V**             | Action, Adventure                                      | 1.640.234           |
| **Tom Clancy's Rainbow Six Siege** | Action                                                 | 1.090.287           |
| **Team Fortress 2**                | Action, Free to Play                                   | 1.045.851           |
| **Terraria**                       | Action, Adventure, Indie, RPG                          | 1.024.921           |
| **Garry's Mod**                    | Casual, Indie, Simulation                              | 917.455             |
| **Rust**                           | Action, Adventure, Indie, Massively Multiplayer, RPG   | 872.960             |
| **Apex Legends™**                  | Action, Adventure, Free to Play                        | 828.477             |
|                                    |                                                        |                     |

#### Conclusão

A análise exploratória da plataforma Steam revelou insights valiosos sobre o mercado de jogos. A predominância de jogos independentes de ação, a maior proporção de jogos single player, a importância contínua da Steam para desenvolvedores independentes e grandes empresas, e o significativo crescimento anual de lançamentos são alguns dos principais achados. A análise detalhada das principais empresas e jogos com maior quantidade de avaliações fornece uma visão abrangente da competitividade e inovação no mercado de jogos eletrônicos.



