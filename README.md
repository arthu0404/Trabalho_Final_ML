# Trabalho Final - Machine Learning - Equipe Windsurf  🏄 💨

No presente trabalho, nos propusemos a analisar dados a respeito da toxicidade de nanopartículas utilizando 6 modelos de aprendizado de máquina:

- Dummy Classifier
- $k-NN$
- Árvore de decisão
- Floresta aleatória
- Regressão logística
- SVC

Em todas as aplicações, utilizamos a mesma métrica como target: toxicidade.

# !["Badge Ilum"](https://img.shields.io/badge/Ilum%20-%20purple) !["Badge Satus"](https://img.shields.io/badge/Status%20-%20Em_Desenvolvimento%20-%20orange)

# 🎲  Fonte dos Dados 🎲 

Os datasets utilizados foram obtidos em: 

- HA, E.; HA, S. Structured Nanotoxicity Datasets with Physicochemical and Toxicological Attributes of Metal Oxide Nanoparticles. Zenodo, 12 maio 2025.
  Disponível em (https://zenodo.org/records/15385143).

- HA, M. Meta-analyzed datasets for toxicity classification of metal oxide nanoparticles. Zenodo, 16 fev. 2018.
  Disponível em (https://zenodo.org/records/15300193).

# ❓Por que escolhemos esses datasets? ❓

Na disciplina de Iniciação à Pesquisa I e Laboratório Avançado I, a turma 25 da Ilum tratou da síntese de nanopartículas. Uma das métricas mais importantes para decidir a aplicabilidade de um nanomaterial é corretamente conhecer sua toxicidade. É a fim de facilitar interpretações futuras que escolhemos treinar algoritmos de aprendizado de máquina com otimização de hiperparâmetros para prever se um nanomaterial é tóxico ou não-tóxico. 

# 🛠️ Ferramentas Utilizadas 🛠️

### 📚Bibliotecas e Módulos📚
- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org)
- [Scikit-learn](https://scikit-learn.org)
- [Optuna](https://optuna.org/)
- [Scipy](https://scipy.org/pt/)
- [Seaborn](https://seaborn.pydata.org/)

#### 🐍 Versão do Python 🐍
  Python 3.12.7

#  🔧 Como utilizar o repositório? 🔧 

1. Clone o repositório.
2. Tenha certeza de que os arquivos estão corretamente posicionados na pasta _datasets_.
3. Crie um ambiente virtual e o ative:
      ```bash
   python -m venv venv
   
   # Windows:
   venv\Scripts\activate
   
   # macOS/Linux:
   source venv/bin/activate
  4. Instale as bibliotecas necessárias acima listadas seguindo a sintaxe:
     ```bash
     pip install -r requirements.txt
  5. Execute o notebook _modelos_finais_.
     
# 💾 Resultados esperados 💾

Ao executar os passos anteriormente detalhados, um usuário deve receber como output esperado a matriz de confusão de cada um dos modelos, assim como o seguinte retorno de métricas de interesse: 

| Modelo               |   F1-Macro |
|----------------------|------------|
| Baseline             |     0.8681 |              
| K-NN                 |     0.9331 |            
| Árvore de Decisão    |     0.9414 |          
| Floresta Aleatória   |     0.9555 |        
| Regressão Logística  |     0.8544 |        
| SVC                  |     0.9166 |  

# 🌐Desenvolvedores🌐

[<img loading="lazy" src="https://avatars.githubusercontent.com/arthu0404" width=115><br><sub>🐵 Arthur Brandão do Nascimento 🐵</sub>](https://github.com/arthu0404)

Aluno do segundo semestre da Ilum - Escola de Ciência.

[<img loading="lazy" src="https://avatars.githubusercontent.com/Caio1833" width=115><br><sub>🐢 Caio Ávila Paulo 🐢</sub>](https://github.com/Caio1833)

Aluno do segundo semestre da Ilum - Escola de Ciência. 

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/88594280?v=4" width=115><br><sub>🐳Matheus Macedo do Nascimento🐳</sub>](https://github.com/matheusMNa)

Aluno do segundo semestre da Ilum - Escola de Ciência.



# **Referências**

CASSAR, Daniel Roberto. Classificação binária. [Jupyter Notebook], Ilum – Escola de Ciência, Campinas, 2025. 

CASSAR, Daniel Roberto. Otimização de hiperparâmetros com optuna. [Jupyter Notebook], Ilum – Escola de Ciência, Campinas, 2025.

CASSAR, Daniel Roberto. Validação cruzada e otimização de hiperparâmetros. [Jupyter Notebook], Ilum – Escola de Ciência, Campinas, 2025.

NUMPY DEVELOPERS. NumPy documentation. Disponível em: https://numpy.org/doc/
. Acesso em: 1 nov. 2025.

OPTUNA DEVELOPERS. Optuna documentation. Disponível em: https://optuna.org/
. Acesso em: 1 nov. 2025.

PANDAS DEVELOPMENT TEAM. pandas documentation. Disponível em: https://pandas.pydata.org/docs/
. Acesso em: 1 nov. 2025.

SCIKIT-LEARN DEVELOPERS. Scikit-learn documentation. Disponível em: https://scikit-learn.org/stable/
. Acesso em: 1 nov. 2025.

SCIPY DEVELOPERS. SciPy documentation. Disponível em: https://docs.scipy.org/doc/
. Acesso em: 1 nov. 2025.

WASKOM, Michael et al. Seaborn documentation. Disponível em: https://seaborn.pydata.org/
. Acesso em: 1 nov. 2025.





