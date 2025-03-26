Processamento de Imagens com Correlação 2D e Aumento de Dados
📌 Descrição do Projeto
Este projeto implementa operações de processamento de imagens utilizando correlação 2D para aplicar filtros, além de um sistema de aumento de dados que realiza transformações como flip horizontal, rotação aleatória e zoom aleatório.

A implementação é feita em Python no Google Colab, com o objetivo de explorar filtros como Gaussiano (5x5) e Sobel horizontal, além de visualizar e analisar os efeitos dessas operações nas imagens.

📚 Fundamentação Teórica
O processamento de imagens é uma área essencial da visão computacional e aprendizado de máquina. Duas operações fundamentais são:

Correlação 2D: Multiplica os valores de um filtro (ou kernel) por pixels da imagem e soma os resultados.

Aumento de Dados: Aplica transformações para gerar variações de uma imagem, evitando overfitting em modelos de aprendizado profundo.

O projeto utiliza filtros clássicos:

Filtro Gaussiano (5x5): Suaviza a imagem, removendo ruídos.

Filtro Sobel Horizontal: Detecta bordas na direção horizontal.

🎯 Objetivos
✔ Implementar a correlação 2D separadamente para os canais R, G e B.
✔ Criar um sistema para aumentar dados de imagens.
✔ Armazenar os filtros e parâmetros em um arquivo externo para facilitar a modificação.
✔ Visualizar e comparar os resultados das operações aplicadas às imagens.

🔧 Materiais e Métodos
📂 Ferramentas Utilizadas
Python (Google Colab)

Bibliotecas: numpy, opencv (cv2), matplotlib, tensorflow

📌 Atividades Desenvolvidas
Leitura e Exibição das Imagens

Implementação da Correlação 2D

Definição dos Filtros e Parâmetros em um arquivo separado

Aplicação dos Filtros nas Imagens

Implementação do Aumento de Dados

Visualização e Análise dos Resultados

📊 Resultados e Discussão
O filtro Gaussiano suavizou as imagens conforme esperado, reduzindo ruídos.

O filtro Sobel horizontal evidenciou bordas, mostrando detalhes estruturais da imagem.

O aumento de dados gerou variações úteis das imagens, tornando-as mais robustas para possíveis aplicações em aprendizado de máquina.

✅ Conclusão
O projeto mostrou como correlação 2D e aumento de dados são ferramentas poderosas no processamento de imagens. As operações implementadas podem ser usadas para melhoria de imagens, segmentação e treinamento de redes neurais. O código pode ser expandido para incluir mais filtros e técnicas avançadas de pré-processamento.
