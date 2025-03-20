# Análise de Dados e Machine Learning: Perfil de Estudantes e Sucesso Profissional

## 1. Descrição do Projeto
Este projeto tem como objetivo identificar perfis distintos de estudantes e profissionais a partir de um conjunto de dados que abrange características acadêmicas e indicadores de sucesso na carreira. Através de técnicas de análise exploratória, pré-processamento de dados e algoritmos de machine learning com foco na clusterização via K-Means, o estudo busca revelar padrões e insights que possam subsidiar estratégias educacionais personalizadas e ações de melhoria de desempenho.

### **Escopo e Objetivos:**
- Realizar análise exploratória e visualização de dados para compreender a distribuição e correlação entre variáveis.
- Aplicar técnicas de limpeza, transformação e padronização dos dados.
- Implementar o algoritmo K-Means para segmentar os estudantes em clusters com base em indicadores como notas, pontuações em exames (SAT), desempenho universitário, ofertas de emprego, salário inicial e satisfação na carreira.
- Interpretar os resultados dos clusters e discutir implicações para estratégias pedagógicas e de desenvolvimento profissional.

### **Significância:**
Este estudo contribui para a área de data analytics e machine learning ao demonstrar como a combinação de técnicas estatísticas e algoritmos de clusterização pode ser aplicada para identificar perfis em contextos educacionais e profissionais. Os insights obtidos podem auxiliar instituições educacionais e empresas na tomada de decisões estratégicas para a melhoria do desempenho e satisfação dos alunos e colaboradores.

## 2. Instruções de Instalação
### **Pré-requisitos**
- **Linguagem:** Python 3.x
- **Ambiente:** Google Colab (ou qualquer ambiente Jupyter Notebook)
- **Bibliotecas:** 
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - matplotlib.cm (para coloração dos gráficos)

### **Passos para Configuração do Ambiente**
1. **Clone ou faça o upload do notebook:**
   - Se estiver usando o Google Colab, basta fazer o upload do arquivo `.ipynb`.
2. **Instale as bibliotecas necessárias:**  
   Se necessario execute o seguinte comando em uma célula do notebook:
   ```python
   !pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. **Execute o notebook em sequência:**  
   Garanta que todas as células sejam executadas na ordem correta para reproduzir os passos de carregamento, pré-processamento, análise e clusterização dos dados.

## 3. Guia de Uso
### **Como Executar o Projeto**
- Abra o notebook no Google Colab.
- Execute as células sequencialmente para:
  - Carregar e visualizar o dataset (ex.: `education_career_success.csv`).
  - Realizar análise exploratória com gráficos (histogramas, boxplots e heatmaps de correlação).
  - Pré-processar os dados (remoção de colunas irrelevantes, tratamento de valores ausentes, codificação de variáveis categóricas e padronização).
  - Determinar o número ideal de clusters utilizando o método do cotovelo e análise do coeficiente de silhueta.
  - Aplicar o algoritmo K-Means e visualizar os clusters obtidos.

### **Exemplos de Entrada e Saída**
- **Entrada:** Dataset com variáveis como idade, GPA do ensino médio, pontuação SAT, GPA universitário, ofertas de emprego, salário inicial, satisfação com a carreira, entre outros.
- **Saída Esperada:**  
  - Gráficos demonstrando a distribuição e correlação entre variáveis.
  - Plot de silhueta e gráfico do método do cotovelo para definir o número de clusters.
  - Tabela de clusters com os centróides (valores médios revertidos para a escala original) e análise descritiva de cada cluster.

## 5. Fontes de Dados
- **Dataset Principal:** [Education and Career Success](https://www.kaggle.com/adilshamim8/education-and-career-success)

## 6. Metodologia
- **Pré-processamento:** Limpeza de dados, normalização e codificação.
- **Modelo:** Algoritmo K-Means para clusterização.
- **Métricas:** Silhouette Score e WCSS (Método do Cotovelo).

## 7. Resultados e Conclusão
- .
- .