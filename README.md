# Análise de Dataset de Filmes dos EUA

## Visão Geral
Este projeto tem como objetivo analisar e explorar um dataset de filmes dos Estados Unidos, obtido do Kaggle. A análise foi realizada utilizando a linguagem R, com foco em visualizações de dados para identificar padrões e tendências na indústria cinematográfica.

## Objetivos do Projeto
- **Visualizar e explorar dados**: Entender as tendências na produção de filmes, fluxo de público nas salas de cinema, e a relação entre duração dos filmes e suas críticas.
- **Identificar o impacto da crise de 2008**: Analisar como a crise financeira global afetou a quantidade de filmes lançados e o público dos cinemas.
- **Explorar estratégias de lançamento**: Investigar a escolha dos dias para lançamento dos filmes e como isso impacta no desempenho inicial dos mesmos.
- **Avaliar a relação entre a duração dos filmes e suas críticas**: Determinar se há uma correlação significativa entre o tempo de duração de um filme e sua nota em sites de crítica, como o IMDb.

## Conclusões Principais
- **Impacto da Crise de 2008**: Houve uma queda significativa no número de filmes lançados nos anos seguintes à crise, com uma recuperação lenta ao longo dos quatro anos seguintes.
- **Fluxo nas Salas de Cinema**: Apesar da queda na produção de filmes, o número de ingressos vendidos aumentou, indicando que o interesse do público pelo cinema permaneceu forte, mesmo em tempos de crise.
- **Escolha dos Dias de Lançamento**: A maioria dos filmes é lançada às sextas-feiras, aproveitando o final de semana para maximizar o público. No entanto, há estratégias de lançamento em outros dias, especialmente em feriados, para maximizar o tempo de exibição inicial.
- **Relação entre Duração do Filme e Crítica**: Não foi encontrada uma correlação forte entre a duração dos filmes e suas notas no IMDb, com exceções notáveis em certos gêneros, como o drama, que tendem a ter correlações ligeiramente mais altas.

## Tecnologias Utilizadas
- **Linguagem**: R
- **Bibliotecas Principais**: `ggplot2`, `dplyr`, `readr`

## Como Executar
1. Clone este repositório: 
   ```bash
   git clone https://github.com/Gabriel-Machado-GM/data_movies_A2.git
   ```
2. Instale as dependências necessárias:
   ```R
   install.packages(c("ggplot2", "dplyr", "readr"))
   ```
3. Execute o script de análise:
   ```R
   source("script_analise.R")
   ```

## Resultados e Visualizações
A seguir estão algumas das visualizações e análises realizadas durante o projeto:

1. **Impacto da Crise de 2008 na Produção de Filmes**: 
   - Gráfico mostrando a queda na produção de filmes em 2009-2010.
2. **Fluxo de Ingressos Vendidos Durante a Crise**: 
   - Gráfico demonstrando o aumento na venda de ingressos, mesmo durante a crise.
3. **Distribuição dos Dias de Lançamento**: 
   - Gráfico de barras mostrando a frequência de lançamentos por dia da semana.
4. **Correlação entre Duração do Filme e Crítica**: 
   - Scatter plot explorando a relação entre a duração dos filmes e suas notas no IMDb.

## Autores
- **Gabriel Machado**
- **Victor de Almeida Bombarda**

## Licença
Este projeto é licenciado sob a [MIT License](LICENSE).

---
