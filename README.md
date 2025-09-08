# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="Assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%></a>
</p>

<br>


# Cap 1 - FarmTech na era da cloud computing #


## Grupo
João José Domingues Siva, William Xavier, Murílo Santana, William Ferreira


## 👨‍🎓 Integrantes:
- João José Domingues Siva
- William Xavier
- Murílo Santana
- William Ferreira



## 👩‍🏫 Professores:
### Tutor(a)
- [Nome do Tutor]
### Coordenador(a)
- [Nome do Coordenador]

---


## 📜 Descrição
Este projeto tem como objetivo prever o rendimento de diferentes culturas agrícolas utilizando algoritmos de aprendizado de máquina. O processo tradicional de estimativa de rendimento é manual e sujeito a erros. Com a solução proposta, buscamos automatizar e aumentar a precisão das previsões, auxiliando produtores e cooperativas.

O desenvolvimento seguiu as etapas principais de um projeto de Machine Learning:
- **Análise Exploratória:**
  - Carregamento e inspeção dos dados (arquivo `crop_yield.csv`).
  - Visualização das relações entre variáveis e identificação de tendências.
- **Pré-processamento:**
  - Remoção de duplicatas e outliers.
  - Transformação da coluna categórica 'Crop' em variáveis dummies.
  - Padronização dos dados numéricos.
- **Clusterização:**
  - Aplicação do DBSCAN para identificar agrupamentos e padrões de rendimento por cultura.
- **Modelagem Preditiva:**
  - Treinamento e avaliação de cinco algoritmos de regressão: Regressão Linear, Random Forest, SVR, Decision Tree e KNeighbors.
  - Utilização de GridSearchCV para comparação e escolha do melhor modelo.
  - Aplicação de PCA para redução de dimensionalidade.


## 📊 Resultados
- O modelo **Random Forest Regressor** apresentou o melhor desempenho, sendo robusto, preciso e capaz de capturar relações não lineares.
- Os demais modelos (Linear, SVR, Decision Tree, KNN) foram avaliados e comparados, mas tiveram desempenho inferior.
- O uso de clusterização e análise exploratória permitiu identificar padrões e tendências relevantes para cada cultura.


## 🏁 Conclusão
A abordagem baseada em Random Forest se mostrou a mais eficaz para prever o rendimento das safras, devido à sua robustez e capacidade de lidar com dados complexos. O projeto demonstra como técnicas de ciência de dados podem ser aplicadas para apoiar decisões no agronegócio, tornando o processo mais eficiente e confiável.

---



## 📁 Estrutura de Pastas

- <b>Assets/</b>: Imagens e recursos do projeto (ex: logo da FIAP).
- <b>Scripts/</b>: Contém o notebook principal e o arquivo de dados.
  - <b>crop_yield.csv</b>: Base de dados utilizada no projeto.
  - <b>JoaoJose_rm564111_pbl_fase4.ipynb</b>: Notebook principal com todo o desenvolvimento, análises e modelos.
- <b>README.md</b>: Guia e explicação geral sobre o projeto (este arquivo).


## 🔧 Como executar o código

**Pré-requisitos:**
- Python 3.x
- Bibliotecas: scikit-learn, pandas, numpy, matplotlib, seaborn (instale via `pip install -r requirements.txt` se disponível)

**Passos para execução:**
1. Clone este repositório.
2. Instale as dependências necessárias.
3. Execute o notebook `JoaoJose_rm564111_pbl_fase4.ipynb` para reproduzir as análises e resultados.

## 🗃 Histórico de lançamentos

* 1.0.0 - 09/09/2025
    * Versão final do projeto

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

> Projeto desenvolvido para fins acadêmicos, seguindo boas práticas de ciência de dados e aprendizado de máquina.

