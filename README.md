<h1 align='center'>
  🧬 Genes & Graus: Uma Jornada do Trio Epistasia pelos Gliomas</a><br>
  Trio Epistasia: "INIBINDO ESTUPIDEZ"
  </h1>
<div align="center">
  <img src="brasao.png" width="40%">
</div>
<h2>Projeto Final da Disciplina de Aprendizado de Máquina</h2> 
Instituição de ensino vinculada aos desenvolvedores e colaboradores do Projeto: Ilum Escola de Ciência - CNPEM (Centro Nacional de Pesquisa em Energia e Materiais).

<p align="center">

  <img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>  ![Made withPython](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)

</p>

<p align="justify"> Este projeto é uma iniciativa do Trio Epistasisa, voltada para a aplicação de aprendizado de máquina na análise de tumores cerebrais do tipo glioma, com foco nos subtipos LGG (Low-Grade Glioma) e GBM (Glioblastoma Multiforme). Nosso objetivo é investigar padrões genéticos e clínicos que diferenciam os graus dos gliomas, utilizando modelos de machine learning para classificação, visualização e interpretação dos dados. A proposta combina ciência de dados com uma narrativa envolvente, transformando o processo de análise em uma jornada investigativa. </p>

### 🌟 Por que "Genes & Graus"?
Porque cada gene conta uma história, e cada grau revela um desafio. Nesta jornada, o Trio Epistasisa se aventura pelo universo dos gliomas, buscando entender como a genética e os dados clínicos se entrelaçam para revelar os segredos do cérebro.


