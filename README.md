# 📊 Análise Descritiva de Dados de Animes - MyAnimeList (MAL)

Este projeto consiste na **importação de um dataset** contendo informações sobre animes do **MyAnimeList (MAL)** para um banco de dados **PostgreSQL**, seguido de uma análise descritiva utilizando **consultas SQL** avançadas.

## 📌 Descrição do Projeto
O conjunto de dados contém diversas informações sobre animes, incluindo pontuação, estúdios, gêneros, sinopses e muito mais. Com base nesses dados, foram feitas diversas consultas que envolveram operações como **junções (joins)**, **agrupamentos (group by)** e outras técnicas SQL, para responder perguntas relevantes sobre o universo dos animes.

## 📋 Algumas das Perguntas Respondidas:
1. **Quantidade de animes** com pontuação geral acima de 7, por tipo.  
2. **Top 10 animes mais populares** que possuem a palavra "demon" na sinopse.  
3. **Top 10 animes com maior score** e mais de 13 episódios, do gênero **Mystery** e **Supernatural**.  
4. **Top 10 animes estreados entre 2011 e 2017**, mais assistidos, que começam com a letra 'D' e são dos gêneros **Terror** ou **Ficção Científica**.  
5. **Query para retornar animes do estúdio "Studio Pierrot"** com episódios de 21 ou 23 minutos, estreados nas temporadas de **Outono** ou **Primavera**.  
6. **Consulta para identificar usuários assistindo "Claymore"**, que já assistiram pelo menos metade dos episódios.
7. **Média das avaliações dos usuários** para os animes que foram **assistidos completamente** agrupados por sua **fonte de origem**.
8. **Animes dropados com média inferior a 5**, nos quais os espectadores assistiram apenas um episódio ou nenhum.
9. **TOP 10 animes baseados em mangás de gênero Shoujo estreados entre 2015 e 2019** que possuam a maior quantidade de avaliações **nota 10**.
10. **TOP 10 filmes do gênero drama** exibidos em **2016**.

## 🔍 Abordagem
✔️ Importação de dados para o **PostgreSQL**.  
✔️ Análise e **respostas a 10 perguntas relevantes** utilizando consultas SQL avançadas.  
✔️ **Operações de junção, agrupamento e filtros** para extrair insights significativos dos dados.  
