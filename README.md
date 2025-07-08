# 📸 Análise de Dados do Instagram

Análise exploratória de dados do **Instagram**, focando em métricas como engajamento, horário de postagem, hashtags e desempenho de conteúdo.

---

## 📋 Sumário

- [Contexto & Objetivo](#-contexto--objetivo)  
- [📚 Bibliotecas Utilizadas](#-bibliotecas-utilizadas)  
- [📂 Estrutura do Projeto](#-estrutura-do-projeto)  
- [🛠️ Instalação & Execução](#-instalação--execução)  
- [🔍 Metodologia & Análise](#-metodologia--análise)  
- [📈 Resultados & Insights](#-resultados--insights)  
- [🧠 Conclusões](#-conclusões)  
- [🔭 Próximos Passos](#-próximos-passos)  
- [👤 Autor](#-autor)  
- [🤝 Contribuições](#-contribuições)  
- [📄 Licença](#-licença)

---

## 🧠 Contexto & Objetivo

Este projeto realiza uma análise de métricas de engajamento no Instagram (curtidas, comentários, impressões), avaliando padrões de comportamento do público, horários ideais de postagem, impacto de hashtags e o desempenho geral dos posts.

---

## 📚 Bibliotecas Utilizadas

- `pandas`, `numpy` — manipulação e análise de dados  
- `matplotlib`, `seaborn` — visualizações gráficas  
- `datetime` — processamento de datas e horários  
- `openpyxl` ou `xlrd` — importação de dados do Excel/CSV

---

## 📂 Estrutura do Projeto

- `instagram_analysis.ipynb` – notebook com toda a análise exploratória  
- `data/` – pasta contendo os datasets (CSV, Excel)  
- `requirements.txt` – dependências do projeto  
- `.gitignore` – arquivos/desnecessários ignorados pelo Git

---

## 🛠️ Instalação & Execução

Pré-requisitos:
- Python 3.7+
- Jupyter Notebook

```bash
git clone https://github.com/PedroSilva0z/Instagram_analise_de_dados.git
cd Instagram_analise_de_dados

# (Opcional) ambiente virtual
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

```

--- 

## 🔍 Metodologia & Análise

1. Importação dos dados e inspeção inicial (df.head(), df.info()).
2. Limpeza dos dados: remoção de duplicatas e registros ausentes.
3. Conversão de datas, extração de dia da semana e horário das postagens.
4. Criação de métricas como taxa de engajamento = (likes+comments)/impressions.
5. Visualizações:
  - Distribuição de engajamento por faixa de horário e dia da semana.
  - Relação entre número de hashtags e engajamento.
  - Evolução temporal das métricas ao longo dos meses.

6. Segmentação: agrupamentos por tipo de conteúdo ou hora de postagem (com KMeans).
7. Extração de insights para otimizar estratégia.

--- 

## 📈 Resultados & Insights

1. Identificação dos melhores horários e dias da semana para publicar.
2. Verificou-se correlação entre número de hashtags e maior engajamento, até um certo ponto.
3. Observou-se sazonalidade mensal no desempenho das postagens.
4. Clusters de posts com alto, médio e baixo desempenho ajudaram a traçar padrões de conteúdo.

--- 

## 🧠 Conclusões

- Postar nos períodos de maior engajamento (por exemplo, sextas-feiras entre 18h–20h) tende a gerar melhores resultados.
- Utilizar hashtags relevantes — mas sem exagero — pode aumentar a visibilidade.
- Posts com alcance inesperadamente baixo foram identificados, possibilitando revisão de conteúdo.
- Clusterização auxiliou na criação de uma matriz de conteúdo e priorização estratégica.

--- 

## 👤 Autor
Pedro Silveira

📍 São Paulo, Brasil

🔗 LinkedIn

--- 

## 🤝 Contribuições

Contribuições são bem-vindas!

Abra uma issue ou envie um pull request com novas análises, visualizações ou otimizações.
