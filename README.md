# ice-video-game-sales-analysis
Análise de dados históricos de vendas de videogames para identificar padrões relacionados ao sucesso comercial entre plataformas, gêneros e regiões.

## Visão Geral

Este projeto analisa dados históricos de vendas de jogos da loja online **Ice** com o objetivo de identificar fatores associados ao sucesso comercial de um jogo. A análise considera o comportamento do mercado em diferentes plataformas, gêneros, avaliações de críticos e usuários, classificações indicativas e distribuições regionais de vendas.

O foco principal é extrair insights que possam apoiar decisões de negócio mais estratégicas em áreas como marketing, posicionamento de produto e priorização de lançamentos.

## Problema de Negócio

A loja Ice precisa identificar padrões em dados históricos de vendas para tomar decisões mais assertivas sobre campanhas, foco comercial e planejamento de produtos futuros. Ao compreender quais características estão mais associadas a bons resultados de vendas, a empresa pode direcionar melhor seus esforços e reduzir incertezas em lançamentos futuros.

## Conjunto de Dados

O conjunto de dados contém informações históricas sobre jogos eletrônicos, incluindo:

- nome do jogo
- plataforma
- ano de lançamento
- gênero
- nota da crítica
- nota dos usuários
- classificação ESRB
- vendas na América do Norte, Europa, Japão e outras regiões

O arquivo utilizado no projeto está organizado na pasta `datasets/`:

- `games.csv`

## Objetivos da Análise

Este projeto busca responder perguntas como:

- Quais plataformas geraram mais vendas historicamente?
- Quanto tempo uma plataforma costuma permanecer comercialmente relevante?
- Quais gêneros apresentam melhor desempenho em diferentes mercados?
- Existe relação entre avaliações e volume de vendas?
- Como as preferências dos consumidores variam entre América do Norte, Europa e Japão?
- Existem diferenças estatisticamente significativas entre grupos analisados?

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. carregamento e inspeção inicial dos dados
2. limpeza e preparação dos dados
3. análise exploratória
4. avaliação do ciclo de vida das plataformas
5. análise de padrões de vendas por gênero
6. construção de perfis regionais de consumo
7. testes de hipótese
8. conclusões finais de negócio

## Ferramentas e Bibliotecas

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

## Estrutura do Repositório

```text
ice-video-game-sales-analysis/
├── .gitignore
├── README.md
├── requirements.txt
├── ice_video_game_sales_analysis.ipynb
└── datasets/
    └── games.csv
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/ice-video-game-sales-analysis.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd ice-video-game-sales-analysis
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o arquivo `ice_video_game_sales_analysis.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.

5. Execute as células em ordem.

## Principais Pontos Analisados

Entre os principais focos da análise, estão:

* concentração histórica de vendas por plataforma
* ciclos de crescimento e declínio das plataformas
* desempenho de gêneros em diferentes mercados
* relação entre notas da crítica, notas de usuários e vendas
* diferenças regionais no comportamento do consumidor
* implicações estratégicas para futuros lançamentos

## Resultados

O notebook inclui:

* limpeza e validação dos dados
* análise exploratória com visualizações
* comparação entre plataformas e gêneros
* análise de perfis regionais de vendas
* testes estatísticos
* conclusões com foco em negócio

## Conclusão

Este projeto demonstra como análise exploratória de dados e testes estatísticos podem ser aplicados a dados históricos de vendas de videogames para revelar padrões de mercado e apoiar decisões estratégicas no varejo digital. Os resultados indicam que o sucesso comercial de um jogo depende de uma combinação de fatores, como timing da plataforma, apelo do gênero, desempenho em avaliações e diferenças de preferência entre regiões.

## Autor

**Iago Zanquetta**

