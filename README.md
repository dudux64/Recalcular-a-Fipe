# Calculadora de Preço de Veículos

Este projeto é uma aplicação gráfica simples desenvolvida em Python usando a biblioteca Dear PyGui. A aplicação permite calcular o preço final de um veículo com base no preço da tabela FIPE e uma nota de avaliação do veículo.

## Funcionalidades

- **Entrada de Dados:**
  - **Preço FIPE:** Campo de texto para o usuário inserir o preço FIPE do veículo.
  - **Nota de Avaliação:** Campo de texto para o usuário inserir a nota de avaliação do veículo (de 0 a 100).

- **Cálculo do Preço Final:**
  - Se a nota de avaliação for menor que 50, o preço final é reduzido em 20%.
  - Se a nota de avaliação estiver entre 50 e 80, o preço final é mantido.
  - Se a nota de avaliação estiver entre 80 e 100, o preço final é aumentado em 20%.
  - Exibição de mensagens de erro caso os valores inseridos não sejam válidos.

- **Interface Gráfica:**
  - Interface intuitiva com campos de texto e botão para cálculo.
  - Exibição do resultado do cálculo na própria janela da aplicação.

## Requisitos

- Python 3.x
- Biblioteca Dear PyGui

Você pode instalar a biblioteca necessária utilizando o pip:
```sh
pip install dearpygui
