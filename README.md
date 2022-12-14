# Análise de concorência com análise de sentimento

Descrição: 

Este caderno Jupyter contém o código Python para realizar análises da concorrência usando o processamento de linguagem natural (NLP) com a biblioteca TextBlob. O notebook foi criado como parte de um webinar sobre análise da concorrência com dados, onde o PNL foi usado para comparar três marcas de carros. O notebook inclui instruções passo a passo para instalação e uso do TextBlob, bem como código de exemplo e visualizações dos resultados da análise. Estes resultados podem fornecer uma visão valiosa das opiniões e preferências dos clientes, e podem ajudar a orientar as decisões comerciais.

O NLP é uma ferramenta poderosa que pode ser usada para extrair significado e insights dos dados do texto. Usando técnicas como a análise de sentimentos, que pode ser facilmente implementada com a biblioteca TextBlob, você pode obter valiosas percepções sobre as opiniões e preferências do cliente. Isto pode ser especialmente útil no contexto da análise da concorrência, onde você pode usar a NLP para comparar o sentimento dos clientes em relação aos diferentes produtos ou serviços oferecidos por seus concorrentes.

Para usar o TextBlob para análise de sentimentos, você precisa primeiro instalar as depêndencias usando o comando
```
pip install -r requirements.txt
```
Em seguida, você pode rodar o notebook e criar um objeto TextBlob a partir de uma sequência de texto. O objeto tem dois atributos, polaridade e subjetividade, que podem ser usados para determinar o sentimento do texto. A polaridade é um valor de flutuação dentro da faixa [-1, 1], onde -1 é o mais negativo e 1 é o mais positivo. A subjetividade também é um valor de flutuação dentro da faixa [0, 1], onde 0 é muito objetivo e 1 é muito subjetivo. Utilizando estes valores, você pode classificar o sentimento de um texto como positivo, negativo, ou neutro.

Resultados:

<p align="center">
  <img src="https://github.com/nicolasantero/Analise-de-concorrencia-com-analise-de-sentimento/blob/main/comp_marcas.png?raw=true" width="450" title="hover text">
  <img src="https://github.com/nicolasantero/Analise-de-concorrencia-com-analise-de-sentimento/blob/main/trend_marcas.png?raw=true" width="450" title="hover text">
</p>
