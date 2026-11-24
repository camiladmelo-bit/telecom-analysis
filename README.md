# ConnectaTel: Análise de Clientes e Padrões de Uso

Projeto do Sprint 8 do curso de Análise de Dados. O objetivo é analisar os dados de usuários e de uso (chamadas e mensagens) da operadora ConnectaTel para entender o perfil dos clientes e apoiar estratégias de retenção.

## O que foi feito

- Carregamento e exploração inicial dos dados (`users`, `usage` e `plans`).
- Limpeza dos dados: valores sentinela (-999 em idade, "?" em cidade), datas inválidas e valores ausentes.
- Padronização de datas e agregação do uso por usuário.
- Identificação de outliers com boxplots e o método IQR.
- Segmentação de clientes por nível de uso e por faixa de idade.
- Análise executiva com problemas detectados, principais achados e recomendações.

## Tecnologias

Python, pandas, NumPy, Matplotlib e Seaborn (Jupyter Notebook).
