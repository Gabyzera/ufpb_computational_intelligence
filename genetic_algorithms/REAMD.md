# Algoritmo Genético para Otimização de Função

Este projeto implementa um **Algoritmo Genético (GA)** para encontrar o mínimo de uma função matemática dentro de um espaço de busca definido. O código pratica a seleção por meio do método de seleção **torneio**.

## 📌 Objetivo
O objetivo é encontrar o valor **x** que minimiza a função objetivo **f(x)** dentro do intervalo **[-2π, 2π]**.

## 🔧 Estrutura do Código
O projeto é estruturado da seguinte forma:

1. **Definição da Função Objetivo**  
   - A função objetivo **f(x)** é definida com termos trigonométricos e quadráticos.

2. **Codificação e Decodificação**  
   - Cromossomos são representados como sequências binárias e convertidos para valores reais dentro do intervalo de busca.

3. **Operadores Genéticos**  
   - **Geração inicial da população**
   - **Seleção** (Torneio)
   - **Crossover** (Troca de genes entre pais)
   - **Mutação** (Modificação aleatória dos genes)

4. **Execução do Algoritmo Genético**  
   - O GA roda por um número fixo de gerações, buscando soluções cada vez melhores.

5. **Exibição dos Resultados**  
   - Impressão do melhor cromossomo e sua solução correspondente.

## ⚙ Parâmetros do Algoritmo
- **Tamanho da população**: 50 cromossomos
- **Bits por variável**: 10
- **Probabilidade de crossover**: 0.7
- **Probabilidade de mutação**: 0.01
- **Número de gerações**: 100

## 🚀 Como Executar o Projeto
1. Instale as dependências necessárias:
   ```bash
   pip install numpy matplotlib
   ```
2. Execute o código Python no terminal ou em um notebook Jupyter.