# Modelo para Apresentação do Lab06 - Artigo de Dataset Público

# Aluno
* `233895`: `Enrico Piovesana Fernandes`

# Análise do Artigo `MusicOSet: An Enhanced Open Dataset for Music Data Mining`

| campo | valor |
|------------|----------------------------------------|
| referência | `https://marianaossilva.github.io/DSW2019/index.html` |
| link       | `https://marianaossilva.github.io/DSW2019/assets/data/paper.pdf` |
| dataset | `https://marianaossilva.github.io/DSW2019/#downloads` |
| formato | `.sql, .csv` |

## Resumo

> O artigo propõe a construção de um banco de dados tratando de informações sobre músicas especializado para data mining. Mais especificamente, o artigo cónstroi três bancos de dados diferentes contendo informações sobre músicas: 
- O primeiro banco de dados **Popularity** possui dados sobre a popularidade de determinadas músicas, contendo informações sobre rankings de músicas, albums e artistas de acordo com as Billboard charts, sendo os dados de album e músicas coletados das charts de Hot 100 e Billboard 200, a do artista foi montada a partir das outras duas colunas.
- O segundo banco de dados **Metadata**, a informação numérica e textual relacionada as músicas, artistas e álbums, sendo esses dados coletados do Spotify e categorizou os tipos de artistas de acordo com a API do Wikipedia
- O terceiro **Song Features.** lista as features das músicas, a Letra e as features acústicas. As features acústicas contém digitais acústicas coletadas diretamente do Spotify, como nota, intensidade, tempo e duração. Outras features subjetivas como dançabilidade e eneriga foram calculadas usando a ferramenta The Echo Nest's.

## Perguntas de pesquisa/análises

> É possível fazer tanto análises de popularidade por tempo de artistas, albums e músicas individuais, como classificar eles por diferentes atributos e categorias, tanto objetivos quanto subjetivos e possívelmente analizar quais características são mais influenciais.
- Qual/quando/por quanto tempo foi o ápice de popularidade de uma música/artista/album?
- Um ranking de músicas de um gênero específico clássificadas por sua popularidade
- Qual a maior posição ocupada por uma música no ranking de popularidade e quanto tempo em semanas durou essa popularidade
- Um diagrama de popularidade de um artista 

## Trabalhos relacionados

- The RWC Music Database [Goto et al. 2003]
- Computer Audition Lab 500-song (CAL500) [Turnbull et al. 2008]
- The Million Song Dataset (MSD) [Bertin-Mahieux et al. 2011]
- MusiClef dataset [Schedl et al. 2013]
- Track Popularity Dataset (TPD) [Karydis et al. 2016]
