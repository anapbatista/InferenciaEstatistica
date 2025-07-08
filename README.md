# Trabalho Prático — Inferência Estatística

## Objetivo

Este trabalho tem como objetivo investigar como os hábitos diários dos estudantes impactam seu desempenho acadêmico, representado pela nota no exame final.

Buscamos analisar se variáveis como:

- Horas de estudo por dia  
- Tempo de sono diário  
- Uso de redes sociais ou Netflix  

estão estatisticamente associadas à variável resposta:

- Nota no exame final (`exam_score`)

## Dataset

O conjunto de dados utilizado está disponível no Kaggle, no dataset **Student Habits vs Academic Performance**.

## Metodologia

Foram realizados os seguintes testes estatísticos para analisar as relações entre as variáveis:

- **Testes paramétricos**  
  - Teste de média (teste t de uma amostra) para comparar médias com um valor de referência.  
  - Teste de comparação de médias (teste t para duas amostras independentes) para verificar diferenças entre grupos.

- **Testes não paramétricos**  
  - Teste de Mann-Whitney para comparação de distribuições quando a normalidade não foi assumida.

- **Testes de associação**  
  - Teste Qui-quadrado e Correlação de Spearman para verificar associações entre variáveis categóricas (por exemplo, uso de redes sociais e desempenho).

As análises consideraram o nível de significância de 5% para rejeição das hipóteses nulas.

## Resultados

Os testes estatísticos indicaram evidências sobre a influência dos hábitos dos estudantes no desempenho acadêmico, permitindo identificar variáveis significativamente associadas à nota final.

## Integrantes

- Ana Paula de Abreu Batista — Nº USP: 12688424  
- Italo Carlos Martins Bresciani – Nº USP: 15461782  
- Luiz Gabriel Correia dos Santos – Nº USP: 15639682  
- João Pedro Barbosa Madeira — Nº USP: 13683038

## Como executar

1. Instalar as dependências necessárias (`pandas`, `scipy`, `numpy`, entre outras).  
2. Carregar o dataset no ambiente de trabalho.  
3. Executar os scripts de análise para reproduzir os testes e obter os resultados.
