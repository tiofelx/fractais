# Visualizador do Conjunto de Mandelbrot

Este projeto é uma implementação em Python para a geração e visualização do Conjunto de Mandelbrot, um famoso fractal que é amplamente estudado na matemática complexa e visualizado em gráficos coloridos. Utilizando `numpy` e `matplotlib`, o programa permite a visualização de diferentes regiões do Conjunto de Mandelbrot, com a possibilidade de ajustar a resolução e o número máximo de iterações.

## Descrição

O Conjunto de Mandelbrot é definido como o conjunto de números complexos \(c\) para os quais a sequência definida por \(z_{n+1} = z_n^2 + c\) (com \(z_0 = 0\)) não tende ao infinito. O projeto implementa um algoritmo que calcula o número de iterações necessárias para determinar se um ponto pertence ao conjunto e gera uma visualização colorida do fractal.

## Funcionalidades

- **Geração do Conjunto de Mandelbrot:** Cálculo do Conjunto de Mandelbrot para uma determinada região do plano complexo, com base em parâmetros de entrada.
- **Visualização Gráfica:** Renderização do fractal usando `matplotlib`, com coloração baseada no número de iterações.
- **Personalização de Parâmetros:** Ajuste da região do plano complexo a ser visualizada, a resolução da imagem e o número máximo de iterações.

## Como usar

1. Clone o repositório para o seu ambiente local.
2. Certifique-se de ter o Python instalado.
3. Instale as dependências necessárias:

```bash
pip install numpy matplotlib
```
