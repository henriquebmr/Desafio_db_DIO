# 🏎️ Porsche Sales Analytics Dashboard

Dashboard interativo desenvolvido para análise comercial e inteligência de dados a partir de uma base sanitizada com **100 registros de vendas da Porsche**.

🔗 **Acesse o Dashboard Online:** [https://henriquebmr.github.io/Desafio_db_DIO/](https://henriquebmr.github.io/Desafio_db_DIO/)

---

## 🎯 Perguntas de Negócio Respondidas

O dashboard foi projetado para responder a três perguntas estratégicas de desempenho comercial:

1. **Quais modelos da Porsche geram a maior receita total (USD)?**
   - *Análise:* Visualização em gráfico de barras horizontais indicando os top modelos por faturamento acumulado, permitindo identificar os veículos topo de linha mais rentáveis.
2. **Qual é a preferência comercial em termos de métodos de pagamento?**
   - *Análise:* Gráfico de rosca (*Doughnut*) demonstrando a representatividade financeira de cada meio de liquidação (*Wire Transfer*, *Credit Card*, *Financing*, *Crypto*, etc.).
3. **Como se comporta a distribuição geográfica do faturamento nos EUA?**
   - *Análise:* Gráfico de colunas indicando o Top 10 estados americanos em volume financeiro e concentração de vendas.

---

## 🛠️ Tratamento e Sanitização da Base de Dados

A base de dados passou por um processo prévio de limpeza para garantir a consistência técnica dos dados:
- **Tratamento de Datas Inválidas:** Identificação de registros inconsistentes do calendário (ex: *30/02*, *31/04*) que foram sanitizados.
- **Normalização Numérica:** Padronização dos preços e quilometragens para valores estritamente numéricos, removendo símbolos de moedas e unidades escritas em texto (*USD*, *$*, *k*, *miles*).
- **Higienização de Categorias:** Padronização de nomes de modelos, cidades, estados e métodos de pagamento.

---

## 💻 Prompts e Processo de Construção com IA

- **Assistente Utilizado:** Gemini AI (Engenharia de Prompts).
- **Estratégia de Prompting:**
  - Definição das 3 perguntas analíticas essenciais.
  - Especificação do layout em *Dark Mode* inspirado na identidade visual da Porsche (tons escuros com acentos em dourado `#D97706`).
  - Solicitação de código em arquivo único (`index.html`) utilizando **Tailwind CSS** para estilização flexível e **Chart.js** para renderização de gráficos reativos.
  - Implementação de filtros combinados em JavaScript puro (*Vanilla JS*) com recalculo de KPIs em tempo real.

---

## 🚀 Tecnologias Utilizadas

- **HTML5 & JavaScript (ES6+)**
- **Tailwind CSS (via CDN)**
- **Chart.js (via CDN)**
- **GitHub Pages (Hospedagem)**
