# 🤖 Rede Neural com Funções de Ativação ReLU e Sigmoid 🚀

![Neural Network](https://media.giphy.com/media/3o7aCTfyhYawdOXcFW/giphy.gif)

## 📌 Descrição
Este projeto implementa uma rede neural simples para resolver o problema do **XOR**. A rede pode utilizar duas funções de ativação diferentes: **ReLU (Rectified Linear Unit)** e **Sigmoid**. O modelo é treinado usando **backpropagation** e comparado em termos de desempenho para ambas as funções de ativação.

## 🏗️ Estrutura do Modelo
- 🟢 **Entrada**: 2 neurônios (valores binários representando a entrada)
- 🏋️ **Camada Oculta**: 1 camada com 1 neurônio ativado por ReLU ou Sigmoid
- 🎯 **Saída**: 1 neurônio com ReLU ou Sigmoid
- 📉 **Função de Erro**: Erro Quadrático Médio (MSE)
- ⚡ **Otimizador**: Descida do Gradiente com taxa de aprendizado de 0.1

## 📦 Dependências
O projeto foi desenvolvido em Python e utiliza as seguintes bibliotecas:
```bash
pip install numpy matplotlib
```

## ▶️ Execução
Para executar o treinamento, basta rodar o script Python. O treinamento ocorrerá por **10.000 épocas**, exibindo o erro ao longo das iterações.

### 🔹 Executar com Sigmoid:
```bash
python sigmoid.ipynb
```

### 🔹 Executar com ReLU:
```bash
python relu.ipynb
```

Ao final, será exibido um gráfico mostrando a evolução do erro e os testes da rede com os valores de entrada.

## 📊 Resultados
O modelo tenta aprender a função XOR através de um aprendizado supervisionado. A saída esperada para cada entrada é:

| Entrada | Saída Esperada |
|---------|----------------|
| (0,0)   | 0              |
| (0,1)   | 1              |
| (1,0)   | 1              |
| (1,1)   | 0              |

A rede neural tenta minimizar o erro para que os resultados obtidos se aproximem dos valores esperados. 📈

🔹 **Comparação entre Sigmoid e ReLU:**
- ✅ **Sigmoid** tende a funcionar bem, mas pode sofrer com o problema do **vanishing gradient**, tornando o treinamento mais lento.
- ⚡ **ReLU** pode acelerar o aprendizado, mas é suscetível ao problema dos **neurônios mortos**.

## 🎥 Demonstração Visual
![Training Process](https://media.giphy.com/media/VbnUQpnihPSIgIXuZv/giphy.gif)

## 👨‍💻 Autor
Este código foi desenvolvido para fins educacionais como parte de um exercício de redes neurais. ✨
