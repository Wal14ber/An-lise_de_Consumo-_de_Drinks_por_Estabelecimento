# 🍹 Análise de Consumo de Drinks por Estabelecimento

Este repositório contém um pequeno projeto de análise de dados em Python, utilizando um arquivo Excel com informações de **pessoas atendidas por estabelecimento** e **consumo de produtos (DRINKS e SOFT DRINKS)**.

O objetivo é responder perguntas como:
- Qual estabelecimento consome mais DRINKS por pessoa?
- Qual o consumo médio de DRINKS e SOFT DRINKS por pessoa em cada loja?
- Quais são os **top 5 produtos** mais consumidos por estabelecimento e categoria?

---

## 🧱 Estrutura do Projeto

- `drinks.ipynb` → Notebook com todo o código da análise.
- `dados.xlsx` → Arquivo Excel com as bases:
  - **Por Canal** → Quantidade de pessoas por estabelecimento.
  - **Consumo de Produtos** → Consumo de produtos por estabelecimento, categoria e descrição.

*(Os nomes das abas podem ser ajustados no notebook, caso sejam diferentes.)*

---

## 🛠 Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter/Google Colab

---

## 🚀 Como executar no Google Colab

1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Clique em **File → Upload notebook** e envie o arquivo `drinks.ipynb`.
3. No Colab, na primeira célula, faça o upload do arquivo `dados.xlsx` (já está previsto no código com `files.upload()`).
4. Execute as células na ordem (Shift + Enter).

---

## 💻 Como executar localmente (VS Code ou Jupyter)

1. Clone este repositório:

   ```bash
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   cd SEU_REPOSITORIO

   📄 Licença

Este projeto é de uso pessoal/educacional.
Sinta-se à vontade para adaptar, melhorar e utilizar como base para outros estudos de análise de dados.