<h2>Desenvolvedores do Projeto</a></h2>
<ul>
  <li>Bruna Guedes Pereira (https://github.com/Bruna-guedes09): Pré-processamento, redação da Introdução, Revisão Teórica e Desenvolvimento;</li>
  <li>Laura Medeiros Dal Ponte (https://github.com/medeirosdal78): Escolha do dataset, instanciação dos modelos, redação dos Resultados e Discussões/Conclusão e <i>design</i> do Brasão;</li>
  <li>Mariana Melo Pereira (https://github.com/marip864): Investigação dos conjuntos de hiperparâmetros com Optuna, comparação dos algoritmos usando validação cruzada, uso de ferramentas explicativas e redação da Metodologia.</li>
</ul>

<h2>Professor Responsável:</h2> Prof. Dr. Daniel Roberto Cassar (https://github.com/drcassar)

<h2>Uma descrição do projeto um pouco mais aprofundada...</a></h2>
<p align="justify">Nos últimos anos, a aplicação de técnicas de Ciência de Dados e Aprendizado de Máquina (Machine Learning, ML) tem se consolidado como uma das abordagens mais promissoras na área biomédica [25, 26]. O grande volume de dados clínicos, genéticos e de imagem atualmente disponível possibilita a construção de modelos computacionais capazes de identificar padrões complexos e apoiar o diagnóstico e a tomada de decisão médica com maior precisão e rapidez. Essas abordagens computacionais têm se mostrado essenciais para identificar padrões complexos, auxiliar no diagnóstico precoce e otimizar estratégias terapêuticas, contribuindo para o desenvolvimento da medicina de precisão [25, 26].</p>

<p align="justify">No contexto dos tumores cerebrais, os gliomas representam um dos principais desafios clínicos e científicos. Eles são neoplasias originadas das células gliais e podem apresentar diferentes graus de agressividade, variando desde formas de baixo grau, com evolução mais lenta, até glioblastomas, altamente malignos e de difícil tratamento [23]. São classificados em diferentes graus de malignidade, variando desde os gliomas de baixo grau (Low Grade Glioma – LGG), de crescimento mais lento, até o glioblastoma multiforme (GBM), o tipo mais agressivo e de pior prognóstico [24]. A distinção precisa entre esses subtipos é essencial para o planejamento do tratamento e prognóstico clínico, mas nem sempre é uma tarefa simples, uma vez que envolve múltiplos fatores clínicos, moleculares e genéticos.</p>

<p align="justify">Diante desse cenário, o presente trabalho teve como objetivo comparar o desempenho de diferentes algoritmos de aprendizado supervisionado – RandomForestClassifier, XGBoostClassifier, SupportVectorClassification, Bernoulli NaiveBayese e ExtraTreesClassifier – na previsão do tipo de glioma (LGG e GBM), utilizando o conjunto de dados “Glioma Grading Clinical and Mutation Features”. Todas as variáveis clínicas e genéticas disponíveis foram consideradas na modelagem, a fim de explorar o potencial preditivo desses dados e avaliar o desempenho de algoritmos de classificação na discriminação entre os dois tipos de glioma.</p>

### 🧠 Técnicas Utilizadas
- Pré-processamento e normalização
- Modelos supervisionados (RandomForestClassifier, GradientBoostClassifier, SupportVectorClassifier, Bernoulli NaiveBayes e ExtraTreesClassifier)
- Avaliação com métricas como recall, acurácia e F1-score
- Interpretação de variáveis com SHAP e LIME

## 📁 Organização do Repositório
- `ProjetoFinal_SHAPLIME`: Caderno Jupyter com análises exploratórias, pré-processamento e modelagem.
- `TCGA_GBM_LGG_Mutations_all.csv`: Conjunto de dados originais.
- `TCGA_InfoWithGrade.csv`: Conjunto de dados utilizados no projeto (com dados pré-processados).
- `brasao.png`: Brasão da Equipe
- `imagem_val_cruzada.webp`: Imagem explicativa sobre Validação Cruzada importada para o Jupyter Notebook

<h2>Como posso rodar o Projeto na minha máquina?</h2>

- Passo 1: clonar o repositório ou baixar arquivo zip
- Passo 2: rodar comando "Restart the kernel and run all cells" no arquivo `ProjetoFinal_SHAPLIME.ipynb`

<h2>Aviso de licença</h2>
Todos são livres para utilizar e modificar os códigos deste repositório, mas desde que sejam dados os devidos créditos.

<h2>Referências</h2>
[1] TASCI, E., CAMPHAUSEN, K., KRAUZE, A., & ZHUGE, Y. (2022). Glioma Grading Clinical and Mutation Features [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5R62J.

[2] SCIKIT-LEARN. StandardScaler. Disponível em: https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html.

[3] UCI Machine Learning Repository. Disponível em: https://archive.ics.uci.edu/dataset/759/glioma+grading+clinical+and+mutation+features+dataset.

[4] SHAFI, A. Classificação de floresta aleatória com o Scikit-Learn. Disponível em: https://www.datacamp.com/pt/tutorial/random-forests-classifier-python. Acesso em: 30 out. 2025

[5] BEX TUYCHIEV. Um guia para o algoritmo Gradient Boosting. Disponível em: https://www.datacamp.com/pt/tutorial/guide-to-the-gradient-boosting-algorithm. Acesso em: 30 out. 2025.

[6] AWAN, A. A. Uma introdução aos valores SHAP e à interpretabilidade do aprendizado de máquina. Disponível em: https://www.datacamp.com/pt/tutorial/introduction-to-shap-values-machine-learning-interpretability. Acesso em: 31 out. 2025.

[7] ERICK FREIRE DEV. O que é uma Instância em Java ? - Erick Freire. Disponível em: https://www.youtube.com/watch?v=_ye5oGvj-9A. Acesso em: 3 nov. 2025.

[8] PAUL, S. Hyperparameter Optimization & Tuning for Machine Learning (ML). Disponível em: https://www.datacamp.com/tutorial/parameter-optimization-machine-learning-models.

[9] BUNMI AKINREMI. Optuna for Deep Reinforcement Learning in Python. Disponível em: https://www.datacamp.com/tutorial/optuna.

[10] Entenda o que é Variância e Viés em Machine Learning. Disponível em: https://didatica.tech/conceitos-de-variancia-e-de-vies/. Acesso em: 3 nov. 2025.

[11] Entenda o que é Underfitting e Overfitting (Machine Learning). Disponível em: https://didatica.tech/underfitting-e-overfitting/.

[12] SAVIETTO, J. V. Machine Learning: Métricas, Validação Cruzada, Bias e Variância. Disponível em: https://medium.com/@jvsavietto6/machine-learning-m%C3%A9tricas-valida%C3%A7%C3%A3o-cruzada-bias-e-vari%C3%A2ncia-380513d97c95.

[13] Entenda o que são Dados de Treino e Teste (Machine Learning). Disponível em: https://didatica.tech/dados-de-treino-e-teste/.

[14] LUNDBERG, S.; LEE, S.-I. A Unified Approach to Interpreting Model Predictions. [s.l: s.n.]. Disponível em: https://proceedings.neurips.cc/paper_files/paper/2017/file/8a20a8621978632d76c43dfd28b67767-Paper.pdf.

[15] SALIH, A. M. et al. A Perspective on Explainable Artificial Intelligence Methods: SHAP and LIME. Advanced Intelligent Systems, v. 7, n. 1, 27 jun. 2024.

[16] VIMBI, V.; SHAFFI, N.; MAHMUD, M. Interpreting artificial intelligence models: a systematic review on the application of LIME and SHAP in Alzheimer’s disease detection. Brain informatics, v. 11, n. 1, 5 abr. 2024.

[17] NATIONAL CANCER INSTITUTE. The Cancer Genome Atlas Program (TCGA) - NCI. Disponível em: https://www.cancer.gov/ccg/research/genome-sequencing/tcga.

[18] VERHAAK, R. G. W. et al. Integrated Genomic Analysis Identifies Clinically Relevant Subtypes of Glioblastoma Characterized by Abnormalities in PDGFRA, IDH1, EGFR, and NF1. Cancer Cell, v. 17, n. 1, p. 98–110, jan. 2010.

‌[19] CANCER GENOME ATLAS RESEARCH NETWORK. Comprehensive, Integrative Genomic Analysis of Diffuse Lower-Grade Gliomas. New England Journal of Medicine, v. 372, n. 26, p. 2481–2498, 25 jun. 2015.

‌[20] PARSONS, D. W. et al. An Integrated Genomic Analysis of Human Glioblastoma Multiforme. Science, v. 321, n. 5897, p. 1807–1812, 26 set. 2008.

‌[21] LOUIS, D. N. et al. The 2016 World Health Organization Classification of Tumors of the Central Nervous System: a Summary. Acta Neuropathologica, v. 131, n. 6, p. 803–820, 9 maio 2016.

[22] IBM. Pipeline de aprendizado de máquina. Disponível em: https://www.ibm.com/br-pt/think/topics/machine-learning-pipeline. Acesso em: 3 nov. 2025.

‌[23] DIAZ, M.; PAN, P. C. Management of Low-Grade Gliomas. The Cancer Journal, v. 31, n. 1, 1 jan. 2025.

[24] ABIKENARI, M. et al. Revisiting glioblastoma classification through an immunological lens: A narrative review. Glioma, v. 7, n. 2, p. 3–9, abr. 2024.

[25] Baldi P. Deep Learning in Biomedical Data Science. Annu Rev Biomed Data Sci. 2018;1:181-205

[26] Manepalli S, Varghese J, Madslhusdhan A, Umamahesh G, Penubaka KK. AI and ML in Biomedical Research: Unlocking Precision Medicine and Accelerating Discoveries. J Neonatal Surg. 2025;14:2940.
