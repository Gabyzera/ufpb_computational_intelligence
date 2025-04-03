# 🤖Sistema de Inferência Fuzzy com scikit-fuzzy

Este projeto implementa um sistema de inferência fuzzy utilizando a biblioteca **scikit-fuzzy**. O objetivo é calcular a "guinhada" (ângulo de desvio) e a velocidade de um robô a partir de entradas de **distância** (0–10) e **ângulo** (0–10).

## 🎯 Objetivo

Determinar:
- **Guinhada**: Calculada com base na distância e no ângulo de aproximação, usando conjuntos fuzzy (Zero, Modesta, Média, Grande e Severa).
- **Velocidade**: Definida de forma simples conforme a distância (Lenta, Rápida e MuitoRápida).

## 🚧 Estrutura do Código

1. **Definição dos Universos**  
   - *distância*: 0 a 10  
   - *ângulo*: 0 a 10  
   - *guinhada*: 0 a 1.57 (rad)  
   - *velocidade*: 0 a 15

2. **Funções de Pertinência**  
   - *distância*: Pequena, Longa, MuitoLonga  
   - *ângulo*: Pequeno, Médio, Amplo  
   - *guinhada*: Zero, Modesta, Média, Grande, Severa  
   - *velocidade*: Lenta, Rápida, MuitoRápida

3. **Regras de Inferência**  
   - Definem a guinhada com base na combinação dos conjuntos fuzzy de distância e ângulo.  
   - Estabelecem a velocidade com base na distância.

4. **Simulação**  
   - Um exemplo de entrada é processado para mostrar as saídas de guinhada e velocidade.