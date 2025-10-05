# MAE (Mean Absolute Error)

O MAE é uma métrica adequada para este estudo porque mede a média dos erros absolutos entre os valores previstos e os valores reais, sem considerar a direção do erro. Conforme observado na primeira imagem, o modelo LSTM apresentou um MAE de 1.5219, enquanto o Prophet registrou 2.1878, indicando que o LSTM teve, em média, previsões mais próximas dos valores reais.

# Justificativa da escolha do MAE:

De acordo com Hyndman e Koehler (2006) em seu artigo "Another look at measures of forecast accuracy", o MAE é uma métrica preferível quando se deseja avaliar erros de previsão na mesma unidade da variável original. Esta característica torna o MAE mais interpretável e diretamente aplicável no contexto de previsões de temperatura, onde diferenças absolutas têm significado prático imediato.
O MAE é menos sensível a outliers comparado ao MSE (Mean Squared Error), o que é particularmente útil para séries temporais de clima, onde variações extremas ocasionais podem ocorrer. Como apontado por Chai e Draxler (2014) no artigo "Root mean square error (RMSE) or mean absolute error (MAE)?", o MAE fornece uma avaliação mais natural da magnitude média dos erros sem dar peso desproporcional a grandes desvios ocasionais.
No contexto de previsões climáticas, onde pequenas diferenças de temperatura podem ter impactos significativos, o MAE oferece uma métrica direta que permite avaliar o desempenho prático dos modelos para aplicações como planejamento agrícola, gestão energética ou alertas meteorológicos.
Referências:

* Hyndman, R. J., & Koehler, A. B. (2006). Another look at measures of forecast accuracy. International Journal of Forecasting, 22(4), 679-688.

* Chai, T., & Draxler, R. R. (2014). Root mean square error (RMSE) or mean absolute error (MAE)? Arguments against avoiding RMSE in the literature. Geoscientific Model Development, 7(3), 1247-1250.
