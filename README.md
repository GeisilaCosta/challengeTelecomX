# challengeTelecomX

# Análise de Evasão de Clientes — Telecom X

## 📌 Descrição do Projeto

Este projeto realiza uma análise exploratória dos dados de clientes da Telecom X, focando no fenômeno de evasão (churn). O objetivo é identificar padrões e fatores que levam os clientes a cancelar seus contratos, fornecendo insights para a equipe de Data Science desenvolver estratégias de retenção e modelos preditivos.

---

## 🚀 Funcionalidades

- Importação dos dados diretamente da API da Telecom X
- Limpeza e tratamento dos dados (expansão, conversão de tipos, tratamento de valores ausentes e inconsistentes)
- Criação de novas variáveis, como conta diária e quantidade de serviços contratados
- Análise exploratória detalhada com gráficos e visualizações
- Identificação de fatores que influenciam a evasão, com base em variáveis categóricas e numéricas
- Análise opcional de correlações entre variáveis para suporte a modelagem preditiva

---

## 🛠 Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Requests (para consumo da API)

---

## 📁 Estrutura do Projeto

├── data/ # Dados brutos ou arquivos JSON (se houver)
├── notebooks/ # Notebooks com análises e relatórios
│ └── análise_churn.ipynb # Notebook principal do projeto
├── src/ # Scripts Python auxiliares (opcional)
├── README.md # Este arquivo
└── requirements.txt # Dependências do projeto


---

## 📖 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git
   cd seu_repositorio

   pip install -r requirements.txt

jupyter notebook notebooks/análise_churn.ipynb

jupyter notebook notebooks/análise_churn.ipynb

🎯 Resultados e Insights
Clientes com contratos mensais apresentam maior taxa de evasão.

Pagamentos via cheque eletrônico estão associados a maior churn.

O tempo de permanência e a quantidade de serviços contratados são fatores importantes na retenção.

Clientes com contas diárias mais altas tendem a evadir mais.

Recomendações para retenção incluem incentivos a contratos mais longos, melhoria no processo de pagamento e foco no atendimento inicial.

📚 Referências
Documentação do Pandas: https://pandas.pydata.org/docs/

Documentação do Seaborn: https://seaborn.pydata.org/

API Telecom X — Dados do projeto

🤝 Contribuição
Contribuições são bem-vindas! Para colaborar, por favor abra uma issue ou envie um pull request.

📝 Licença
Este projeto está sob a licença MIT — veja o arquivo LICENSE para mais detalhes.

Desenvolvido por Geisila Costa



