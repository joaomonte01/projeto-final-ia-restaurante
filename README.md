# Inteligência Artificial para Previsão de Demanda em Restaurantes

Este repositório contém a implementação técnica do Projeto Final da disciplina de Inteligência Artificial do Instituto Federal da Paraíba (IFPB) - Campus Esperança.

## Descrição do Projeto
O objetivo deste projeto é adicionar uma camada analítica e preditiva (Machine Learning) ao ecossistema de um sistema de gestão de restaurantes (RestaurantSystem). A proposta é extrair dados históricos de vendas armazenados na arquitetura do sistema (que utiliza PostgreSQL e MongoDB) e aplicar um modelo de regressão para antecipar a demanda de pratos.

Utilizando o algoritmo `RandomForestRegressor`, o modelo cruza o histórico de pedidos com variáveis de calendário (dia da semana, feriados) e condições meteorológicas (temperatura, chuva) para prever a quantidade de refeições que serão vendidas no dia seguinte, auxiliando na otimização de estoque e redução de desperdício.

## Estrutura de Arquivos
* `historico_vendas_restaurante.csv`: Conjunto de dados contendo o histórico de 365 dias de vendas (simulando uma exportação do banco de dados).
* `ProjetoFinal.ipynb`: Notebook contendo todo o pipeline de Machine Learning (treinamento, avaliação com métricas MAE e RMSE, e inferência prática).

## Como Executar
1. Clone este repositório ou faça o download dos arquivos.
2. Abra o arquivo `ProjetoFinal.ipynb` em um ambiente como Google Colab ou Jupyter Notebook.
3. Certifique-se de que o arquivo `historico_vendas_restaurante.csv` esteja carregado no mesmo diretório de execução.
4. Execute as células sequencialmente para treinar a Inteligência Artificial e realizar novas previsões.

## Autores
* João Francisco da Silva Monte
* Pedro Pereira da Silva
* Roberto Bento dos Santos Sobrinho
