# CodeHealth CI/CD Pipeline

Este repositório contém o pipeline de Integração Contínua e Entrega Contínua (CI/CD) da startup CodeHealth, que está desenvolvendo um sistema de agendamento médico. O objetivo é automatizar o processo de build, teste e deploy de forma eficiente e segura.

## Estrutura do Repositório

- `main.py`: código simples que imprime uma mensagem.
- `.gitignore`: ignora arquivos desnecessários.
- `.github/`: contém a configuração do GitHub Actions.

## Fluxo do Pipeline

1. Quando um commit é feito na branch `develop`, o pipeline de CI é acionado.
2. O código é testado e, se aprovado, é enviado para o ambiente de homologação.
