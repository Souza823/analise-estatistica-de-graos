## Análise Granulométrica com R <BR/>
Este script em R realiza a análise estatística de distribuições granulométricas (curvas de frequência por classes Phi) para um conjunto de amostras sedimentares. Ele executa os seguintes passos:

Importa e organiza os dados com frações percentuais para cada classe Phi (de 0 a 5) em diversas amostras (FN_01 a FN_10).

Normaliza os dados para obter frequências relativas.

Gera histogramas com curvas para cada amostra, mostrando visualmente a distribuição granulométrica.

Calcula e imprime no console as principais estatísticas sedimentológicas:

Média (phi): tendência central da distribuição.

Desvio padrão: grau de dispersão dos grãos.

Assimetria: indica a simetria da curva (positiva, negativa ou simétrica).

Curtose: mostra o grau de achatamento ou agudez da curva.

As visualizações são úteis para interpretar a textura do sedimento e comparar amostras. O script utiliza a biblioteca e1071 e a função barplot do R base para visualização gráfica.


