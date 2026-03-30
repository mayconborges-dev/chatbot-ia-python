# 🤖 Chatbot com Inteligência Artificial em Python

Projeto de chatbot interativo desenvolvido com Python, utilizando Streamlit para interface e integração com a API da OpenAI para geração de respostas inteligentes.

---

## 🚀 Funcionalidades

- Interface de chat em tempo real
- Histórico de mensagens com `session_state`
- Integração com IA (OpenAI)
- Tratamento de erros (ex: falta de crédito ou falha na API)
- Uso de variáveis de ambiente para segurança da chave

---

## 🛠️ Tecnologias utilizadas

- Python
- Streamlit
- OpenAI API
- python-dotenv

---

## 📦 Como executar o projeto

### 1. Clone o repositório

```bash 
git clone https://github.com/mayconborges-dev/chatbot-ia-python.git
```

### 2. Instale as dependências

```bash 
pip install -r requirements.txt
```

### 3. Configure a chave da API

```env
OPENAI_API_KEY=sua_chave_aqui
```
### 4. Execute o projeto

```bash
python -m streamlit run main.py
```
