# Power BI Dashboard: Classic rock dataset

Este projeto consiste na criação de dois dashboards interativos no Power BI, gerados a partir um conjunto de dados público baixada do site Kaggle, com o objetivo de fornecer insights sobre uma amostra de artistas e músicas do gênero rock clássico ao longo dos úlimos cinquenta anos.

## 📊 Visão Geral dos Dashboards

### 1. **Visão dos artistas**
Este dashboard oferece uma visão geral sobre os artistas e álbums do dataset:
- **Total de artistas:** Número total de artistas no dataset.
- **Total de álbums:** Número total de álbums lançados no período citado.
- **Período analisado:** O dashboard compreende o período entre 1962 e 2024.
- **Top 20 Artistas mais Populares:** Artistas mais populares no período, usando como métrica a soma do campo "Popularity" do dataset.
- **Total de álbums lançados por ano:** Gráfico temporal que exibe a soma total de álbums lançados em cada ano pelos artistas do set.

![dashboard_rock_classico_page-0001_cp](https://github.com/user-attachments/assets/c6d256dc-38f3-4425-a9d5-51bcdc3967d4)

 


### 2. **Visão das músicas**
Este dashboard foca nas informações sobre as músicas lançadas no período de 1962 a 2024:
- **Total de Músicas:** Número total de músicas lançadas.
- **Duração das músicas:** Duração média, em minutos, das músicas do dataset.
- **Total de Vendas:** Número total de transações.
- **Música mais popular:** Música mais popular, considerando a medida de popularidade do dataset.
- **Top 10 de músicas mais populares:** Ranking das músicas com maior índice no campo popularidade do período analisado.
- **Variação do volume ao longo do tempo:** Variação da média de volume, em decibéis, ao longo do período analisado.
- **Variação da popularidade ao longo tempo:** Variação da soma do índice de popularidade das canções ao longo do tempo.
- **Relação entre popularidade e energia:** Relação entre a soma do índice de popularidade e o índice de energia das músicas.
  
 ![dashboard_rock_classico_page-0002cp](https://github.com/user-attachments/assets/98a63c99-51e7-4071-a0ce-327e76e531e5)


## 🗂 Estrutura do Dataset

O dataset utilizado está organizado em dezoito colunas:

- Track   
- Artist    
- Album                 
- Year                   
- Duration               
- Time_Signature         
- Danceability           
- Energy                 
- Key                 
- Loudness               
- Mode                
- Speechiness
- Acousticness           
- Instrumentalness    
- Liveness               
- Valence                
- Tempo                  
- Popularity            


## 📅 Tecnologias Utilizadas

- **Power BI:** Ferramenta utilizada para visualização de dados e criação dos dashboards.
- **Git:** Utilizado para controle de versão do projeto e compartilhamento de código.

## 📈 Fonte: 
https://www.kaggle.com/datasets/thebumpkin/14400-classic-rock-tracks-with-spotify-data

