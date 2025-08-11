# 📊 Análise de Evasão de Clientes – TelecomX

<h2> 📋 Sobre o Projeto </h2>
Este projeto foi desenvolvido como parte da formação em Data Science do programa **Oracle Next Education (ONE)** em parceria com a **Alura**.  
O objetivo é analisar os dados de uma empresa fictícia do setor de telecomunicações para entender os fatores que mais influenciam a evasão de clientes (**Churn**) e propor estratégias de retenção com base nos resultados.

A análise utiliza bibliotecas do ecossistema Python para ciência de dados, incluindo **Pandas**, **Matplotlib**, **Seaborn** e modelos de Machine Learning como **KNN** e **Árvore de Decisão**.

---

<h2> 🛠️ Ferramentas Utilizadas </h2>

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

<h2> 📂 Estrutura da Base de Dados </h2>

O dataset contém informações sobre clientes, incluindo:
- Dados demográficos
- Tipo de contrato e serviços contratados
- Valores cobrados e totais pagos
- Informações sobre cancelamento (Churn)

---

<h2> 🧹 Preparação dos Dados </h2>

1. **Codificação de variáveis categóricas**
2. **Balanceamento das classes (Churn)**
3. **Separação em variáveis preditoras (X) e alvo (y)**

---

<h2> 📊 Análise Exploratória de Dados </h2>

A análise buscou entender como diferentes variáveis influenciam a evasão, com destaque para:
- Tipo de contrato
- Tempo de permanência
- Valor mensal pago
- Quantidade de serviços contratados
- Método de pagamento

<h3> Distribuição de Evasão </h3>

![Imagem](images/distribuicao_evasao.png)

<h3> Correlação entre Variáveis Numéricas </h3>

![Imagem](images/matriz_correlacao.png)

<h3> Evasão por Tipo de Contrato </h3>

![Imagem](images/evasao_contrato.png)

---

<h2> 🤖 Modelos de Machine Learning </h2>

Foram utilizados e comparados dois modelos:
- **KNN (K-Nearest Neighbors)**
- **Árvore de Decisão**

Ambos foram treinados com dados balanceados para melhorar a capacidade preditiva.

<h3> Métricas Avaliadas </h3>
- Acurácia
- Precisão
- Recall
- F1-Score
- Matriz de Confusão

![Imagem](images/comparacao_modelos.png)

---

<h2> 📈 Comparação de Desempenho </h2>

- O **KNN** apresentou [descrever desempenho com base nos seus resultados].
- A **Árvore de Decisão** apresentou [descrever desempenho com base nos seus resultados].
- Com base nas métricas, o modelo **[vencedor]** apresentou melhor equilíbrio entre precisão e recall.

---

<h2> 🔍 Principais Fatores que Influenciam a Evasão </h2>

Com base na análise e importância das variáveis:
1. Tipo de contrato (mensal tem maior evasão)
2. Tempo de permanência
3. Valor mensal pago
4. Método de pagamento
5. Quantidade de serviços adicionais

---

<h2> 💡 Estratégias de Retenção </h2>

- **Oferecer descontos ou benefícios** para clientes com contrato mensal migrarem para planos anuais.
- **Criar programas de fidelidade** para aumentar o tempo de permanência.
- **Oferecer pacotes personalizados** com base nos serviços mais usados.
- **Facilitar o método de pagamento**, oferecendo mais opções e descontos para débito automático.
- **Campanhas de reengajamento** para clientes que indicam insatisfação.

---

<h2> 📌 Conclusão </h2>

O projeto mostrou que a evasão de clientes está fortemente relacionada ao tipo de contrato e ao valor mensal pago.  
A aplicação de modelos preditivos pode ajudar a identificar clientes com maior probabilidade de cancelar, permitindo ações proativas para reter a base.

---
