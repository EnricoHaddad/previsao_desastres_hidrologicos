# Previsão de Desastres Hidrológicos
Trabalho de previsão de desastres hidrológicos no Brasil a partir da base de dados de desastres da Defesa Civil.

## Apresentação do Trabalho
Este é o primeiro trabalho na construção deste portfólio. Embora não seja um trabalho de business propriamente, eu espero que possa demonstrar minha forma de pensamento analítico bem como as habilidades técnicas desenvolvidas ao longo destes anos de estudos.

A escolha do tema se deu em nome de dois objetivos. Eu queria usar uma base nova, sem muitos projetos publicados de maneira a desafiar minhas próprias habilidades. E também busquei tratar de um tema importante, de impacto para o país. Acredito no poder transformador dos dados.

Caso queria avaliar técnicamente o trabalho, siga o link: https://colab.research.google.com/drive/1S6u5M5A_ildkCRicnFtXbYxDFao3rVol?usp=sharing

## Contextualização do Projeto
Em uma noticia de 11 de maio de 2024, o G1 afirma que mais de 2,1 milhões de pessoas foram afetadas pelas chuvas intensas no Rio Grande do Sul. São 130 mortos, 125 desaparecidos e 618 mil desabrigados. Dos 497 municípios do estado, 446 foram atingidos. A notícia ainda fala de R$ 50 milhões em auxílio do governo estadual para a reconstrução. Houve auxílio do governo federal e uma campanha nacional de arrecadação que chegou aos halls dos prédios, às academias e às grandes multinacionais.

Não faltam exemplos de desastres naturais. Todos os anos notícias sobre deslizamentos de terra no litoral aparecem nos jornais. Alagamentos, enchentes e enxurradas assolam o país que naturalmente não têm terremotos, furacões e vulcões. 

Todos esses eventos que afetam o país podem ser mitigados e evitados pela ação humana, salvando vidas, reduzindo a desigualdade e economizando nos cofres públicos.


Fontes: https://g1.globo.com/sp/sao-paulo/noticia/2024/09/30/agosto-e-setembro-de-2024-sao-meses-com-mais-registros-de-focos-de-incendio-em-sp-desde-1998.ghtml
https://g1.globo.com/rs/rio-grande-do-sul/noticia/2024/05/11/mais-de-21-milhoes-de-pessoas-foram-afetadas-pelo-temporal-no-rs-618-mil-estao-fora-de-casa.ghtml

## Análise Exploratória


Tanto a frequência de desastres quanto a de chuvas intensas revelam um padrão sazonal, dado que seus picos e vales no gráfico coincidem. Por exemplo, o pico após o mês 80 e os vales que existem próximos aos meses 20, 30 e 40. O último gráfico demonstra que há uma relação linear entre as variáveis, mas que não parece ser são forte.

<img width="1766" height="580" alt="image" src="https://github.com/user-attachments/assets/a3442dc7-8717-48d2-af76-7e1a3b1d16a0" />


Os gráficos mostram um padrão esperado. Nas estações mais úmidas, verão e primavera, há mais registros de chuvas e desastres hidrológicos. No outono-inverno há menos registros de todos os eventos. Por isso, os valores mais altos estão concentrado no começo e no final do ano.  Os meses de agosto e setembro, que são o final do inverno, apresentam os valores mais baixos. A semelhança dos gráficos revela um padrão esperado.

<img width="1682" height="543" alt="image" src="https://github.com/user-attachments/assets/7c37824d-a665-4471-bc63-7203f055da74" />

O gráfico compara as médias mensais para cada ano. Nos últimos 3 anos (2021-2023) houve um aumento na frequência das chuvas. No mais, não existe uma diferença evidente para cada ano.

<img width="1682" height="571" alt="image" src="https://github.com/user-attachments/assets/eac6e273-53ed-43e5-8cbb-f326e68890c8" />

Os gráficos de boxplot mostram o mesmo incremento de chuvas nos últimos ano e um incremento leve de desastres entre 2021 e 2023. As caixas para esses anos apresentam o limite do 1º quartil e medianas ligeiramente mais altos do que os anos anteriores.

<img width="1682" height="548" alt="image" src="https://github.com/user-attachments/assets/2a82c5ea-66d4-4f2c-90eb-02a0bdb6d075" />
