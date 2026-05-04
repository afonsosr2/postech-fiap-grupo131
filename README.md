# 📊 Tech Challenge – Fase 1  
## Modelagem Preditiva de NPS em Contexto de E-commerce

> Projeto desenvolvido como parte do Tech Challenge da Pós Tech FIAP – IA Scientist.

---

## 🎯 Objetivo do Projeto

O presente projeto tem como objetivo central analisar e modelar os determinantes da satisfação do cliente em um ambiente de e-commerce, utilizando o **Net Promoter Score (NPS)** como variável de interesse.

Busca-se, de forma estruturada:

- Investigar os fatores operacionais que influenciam a percepção do cliente;
- Compreender a variabilidade do NPS mesmo diante de experiências aparentemente semelhantes;
- Identificar padrões latentes nos dados que expliquem comportamentos de promotores, neutros e detratores;
- Avaliar a viabilidade de modelos preditivos para antecipação da satisfação do cliente.

A proposta está alinhada à perspectiva de *data-driven decision making*, na qual dados históricos são utilizados para orientar estratégias de melhoria contínua da experiência do consumidor.

---

## 🗂️ Descrição da Base de Dados

A base de dados analisada é composta por registros operacionais de uma empresa de e-commerce, contemplando múltiplas dimensões da jornada do cliente:

- **Dados transacionais**: informações sobre pedidos realizados;
- **Dados logísticos**: prazos de entrega, atrasos e status de envio;
- **Dados de atendimento**: interações com suporte e resolução de problemas;
- **Dados de satisfação**: avaliação final do cliente por meio do NPS.

Do ponto de vista analítico, trata-se de um dataset com características típicas de problemas reais de Ciência de Dados:

- Presença de variáveis numéricas e categóricas;
- Relações não lineares entre variáveis;
- Variabilidade comportamental dos clientes.

Essas características demandam uma abordagem robusta de preparação e exploração dos dados.

---

## ⚙️ Metodologia Utilizada

A condução do projeto seguiu um pipeline estruturado de Ciência de Dados, inspirado em boas práticas como o modelo CRISP-DM, organizado nas seguintes etapas:

### 1. Compreensão do Problema

Inicialmente, foi realizada a definição do problema sob a ótica de negócio, com foco na identificação dos fatores que impactam a satisfação do cliente e sua mensuração via NPS (**variável alvo**).

---

### 2. Análise Exploratória de Dados (EDA)

Nesta etapa, foram aplicadas técnicas de estatística descritiva e visualização de dados para:

- Compreender a distribuição das variáveis;
- Identificar padrões, tendências e outliers;
- Avaliar o comportamento da variável alvo (NPS);
- Explorar possíveis relações entre variáveis explicativas e a satisfação do cliente.

A EDA foi fundamental para orientar as decisões subsequentes de modelagem.

---

### 3. Pré-processamento e Tratamento de Dados

Foram realizadas atividades de preparação dos dados, incluindo:

- Codificação de variáveis categóricas;
- Seleção e organização das variáveis relevantes.

Essa etapa foi essencial para garantir a qualidade e a consistência dos dados utilizados na modelagem.

---

### 4. Análise de Relações e Seleção de Variáveis

Foram investigadas correlações e associações entre variáveis, com o objetivo de:

- Identificar os principais drivers do NPS;
- Analisar medidas de tendência central (Estatística Descritiva);
- Selecionar atributos com maior poder explicativo;
- Dimensionar o impacto no NPS.

---

### 5. Modelagem Preditiva

Foram aplicados modelos de aprendizado de máquina com o intuito de prever o NPS a partir das variáveis operacionais.

O processo envolveu:

- Separação entre conjuntos de treino e teste;
- Treinamento do modelo;
- Avaliação de desempenho por métricas apropriadas;
- Interpretação dos resultados.

A modelagem permitiu avaliar a capacidade de generalização e o potencial preditivo dos dados disponíveis.

---

### 6. Interpretação e Geração de Insights

Os resultados obtidos foram analisados sob a perspectiva de negócio, possibilitando:

- Identificação de fatores críticos para a satisfação do cliente;
- Proposição de melhorias operacionais;
- Apoio à tomada de decisão baseada em evidências.

---

## ▶️ Como Reproduzir os Resultados

### 1. Clonagem do Repositório

```bash
git clone https://github.com/afonsosr2/postech-fiap-grupo131.git
cd postech-fiap-grupo131

3. Execução do Notebook

🔹 Ambiente recomendado: Google Colab

Acessar o notebook diretamente pelo repositório;
Executar as células sequencialmente em ambiente cloud.

🔹 Execução local

Instalar as dependências:

pip install pandas numpy matplotlib seaborn scikit-learn

Iniciar o ambiente Jupyter:

jupyter notebook

Abrir o arquivo:
Tech_Challenge_Final.ipynb

📈 Resultados e Contribuições

A análise permitiu:

* Identificar variáveis com maior impacto sobre o NPS;
* Evidenciar a influência de fatores logísticos e de atendimento na percepção do cliente;
* Demonstrar o potencial de modelos preditivos na antecipação da satisfação;
* Gerar insights aplicáveis à melhoria da experiência do consumidor.

🧠 Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Google Colab

📌 Considerações Finais

O projeto evidencia a importância da integração entre análise exploratória, modelagem estatística e interpretação de resultados no contexto da Ciência de Dados aplicada.
Mais do que prever o NPS, a abordagem adotada permite compreender os mecanismos subjacentes à experiência do cliente, contribuindo para uma atuação estratégica orientada por dados.
