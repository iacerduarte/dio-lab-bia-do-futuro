# Passo a Passo de Execução

## Setup do Ollama

```bash
# 1. Instalar Ollama (ollama.com)

# 2. Baixar um modelo leve
ollama pull phi4-mini

# 3. Testar se funciona
ollama run phi4-mini "Olá!"
```

## Código Completo

Todo o código-fonte está no arquivo `app.py`.

## Exemplo de requirements.txt

```
streamlit
openai
python-dotenv
```

## Como Rodar

```bash
# 1. Instalar dependências
pip install streamlit pandas requests

# 2. Garantir que Ollama está rodando
ollama serve

# 3. Rodar o app
streamlit run ./src/app.py
```
## Evidência de execução

<img width="1358" height="610" alt="evidencia" src="https://github.com/user-attachments/assets/72081367-72b0-4b66-b025-03dd88a6eb46" />

