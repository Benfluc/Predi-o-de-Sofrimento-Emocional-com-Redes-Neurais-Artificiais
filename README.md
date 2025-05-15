# Predição de Sofrimento Emocional com Redes Neurais Artificiais
Modelo preditivo com redes neurais artificiais (MLP e RBF) treinado com dados da PNS 2019 para identificar sinais de sofrimento emocional no Brasil. Utiliza 24 variáveis sociais, comportamentais e de saúde. Alta acurácia e sensibilidade, com potencial uso em triagens de saúde pública.
Este repositório apresenta um estudo aplicado de aprendizado de máquina voltado à saúde mental pública no Brasil. Utilizando os microdados da Pesquisa Nacional de Saúde (PNS) 2019, foi desenvolvido um modelo preditivo baseado em Redes Neurais Artificiais (RNA) para identificar sinais de sofrimento emocional, como ansiedade, depressão e limitações psicossociais.

A base de dados foi cuidadosamente balanceada, totalizando 17.546 registros com 24 variáveis selecionadas entre domínios socioeconômicos, comportamentais e de saúde geral. Dois modelos foram testados: uma rede MLP (Perceptron Multicamadas) e uma rede RBF (Função de Base Radial), ambos executados 20 vezes para garantir estabilidade e confiabilidade nos resultados.

O modelo MLP foi o que apresentou melhor desempenho, com média de 87,58% de acurácia e recall de 91,50% para a classe positiva (indivíduos com sofrimento emocional), destacando sua elevada sensibilidade. Os resultados indicam que o modelo é capaz de identificar corretamente a maioria dos casos relevantes com baixa taxa de falsos negativos.

A proposta é que este tipo de solução possa ser aplicada como ferramenta de triagem automatizada em contextos como Unidades Básicas de Saúde (UBS), auxiliando na priorização de atendimentos e no planejamento de políticas públicas baseadas em dados.

O repositório inclui o código de pré-processamento, balanceamento da base, treinamento dos modelos, avaliação de desempenho e visualizações como a curva ROC.

O arquivo 'df_balanceado' traz o dataset utilizado e o arquivo 'modelo_balanceado' apresenta o código MLP.
