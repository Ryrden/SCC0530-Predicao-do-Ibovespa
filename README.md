# Predição do Ibovespa - SCC0530 Inteligência Artificial

<div style="display: flex; flex-wrap: wrap;">
    <img src="https://i.imgur.com/iFBgxRD.png" alt="Capa do Projeto - Resultado Predição Ibovespa utilizando ibovespa como parametro" width="50%"/>
    <img src="https://i.imgur.com/pRN8R4G.png" alt="Capa do Projeto - Matriz de confusão" width="40%"/>
</div>
<br>

> Trabalho 2 da disciplina de Inteligência Artificial 2024/01

## Objetivo

O objetivo deste trabalho é aplicar técnicas de aprendizado de máquina para prever o comportamento do índice Ibovespa, visando auxiliar investidores na tomada de decisões financeiras. A proposta é analisar dados históricos e utilizar algoritmos preditivos para antecipar a tendência de subida ou descida do Ibovespa, considerando variáveis econômicas como SELIC, IPCA, PIB, cotação do dólar, petróleo, ouro e índices internacionais.

## Resultados

Os resultados demonstram que, ao utilizar apenas os atributos essenciais (SELIC, IPCA, PIB e dólar), os modelos preditivos apresentaram erros significativos e baixa eficiência. Com o enriquecimento do dataset com dados adicionais (preços de petróleo, ouro e índices internacionais), observou-se uma melhora nos resultados, embora ainda insatisfatórios. A inclusão de dados históricos do próprio Ibovespa (máxima, mínima e abertura do dia anterior) resultou em uma melhora significativa na precisão das previsões, com métricas de erro reduzidas e uma aproximação dos valores preditos aos valores reais. No entanto, a análise crítica revelou que o modelo ainda apresenta limitações em prever corretamente as tendências de alta e baixa, levando a decisões erradas de investimento em alguns casos. Mais detalhes sobre a metodologia, resultados e análises podem ser encontrados no relatório do projeto.

## Licença

Este projeto está sob licença. Consulte [LICENSE](LICENSE) para obter mais informações.
