# Projeto Sprint 8 — Y.Afisha: Otimização de Marketing com Análise de Produto e Vendas

Análise do comportamento de usuários, performance de vendas e eficiência de marketing para a empresa **Y.Afisha**, com o objetivo de otimizar os gastos em aquisição de clientes. Utilizando dados de sessões, pedidos e custos, foi possível avaliar o funil de conversão, o valor gerado por cliente (LTV) e o retorno sobre o investimento (ROI).

## 📌 Lista de Projetos

| Sprint | Nome do Projeto                                     | Link                                                                                                                                    |
| ------ | --------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| 1      | Quiz: Avaliação e Correção de Dados de Usuário      | [Ver projeto](https://github.com/gschmidel19/sprint-01-quiz-qualidade-dados/tree/main/sprint-01-quiz-qualidade-dados)                   |
| 2      | Teste de Hipótese: Preferências Musicais por Cidade | [Ver projeto](https://github.com/gschmidel19/sprint-02-preferencias-musicais-cidades/tree/main/sprint-02-preferencias-musicais-cidades) |
| 3      | Análise de Teste A/B em Loja Online                 | [Ver projeto](https://github.com/gschmidel19/sprint-3-ab-test-analysis/tree/main/sprint-3-ab-test-analysis)                             |
| 4      | Análise Estatística de Dados: Plano Megaline        | [Ver projeto](https://github.com/gschmidel19/Sprint_4_Megaline/tree/main/Sprint_4_Megaline)                                             |
| 5      | Dashboard Interativo com Streamlit                  | [Ver projeto](https://testeaula-vadtlkgochzupctcfyxgp6.streamlit.app)                                                                   |
| 6      | Análise de Vendas de Jogos: Ice Game Store          | [Ver projeto](https://github.com/gschmidel19/Sprint_6_VideoGame_Sales/tree/main/Sprint_6_VideoGame_Sales)                               |
| 7      | Teste A/A/B no App Zuber                            | [Ver projeto](https://github.com/gschmidel19/Sprint_7_Zuber/tree/main/Sprint_7_Zuber)                                                   |
| 8      | Otimização de Marketing: Y.Afisha                   | [Ver projeto](https://github.com/gschmidel19/Sprint_8_YAfisha/tree/main/Sprint_8_YAfisha)                                                                          |

## 🧠 Introdução

Você tem:

* Logs do servidor com dados sobre os acessos a Y.Afisha (jan/2017 a dez/2018)
* Arquivo com todos os pedidos realizados
* Estatísticas de despesas com marketing

Você vai analisar:

* Como as pessoas usam o produto
* Quando começam a comprar
* Quanto dinheiro cada cliente traz para a empresa (LTV)
* Quando as despesas serão cobertas (ROI)

---

## 📊 Tecnologias e bibliotecas aplicadas

* **Linguagem:** Python
* **Ferramentas:** Jupyter Notebook, Git, GitHub
* **Bibliotecas:**

  * `pandas` — manipulação de dados
  * `numpy` — cálculos numéricos
  * `matplotlib`, `seaborn` — visualizações
  * `scipy.stats` — testes estatísticos
  * `datetime` — manipulação de datas

---

## 🔬 Práticas aplicadas

* Análise de sessões e comportamento de uso
* Agrupamento por coorte de aquisição
* Cálculo de conversão diária (0d, 1d, etc.)
* Lifetime Value (LTV)
* CAC e ROI por origem de marketing
* Visualizações por origem e dispositivo

---

## 📂 Estrutura do Projeto

```
Sprint_8_YAfisha/
├── data/
│   ├── visits_log_us.csv
│   ├── orders_log_us.csv
│   └── costs_us.csv
│
├── notebooks/
│   └── sprint_8_yafisha.ipynb
│
├── results/
│   ├── ltv_plot.png
│   ├── roi_chart.png
│   └── funnel_conversion.csv
│
├── README.md
└── requirements.txt
```

---

## 🚀 Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/Sprint_8_YAfisha.git
```

2. Instale os pacotes:

```bash
pip install -r requirements.txt
```

3. Execute o notebook:

```bash
jupyter notebook notebooks/sprint_8_yafisha.ipynb
```

---

## 📦 Arquivo requirements.txt

```
pandas
numpy
matplotlib
seaborn
scipy
```

---

