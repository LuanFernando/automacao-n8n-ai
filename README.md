# automacao-n8n-ai

Repositório com automações integrando **n8n** e **IA** para criação de agentes inteligentes utilizando RAG e PGVector.

---

## 🔧 Requisitos para rodar as automações

### 1. Banco Vetorial (PGVector)

- Instale o PGVector seguindo as instruções oficiais: [pgvector/pgvector](https://github.com/pgvector/pgvector).

### 2. Plataforma de Automação (n8n)

- Instale o **n8n** localmente ou utilize na nuvem.  
  Guia rápido de instalação: [Como instalar n8n de graça no seu computador](https://autotic.com.br/como-instalar-n8n-de-graca-no-seu-computador-com-apenas-1-comando/).

### 3. Chave de API do Gemini

- Gere sua **Gemini API Key**: [Google AI Studio](https://aistudio.google.com/apikey).

### 4. Acesso ao Google Drive

- Configure as credenciais e permissões no [Google Cloud Console](https://console.cloud.google.com/).
- Crie uma pasta no Google Drive para armazenar os documentos que serão utilizados no workflow.

---

## ⚙️ Configuração no n8n

1. Adicione no **n8n** as credenciais do:
   - **Gemini API**
   - **Google Drive**
2. Configure os workflows para utilizar a pasta criada no Google Drive como fonte de documentos.
3. Certifique-se de que o PGVector esteja ativo e acessível para o n8n.

---

## 📌 Observações

- Esta automação utiliza a técnica **RAG (Retrieval-Augmented Generation)** para fornecer respostas mais precisas.
- O PGVector é utilizado para armazenar e buscar vetores dos documentos.
