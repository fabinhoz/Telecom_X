
# Telecom X: Análise de Evasão de Clientes (Churn)

## 📋 Sobre o Projeto

A **Telecom X** enfrenta um desafio crítico: o alto índice de cancelamento de clientes. Como Assistente de Análise de Dados, integrei a equipe de Data Science para identificar os fatores que impulsionam essa evasão.

Este projeto foca na etapa de **ETL (Extração, Transformação e Carga)** e **EDA (Análise Exploratória de Dados)**. O objetivo é transformar dados brutos em insights estratégicos para que o time possa avançar na criação de modelos preditivos e políticas de retenção eficientes.

---

## 🛠️ Ferramentas e Tecnologias

* **Linguagem:** Python
* **Manipulação de Dados:** Pandas, Numpy, JSON
* **Visualização Estática:** Matplotlib, Seaborn
* **Visualização Interativa:** Plotly Express
* **Ambiente de Desenvolvimento:** Google Colab

---

## 📊 Principais Descobertas (Insights)

A análise exploratória revelou padrões determinantes para o comportamento de Churn:

### 1. Perfil Financeiro e de Pagamento

* **Risco no Pagamento:** O método **Cheque Eletrônico** possui a maior taxa de evasão (**~42,9%**), sugerindo fricção no processo de pagamento.
* **Ticket Médio:** Existe uma correlação positiva entre mensalidades mais altas e o cancelamento.

### 2. Comportamento Contratual

* **Fidelização:** Clientes em contratos **mês a mês** são os que mais saem. Contratos de 1 ou 2 anos apresentam churn drasticamente menor.
* **Tempo de Casa (Tenure):** O risco de evasão é máximo nos primeiros meses de contrato, conforme demonstrado pelo gráfico de Densidade de Kernel (KDE).

### 3. Serviços e Conectividade

* **Fibra Óptica:** Apesar de ser uma tecnologia superior, clientes de fibra óptica apresentam churn mais elevado, o que pode indicar problemas de preço ou instabilidade na rede.
* **Serviços Adicionais:** A ausência de suporte técnico e segurança online correlaciona-se com maior evasão.

### 4. Fatores Demográficos e Sociais

* **Estrutura Familiar:** Clientes sem parceiros ou dependentes têm maior probabilidade de cancelar (**~32%** vs **~16%** de quem possui dependentes).
* **Gênero:** Não se mostrou um fator determinante para o churn na Telecom X.

---

## 🚀 Próximos Passos Recomendados

Para reduzir o Churn, as seguintes ações são sugeridas:

1. **Migração Contratual:** Incentivar a transição de planos mensais para anuais com descontos progressivos.
2. **Campanhas de Retenção Early-Stage:** Focar em novos clientes (baixas cobranças totais e alta mensalidade) com programas de boas-vindas e suporte proativo.
3. **Análise de Pagamento:** Investigar e possivelmente descontinuar ou automatizar o processo de "Cheque Eletrônico" para reduzir falhas de pagamento.
4. **Pacotes de Valor:** Agrupar serviços de suporte técnico e segurança online para clientes de fibra óptica.

---

## 📁 Como Executar o Projeto

1. Clone este repositório:
```bash
git clone https://github.com/fabinhoz/Telecom_X.git

```


2. Instale as dependências necessárias:
```bash
pip install pandas seaborn plotly matplotlib requests

```


3. Abra o arquivo `.ipynb` no **Google Colab** ou em seu **Jupyter Notebook** local.

---

## 👤 Autor

**Fabio Zinetti**

* **GitHub:** [github.com/fabinhoz](https://github.com/fabinhoz/)
* **Projeto:** Desenvolvido como parte do **Challenge de Data Science – Alura**.

---

*Este projeto foi realizado com fins de estudo e prática de análise de dados aplicada a problemas de negócio reais.*
