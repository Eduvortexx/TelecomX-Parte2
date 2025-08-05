TelecomX Churn Prediction
📊 Sobre o Projeto
Este projeto tem como objetivo analisar o comportamento dos clientes da TelecomX para identificar os principais fatores que influenciam a evasão (churn) e construir modelos preditivos capazes de antecipar quais clientes têm maior probabilidade de cancelar os serviços. Através dessa análise, buscamos fornecer insights e estratégias para melhorar a retenção de clientes.

🗂️ Estrutura do Projeto
TelecomX_data_tratados.csv — Base de dados tratada com informações dos clientes e seus históricos.

data_preprocessing.ipynb — Notebook com a preparação dos dados: limpeza, codificação e tratamento de valores faltantes.

eda_visualizations.ipynb — Análise exploratória e visualização dos dados para identificar padrões e relações.

model_training.ipynb — Construção e avaliação dos modelos de machine learning (Regressão Logística, Random Forest).

feature_importance_analysis.ipynb — Análise da importância das variáveis e interpretação dos resultados.

README.md — Documentação geral do projeto.

🧰 Tecnologias e Bibliotecas Utilizadas
Python 3.8+

Pandas

NumPy

Scikit-learn

Seaborn

Matplotlib

🚀 Como Executar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seuusuario/TelecomX-Churn-Prediction.git
cd TelecomX-Churn-Prediction
Instale as dependências:

bash
Copiar
Editar
pip install -r requirements.txt
Execute os notebooks na ordem:

data_preprocessing.ipynb

eda_visualizations.ipynb

model_training.ipynb

feature_importance_analysis.ipynb

📈 Resultados Principais
Contratos mensais apresentam maior risco de evasão.

Maior tempo de permanência e total gasto reduzem a chance de cancelamento.

Serviços complementares (ex: TV, streaming) ajudam a reter clientes.

Modelos Random Forest e Regressão Logística apresentam boa performance, com Random Forest ligeiramente superior na captura dos cancelamentos.

💡 Próximos Passos
Testar técnicas de balanceamento como SMOTE para melhorar o desempenho em classes desbalanceadas.

Explorar modelos adicionais, como XGBoost e redes neurais.

Desenvolver um sistema de alerta para identificar clientes com maior risco de evasão em tempo real.

Integrar a solução em um dashboard para acompanhamento contínuo.

🤝 Contribuição
Contribuições são bem-vindas! Por favor, abra uma issue para discutir sugestões ou envie um pull request.

📄 Licença
Este projeto está licenciado sob a MIT License.
