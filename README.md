# deep-neural-networks
Estudos feitos na disciplina do mestrado em Redes Neurais Profundas

Conceitos relacionados às Redes Neurais Profundas; Redes Neurais Lineares;
Perceptron Multicamadas; Redes Neurais Convolucionais (CNN): Convolução,
Padding, Stride, Pooling, Normalização e Regularização; Redes Neurais
Convolucionais Modernas: LeNet, AlexNet, VGG, ResNet, DenseNet; Redes Neurais
Recorrentes: Modelos Sequenciais, retropropagação em redes recorrentes; Redes
Neurais Recorrentes Modernas: GRU, LSTM, Bi-LSTM, Arquitetura Encoder-Decoder;
Mecanismos de Atenção; Visão Computacional; Data Augmentation, Redes Yolo, SSD,
RCNN, Fast-RCNN e Faster-RCNN, Redes Neurais Generativas (GANs); e Redes
Neurais Profundas de Aprendizado por Reforço: Reinforce, Q-Learning, DQN, DDQN e
Actor-Critic.

## Classificação de Imagens de Esportes usando Redes Neurais Convolucionais

A classificação de imagens é uma tarefa crucial no âmbito da visão computacional, com aplicações em diversas áreas, como o reconhecimento de objetos e o diagnóstico médico. Neste estudo, nos dedicamos ao desafio de classificar imagens de diferentes esportes usando Redes Neurais Convolucionais (CNNs) com a biblioteca PyTorch.

O conjunto de dados engloba 100 categorias esportivas, totalizando 13.493 imagens para treinamento, 500 para testes e outras 500 para validação. Foram desenvolvidos dois modelos de CNNs: um empregando técnicas convolucionais tradicionais, e outro com uma abordagem manual na camada de convolução. Ambos os modelos foram treinados e sua performance foi avaliada por meio de métricas de acurácia. A meta estabelecida era alcançar uma acurácia superior a 90% como referência.

Os resultados obtidos estão em consonância com a literatura vigente, que também destaca o êxito das redes neurais convolucionais na tarefa de classificação de imagens. Arquiteturas renomadas, como AlexNet, VGG, GoogLeNet e ResNet, têm demonstrado altas taxas de acurácia em variados conjuntos de dados. Contudo, é válido ressaltar que a escolha da arquitetura e das técnicas de regularização é dependente do contexto específico e das particularidades do conjunto de dados em análise.

No escopo deste estudo, o primeiro modelo, que adotou uma arquitetura convencional com implementações de dropout e normalização por lotes, obteve resultados superiores ao segundo modelo, o qual utilizou convolução manual. Isso sugere que a arquitetura convencional, com suas camadas convolucionais e técnicas de regularização, se mostrou mais adequada para a problemática de classificação de imagens esportivas.

Além disso, a seleção do otimizador e dos hiperparâmetros, como a taxa de aprendizado e o momentum, pode impactar significativamente o desempenho do modelo. Neste estudo, empregamos o otimizador SGD com uma taxa de aprendizado de 0,001 e um momentum de 0,9. Explorar diferentes otimizadores e ajustar os hiperparâmetros constitui uma direção promissora para futuras pesquisas, visando aprimorar ainda mais o desempenho dos modelos.

Por fim, a utilização do livro "Dive into Deep Learning: Interactive deep learning book with code, math, and discussions. Implemented with PyTorch, NumPy/MXNet, JAX, and TensorFlow" desempenhou um papel fundamental no respaldo teórico e prático deste estudo. A obra proporcionou um entendimento aprofundado dos conceitos e técnicas de aprendizado profundo, além de exemplos práticos implementados em diferentes frameworks, incluindo o PyTorch, que foi empregado no presente trabalho.

Resumindo, este estudo fortalece a eficácia das Redes Neurais Convolucionais na classificação de imagens esportivas. Por meio da comparação entre um modelo convencional e outro com convolução manual, destacamos a relevância da seleção apropriada da arquitetura e das técnicas de regularização para atingir um desempenho superior. Essas descobertas contribuem para o avanço do campo da visão computacional e oferecem percepções valiosas para o desenvolvimento de modelos mais eficazes e precisos em tarefas semelhantes.
