# Painel Epidemiológico - Hepatites Virais

Este repositório contém os códigos Python utilizados para alimentar o painel epidemiológico da área técnica da Divisão de Vigilância Epidemiológica no setor de Hepatites Virais no Centro Estadual de Vigilância em Saúde(CEVS). 
O painel é desenvolvido no Google Data Studio e utiliza bases de informações populacionais e geográficas do Rio Grande do Sul.

## Estrutura do Repositório

- `ScripPainelHepatitesVirais_Atual.ipynb`: Código Python utilizado para processar e analisar dados relacionados às hepatites virais, preparando as informações para a visualização no Google Data Studio.

- `base_procv.csv`: Arquivo CSV contendo dados demográficos relacionados às demandas epidemiológicas no Rio Grande do Sul.

- `base_pop.csv`: Arquivo CSV com dados pupulacionais e demográficos do Rio Grande do Sul.

## Utilização

1. **Código Python**: O arquivo `ScripPainelHepatitesVirais_Atual.ipynb` contém o código Python utilizado para processar e analisar os dados. Recomenda-se a utilização de um ambiente Python configurado para execução deste código.

2. **Bases de Dados**: Os arquivos CSV (`base_procv.csv` e `base_pop.csv`) contêm os dados populacionais e demográficos necessários para o painel. **Atenção**: O arquivo HEPANET.dbf, que é a fonte original dos dados epidemiológicos, não está presente no repositório por conter informações sensíveis.

## Possíveis Erros e Sensibilidade dos Dados

É importante estar ciente de que os dados contidos nos arquivos CSV podem conter informações sensíveis e devem ser tratados com cuidado. Esteja atento à legislação e políticas de privacidade ao utilizar ou compartilhar esses dados.

## Estruturação do Código

O código Python foi estruturado para processar e analisar as informações contidas nas bases de dados de Hepatites Virais no RS e gerar dataframes apropriados para o painel no Google Data Studio. É recomendável revisar e adaptar o código de acordo com as necessidades específicas do projeto.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias, novas funcionalidades ou correções através de pull requests.
