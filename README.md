# Atividade Integradora Fase 1 — Relatório Operacional de Pré-Decolagem

Projeto da **Missão Aurora Siger**: um sistema que analisa a telemetria de uma nave e decide se ela está pronta para decolar (**LANÇAR**) ou se a decolagem deve ser abortada (**ABORTAR**).

## Sobre o projeto

O sistema recebe 10 leituras dos sensores da nave (temperatura interna e externa, integridade estrutural, energia, pressão dos tanques e módulos críticos) e compara cada uma com faixas de segurança definidas. Se todos os valores estão dentro do normal, autoriza o lançamento; se qualquer um está fora, aborta. Além disso, o projeto calcula a autonomia energética da nave e conta com uma análise independente feita por IA.

## Tecnologias utilizadas

- Python
- pandas
- Google Colab

## Como executar

1. Abra o arquivo `FIAP_FASE_1.ipynb` no Google Colab.
2. No menu, clique em **Ambiente de execução → Executar tudo** (Runtime → Run all).
3. As células rodam de cima para baixo e mostram a tabela de dados, a decisão de cada leitura (LANÇAR/ABORTAR) e a autonomia energética.

## Prints da execução

### Tabela de telemetria
<img width="826" height="340" alt="tabela dataset" src="https://github.com/user-attachments/assets/389cad65-819a-494e-8cc4-d90b9fe0f849" />

### Decisão do script (LANÇAR / ABORTAR)
<img width="1220" height="596" alt="script python" src="https://github.com/user-attachments/assets/fafeb72f-a643-42e7-a465-5974c64dff19" />

### Análise energética
<img width="1262" height="378" alt="Análise energética" src="https://github.com/user-attachments/assets/835625df-8058-49c9-92c0-3f59f343326f" />

## Autor

Gabriel Storer Romero — RM575479
