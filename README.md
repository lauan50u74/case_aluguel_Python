# Exploração de Dados Imobiliários: Identificando as Melhores Oportunidades de Compra

O objetivo deste case é identificar as melhores oportunidades de compra de imóveis em Portugal e na Espanha com base em uma análise detalhada dos dados disponíveis. A meta era encontrar os melhores valores de casas, levando em consideração fatores relevantes que influenciam o mercado. Para isso, foi necessário:

Determinar quais dados são mais relevantes para o problema, como localização, tamanho do imóvel, idade da construção, entre outros.
Definir o setor ou o intervalo de preços mais adequado para análise (range de negócio).
Avaliar se os dados estão no formato correto e identificar quais informações adicionais podem ser extraídas.
Verificar se os dados estão limpos e íntegros, ou seja, se estão prontos para serem utilizados na análise sem erros ou inconsistências.

Etapas do Processo:
Carregamento e Visualização de Dados: O código começa com o carregamento de um arquivo Excel contendo dados de aluguel de casas. As primeiras e últimas linhas são exibidas para garantir a integridade dos dados, enquanto as colunas são ajustadas e renomeadas para facilitar a manipulação posterior.

Limpeza e Transformação dos Dados: Após a inspeção inicial, as colunas passam por ajustes para corrigir inconsistências e tipos de dados. As colunas que contêm valores numéricos, como rent_amount, property_tax e total, são convertidas para o tipo float, garantindo que estejam prontas para análise quantitativa.

Filtragem e Análise: Utiliza-se diferentes filtros para restringir os dados de acordo com critérios específicos, como limite de preço, aceitação de animais e número de quartos. Essa etapa permite uma segmentação dos imóveis de interesse, preparando-os para a análise mais detalhada.

Agrupamentos e Visualização de Dados: Os dados são agrupados por diferentes variáveis, como cidade, número de banheiros e quartos. Em seguida, são calculadas médias de preços e gerados gráficos que ajudam a visualizar a distribuição dos valores de aluguel, facilitando a interpretação dos resultados.

Análise de Preços por Andar: Explora-se a relação entre o andar do imóvel e o preço de aluguel, agrupando os dados por andar e gerando gráficos de barras para demonstrar as tendências de preços com base nessa variável.

Ferramentas e Bibliotecas Utilizadas:
Pandas: Para manipulação e limpeza dos dados.
Seaborn: Para visualização de dados com gráficos de barras e histogramas.
Matplotlib: Suporte à criação de visualizações gráficas.
