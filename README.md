# 🧠 Automação de Análises e Transformações com OpenAI

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-red)](https://pandas.pydata.org/)
[![OpenAI API](https://img.shields.io/badge/OpenAI-ChatGPT-brightgreen)](https://openai.com/)
[![ETL Pipeline](https://img.shields.io/badge/ETL-Pipeline-orange)](#)

🚀 Este projeto automatiza **transformações de dados** e **análises exploratórias** utilizando a API da **OpenAI** (ChatGPT). A ideia é permitir que a IA **analise colunas**, **sugira tratamentos** e **execute comandos automaticamente**, gerando gráficos e insights sem precisar de intervenção manual.

---

## 📌 **Funcionalidades Principais**
✅ **🛠️ Transformação Automática de Dados** 
✅ **📊 Análises Exploratórias Dinâmicas**
✅ **🔍 Limpeza Inteligente de Dados**
✅ **🤖 Integração com OpenAI para Sugestões Automáticas**
✅ **📉 Geração Automática de Gráficos e Relatórios**

---

## 🔧 **Como Funciona?**
O projeto processa um dataset CSV (ou qualquer outro formato suportado para criação de DataFrame), identifica colunas problemáticas e **usa a IA para sugerir e executar transformações**. Além disso, qualquer pergunta sobre os dados pode ser enviada à IA, que **gera códigos prontos para execução automática**.

**📌 Exemplo de fluxo:**

1️⃣ Carrega e processa os dados
2️⃣ A IA analisa as colunas e sugere transformações
3️⃣ O código é executado automaticamente 
4️⃣ Insights e gráficos são gerados conforme perguntas do usuário 

---

## 📂 **Arquitetura do Código**
```
📦 projeto
 ┣ 📜 openai_project.py                 # Código principal com todas as funções
 ┣ 📜 dataset.csv (exemplo)             # Base de dados analisada (pode ser substituída)
 ┣ 📜 README.md                         # Documentação
 ┗ 📜 requirements.txt                  # Dependências do projeto
```

---

## 🛠 **Configuração e Instalação**
### **1️⃣ Clone o Repositório**
```bash
git clone https://github.com/RenanBjj/Python-AI-Data-Cleaner.git
cd Python-AI-Data-Cleaner
```

### **2️⃣ Instale as Dependências**
```bash
pip install -r requirements.txt
```

### **3️⃣ Configure a API Key da OpenAI**
Crie um arquivo **`.env`** e adicione sua chave da OpenAI:
```env
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxx
```

Ou, diretamente no código:
```python
import openai
openai.api_key = "sk-xxxxxxxxxxxxxxxxxxxxxxxx"
```

### **4️⃣ Execute o Projeto**
```bash
python openai_project.py
```

---

## 🚀 **Exemplos de Uso**
### **🔹 Transformação de Dados**
A IA analisa colunas e aplica tratamentos automaticamente:

```python
realizar_transformacao("Stock Quantity")
```
📌 *Exemplo de saída:*
```
📌 Trabalhando na coluna: Stock Quantity
✅ Coluna convertida para float sem perda de dados
```

---

### **🔹 Análises Exploratórias**
Basta fazer uma pergunta que a IA responde com código pronto para execução!

```python
fazer_pergunta("Quais classificações etárias vendem mais?")
```
📌 *Exemplo de saída:*
```
📊 Gráfico gerado com vendas por classificação etária
```
---

## 📊 **A IA gera insights automáticos sobre os dados, permitindo análises dinâmicas, como:**
🔹 **Qual publisher tem mais jogos em estoque?**
🔹 **Existe correlação entre idade do público e preço do jogo?**
🔹 **Qual mês teve mais pedidos enviados?**
🔹 **Quais produtos estão com baixo estoque?**

🚀 *Tudo isso é feito automaticamente!*

---

## 📌 **Tecnologias Utilizadas**
🔹 **Python**
🔹 **Pandas** - Manipulação e limpeza de dados
🔹 **Matplotlib & Seaborn** - Geração de gráficos
🔹 **OpenAI API** - Sugestões automáticas e execução de código

---

## 🤝 **Contribuição**
Se este projeto te ajudou de alguma forma, deixe uma ⭐ e contribua! Sugestões e melhorias são sempre bem-vindas!

Aqui estão algumas formas de ajudar:

1. **⭐ Dê uma estrela no repositório**
2. **💡 Sugira novas funcionalidades** via Issues
3. **🛠 Contribua com código** via Pull Requests

---

## 📜 **Licença**
Este projeto é open-source.

---

## 📬 **Contato**

Para dúvidas ou sugestões:

- **Renan Marques**
  - [GitHub](https://github.com/RenanBjj)
  - [LinkedIn](https://www.linkedin.com/in/renan-marques-rodrigues/)
  - [Email](mailto:renanbjj88@gmail.com)

---

🚀 Criado por [Renan Marques](https://github.com/RenanBjj) com ❤️ e muita automação 🤖!
```
