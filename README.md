# 📘 Trabalho Prático (Projeto com Classificação Binária usando LLMs)

---
**Membros da Equipe:**

- Ademir Guimarães
- Arthur Bezerra
- Debora Barros
- Keven Gomes
- Pedro Carvalho
- Ronald Boadana
---


Este notebook realiza uma **análise exploratória de dados** utilizando bibliotecas como **Pandas**, **Matplotlib** e **Seaborn**.  
Também são aplicadas técnicas de **pré-processamento de texto**, como a **remoção de pontuação e stopwords** com a biblioteca **NLTK**.

Além disso, o projeto faz uso de modelos de linguagem baseados em **Transformers**, com o `SentenceTransformer` para gerar **embeddings semânticos** dos textos.  

Para inferência com **LLMs**, foi utilizado o modelo **LLaMA 3.1–8B-Instant**, acessado por meio da **API do Groq**.

---

## ⚙️ Pré-requisitos

- Conta no [Kaggle](https://www.kaggle.com) e chave da API (`kaggle.json`)
- Chave de API da [Groq](https://console.groq.com/)

---

## 🚀 Como usar

### 1. 🧪 Gere o arquivo .env contendo o nome do modelo e chave de API:
```json
GROQ_API_KEY=api_key
GROQ_MODEL=llama-3.1-8b-instant
```
### 2. 💾 Insira o arquivo .env na raiz do projeto.
### 3. 📥 Ao rodar tudo, na seção **'Explorando o dataset'** insira o arquivo kaggle.json gerado pela API do Kaggle 
```json
{
   "username":"kaggle_username",
   "key":"kaggle_api_key"
}
```
---

## 🧠 Observações
⚠️ Os testes foram realizados utilizando o serviço sob demanda da Groq.
A versão gratuita do modelo LLaMA 3.1 possui limitação no número de tokens por minuto (TPM), o que pode impedir a execução completa dos testes diretamente nessa modalidade.

⚠️ Ao rodar no ambiente do Colab, as bibliotecas necessárias já estão no notebook para instalação.


