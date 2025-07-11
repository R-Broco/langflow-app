# Langflow App - Deploy no Render

Este repositório tem como objetivo hospedar uma instância do Langflow na plataforma Render, para ser utilizada como motor de IA em projetos como o [CRM-IABroco.

## 🚀 Deploy no Render

### Pré-requisitos

- Conta no Render
- Repositório clonado e conectado ao Render

### Estrutura esperada

- `start.sh` com:
  ```bash
  langflow run --host 0.0.0.0 --port $PORT
  ```
