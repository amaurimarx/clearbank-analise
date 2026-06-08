# ClearBank — Análise Financeira de Transações

Projeto de análise financeira desenvolvido como desafio final do módulo de Python para Dados. Processa um arquivo CSV de transações bancárias, valida os registros, calcula métricas mensais, identifica movimentações suspeitas e exporta o resultado em JSON.

---

## 📁 Estrutura do Repositório

```
clearbank-analise/
├── desafio-final.ipynb   # Notebook principal com código e saídas salvas
├── transacoes.csv        # Arquivo de entrada com exemplo de transações
├── relatorio.json        # Gerado automaticamente ao executar o notebook
└── README.md             # Este arquivo
```

---

## ▶️ Como Executar

### No Google Colab (recomendado)

1. Acesse [colab.research.google.com](https://colab.research.google.com)
2. Faça o upload do arquivo `desafio-final.ipynb`
3. Faça o upload do arquivo `transacoes.csv` no painel de arquivos (ícone de pasta)
4. Execute as células **em ordem**, de cima para baixo (`Shift+Enter` ou `Runtime → Run all`)

### No Jupyter Notebook local

```bash
# Clone o repositório
git clone https://github.com/amaurimarx/clearbank-analise.git
cd clearbank-analise

# Abra o notebook
jupyter notebook desafio-final.ipynb
```

---

## 🐍 Compatibilidade

- Python **3.10+**
- Testado no Google Colab e Jupyter local
