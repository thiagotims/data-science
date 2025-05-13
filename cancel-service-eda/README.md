# 📊 Análise de Cancelamento de Serviço

Este projeto foi desenvolvido como uma análise exploratória de dados (EDA) para entender os motivos do cancelamento de serviços em uma empresa com mais de 800 mil clientes. A empresa busca insights para reduzir a evasão de clientes e melhorar sua retenção.

O presente projeto foi inspirado em uma Masterclass de Análise de Dados realizada pela escola de programação Hashtag. A solução de código proposta aqui é diferente da original. 

Base de dados e arquivos foram  extraídos de: https://drive.google.com/drive/folders/1uDesZePdkhiraJmiyeZ-w5tfc8XsNYFZ?usp=drive_link 

## 🔍 Objetivo

Identificar os principais fatores que levam os clientes a cancelar o serviço e gerar insights que possam guiar estratégias de retenção.

## 📁 Base de Dados

A base utilizada é uma amostra da original (por questões de desempenho) e está disponível neste [link do Google Drive](https://drive.google.com/drive/folders/1uDesZePdkhiraJmiyeZ-w5tfc8XsNYFZ?usp=drive_link).

## 🧰 Tecnologias Utilizadas

* Python 3.10+
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## 📈 Análises Realizadas

* Limpeza e pré-processamento dos dados
* Análise da taxa de cancelamento
* Avaliação do impacto das variáveis numéricas (idade, dias de atraso, ligações ao call center, etc.)
* Avaliação de variáveis categóricas (sexo, tipo de assinatura, duração do contrato)
* Correlação entre variáveis e o cancelamento
* Geração de gráficos estatísticos e heatmaps

## 💡 Principais Insights

* **Ligações ao Call Center**: variável com maior correlação positiva com cancelamento.
* **Total Gasto**: variável mais associada à retenção de clientes.
* **Contrato Mensal**: risco extremamente alto de cancelamento (100% de evasão).
* **Mulheres**: maior propensão ao cancelamento comparado aos homens.
* **Atrasos no pagamento**: outro forte indicativo de cancelamento iminente.

Esses fatores podem ser utilizados futuramente para a criação de modelos preditivos ou políticas de retenção segmentadas.

## 📂 Estrutura do Projeto

```
cancel_service.ipynb     # Notebook com a análise completa
cancelamentos_sample.csv # Dataset de entrada
analise_*.png            # Gráficos gerados para cada variável
```

## 🧠 Próximos Passos (opcional)

* Criar modelo preditivo de churn com machine learning
* Implementar dashboard interativo (Streamlit ou Dash)
* Análise por cohort ou segmentações temporais

## 📃 Licença

Este projeto está sob a licença [MIT](LICENSE).

## 📫 Contato
Para mais informações, entre em contato através de thiagotimdev@gmail.com.


