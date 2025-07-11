# langflow-app
Criar e Hospedar o LangFlow no Render

## 📁 Repositório: `langflow-app`

### 🧠 Propósito
Este repositório contém a instância do **Langflow**, uma interface visual para fluxos de IA com LangChain. Ele é usado como **motor de processamento de linguagem natural** para interpretar mensagens recebidas pelo CRM.

### ⚙️ Configuração

- Clona o repositório oficial do Langflow.
- Usa `start.sh` para iniciar o servidor com:
  ```bash
  langflow run --host 0.0.0.0 --port $PORT
  ```

### 🚀 Como testar

1. Acesse a URL pública do Render (ex: `https://langflow-app-xxxx.onrender.com`).
2. Crie um fluxo simples com entrada de texto e saída de resposta.
3. Copie o endpoint do fluxo e use como valor da variável `LANGFLOW_ENDPOINT` no CRM.

### 📦 Deploy

- Plataforma recomendada: **Render**
- Tipo de serviço: **Web Service**
- Porta: `$PORT`
- Comando de inicialização:  
  ```bash
  ./start.sh
  ```
