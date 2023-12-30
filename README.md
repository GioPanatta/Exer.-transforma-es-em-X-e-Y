# Análise de Gorjetas com Regressão Linear

## Visão Geral
Este projeto explora a relação entre a porcentagem da gorjeta (`tip_pct`) e o valor da conta líquida (`net_bill`) em um restaurante, utilizando diferentes modelos de regressão linear.

## Metodologia
Diversos modelos de regressão linear foram ajustados para analisar a relação entre `tip_pct` e `net_bill`. As abordagens incluíram:

1. **Modelo Linear Simples**: Relação direta entre `tip_pct` e `net_bill`.
2. **Modelo com Transformação Logarítmica**: Aplicação da transformação logarítmica em uma ou ambas as variáveis.
3. **Modelo Log-Log**: Ambas `tip_pct` e `net_bill` transformadas em escala logarítmica.

## Resultados
- O modelo log-log mostrou o melhor ajuste, com um R quadrado de 0.293 na escala logarítmica e 0.228 na escala original, indicando que este modelo capta uma relação mais complexa e possivelmente não linear entre as variáveis.
- Comparativamente, modelos com apenas uma variável transformada em logaritmo ou sem transformação logarítmica mostraram ajustes inferiores.

## Conclusões
- A análise sugere que a relação entre a porcentagem da gorjeta e o valor da conta líquida é melhor capturada em uma escala logarítmica, evidenciando uma relação mais complexa e não linear.
- A escolha do modelo depende do equilíbrio entre precisão e facilidade de interpretação.

## Tecnologias Utilizadas
- Python
- Pandas
- Statsmodels
- Numpy
- Seaborn (para visualizações
---

*Nota: Este README resume uma análise de dados realizada como parte de um projeto de ciência de dados.*
