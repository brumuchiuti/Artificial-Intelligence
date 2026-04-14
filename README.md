<p align="right">
  <img src="http://meusite.mackenzie.br/rogerio/mackenzie_logo/UPM.2_horizontal_vermelho.jpg" width="10%" align="center"/>
</p>

# Inteligência Artificial - 1o Semestre 2026 (7G)

rogerio.oliveira@mackenzie.br 

<br>

#### Planos de Ensino e Aulas

* [Plano de Ensino](https://github.com/Rogerio-mack/IA_2026S1/blob/main/CC_7G_Plano_de_ensino_Inteligencia_Artificial_2026_1.pdf)
* [Plano de Aulas](https://github.com/Rogerio-mack/IA_2026S1/blob/main/CC_7G_Plano_de_aula_Inteligencia_Artificial_2026_1.pdf)

#### Datas Importantes

* **08.04** Avaliação A1 (11.04 data limite de notas) | [Notas e feedbacks](https://github.com/Rogerio-mack/IA_2026S1/raw/refs/heads/main/Notas_N1.xlsx) | Correções (*somente em sala*) [A1A](https://github.com/Rogerio-mack/work_private/blob/main/N1A.pdf) | [A1B](https://github.com/Rogerio-mack/work_private/blob/main/N1D.pdf)
* **20.05** Apresentação dos Projetos
* **27.05** Avaliação A2 (03.06 data limite de notas)
* **03.06** PSUB
* **10.062** PF

#### **Projeto: Simulação de Opinião Pública com LLMs**

Com base em uma pesquisa de opinião do [Cesop](https://www.cesop.unicamp.br/) (Centro de Estudos de Opinião Pública) desenvolver um modelo LLM para simulação das respostas dos questionários e comparar com os resultados da pesquisa. [Escolha aqui a pesquisa de opinião](https://drive.google.com/drive/folders/10Zv1waT-aTPFsYhZ6l1CSa3feDEBZ1R2?usp=sharing) (caso deseje empregar outra pesquisa, do [Cesop](https://www.cesop.unicamp.br/) ou outra, consulte o professor). 

0. **Grupo e tema**. Cada grupo (máximo 6 alunos) deve escolher uma pesquisa de opinião. Cada pesquisa poderá ter até 3 grupos no máximo, mas tratando questões diferentes. Ao menos duas questões/respostas devem ser simuladas - ao menos uma com mais de 2 alternativas de resposta. As questões precisam ser diferentes nos grupos que empregarem a mesma pesquisa. Faça o cadastro da pesquisa e questões do seu grupo [aqui](https://docs.google.com/spreadsheets/d/1Hbnt25jLJXbTVxFePT-uHq_v5cEPbXUDfWP-VTCKA0I/edit?usp=sharing) até 21.04.2026. 
1. **Requisitos mínimos**. Ter como ponto de partida o artigo *Simulating Public Opinion: Comparing Distributional and Individual-Level Predictions from LLMs and Random Forests*, disponível na [pasta](https://drive.google.com/drive/folders/10Zv1waT-aTPFsYhZ6l1CSa3feDEBZ1R2?usp=sharing). Avaliar acuracidade, distribuições das respostas e explicabilidade (importância relativa das variáveis preditoras). Simular ao menos 200 respondentes (10% dos dados) com repetições (3-5, cv). Incluir o maior número possível de características e respostas (sugestão: começe com um pequeno número respondentes, características e aumente gradualmente).     
3. **Ferramentas**. Empregue somente modelos e recursos abertos, sendo 100% executável e aberto (não empregue API Keys privadas). Preferencialmente, executar 100% em um notebook Colab. 
4. **GitHub**. Implementar um GitHub com o projeto.
5. **Entrega**. No formato de um artigo SBC, preferencialmente em Latex. Apresentação no YouTube (máximo 6min) com o link a ser incluído no GitHub. Entrega e apresentação do projeto no final do curso, com data a definir (eventualmente só a entrega, incluindo vídeo de apresentação). 
6. **Rubrica**. Modelo LLM, 3 pontos (quantidade de atributos e respostas, qualidade dos prompts e aderência das respostas); Análise e Comparação dos resultados, 3.5 pontos (métricas empregadas, repetições e/ou bootstrapping, gráficos comparativos, técnicas de explicabilidade); Artigo e Aspecto Geral do Trabalho, 3 pontos (Apresentação, fundamentação, justificativas, referências, apresentação dos resultados).
7. Extra: Esse projeto pode ser estendido adicionando-se a comparação com a simulação de respostas a partir de um modelo de aprendizado supervisionado. 

#### Sugestão de Roteiro de Apresentação (máx 6min)

| Slide | Conteúdo |
|-|-|
| 1 | Apresentação do Questionário empregado |
| 2 | Seleção dos dados para o modelos e Preparação dos Dados (alternativamente em um slide separado) |
| 3 | Modelo LLM empregado (características e justificativa da escolha) |
| 4 | Geração e execução dos prompts (+exemplos dos prompts gerados) |
| 5 | Métricas e resultados do modelo LLM |
| 6 | Conclusão |

* [Templates SBC para o artigo do Projeto](https://www.sbc.org.br/documentosinstitucionais/#publicacoes) 

* Exemplos de Projetos no GitHub: [Trabalho1](https://github.com/matteovar/Deteccao_de_image) | [Trabalho2](https://github.com/LeticiaMoraesG/Projeto_gatos/tree/main) | [Trabalho3](https://github.com/erikhsu08/projetoIA/tree/main)

#### Notas

* $N_1 = 0.7 A_1 + 0.3 \text{Atividades}$
> * $\text{Atividades} =   \text{Exercícios}$
* $N_2 = 0.7 A_2 + 0.3 \text{Atividades}$
> * $\text{Atividades} =   \text{Projeto}$
* $MF = 0.5 N_1 + 0.5 N_2$

#### Cursos Google 

* [Formulário de inscrição (até 11.03)](https://docs.google.com/forms/d/e/1FAIpQLSeUbSgnrRtp9ZasjI9ww1Fh1Pgd67VW8zVqupaJL7cBwd7bDQ/viewform?usp=header)

> * **Conclua até 07.04, Beginner: Introduction to Generative AI Learning Path** (+6h complementares)
> * **Conclua até 26.05, Google DeepMind: AI Research Foundations** (+20h complementares)

<br>

## Programação Semanal

**1** [**Introdução à Inteligência Artificial: conceito, história e paradigmas**](https://colab.research.google.com/github/Rogerio-mack/IA_2026S1/blob/main/IA_Introducao.ipynb) 

> * [Resumo de Tópicos ](https://github.com/Rogerio-mack/IA_2026S1/blob/main/IA01.pdf)

> * [MS AI For Beginners](https://github.com/microsoft/AI-For-Beginners) | [Introduction and History of AI](https://github.com/microsoft/AI-For-Beginners/blob/main/lessons/1-Intro/README.md)

> * Leitura da seção [Aprendizado de Máquina: Um Novo Paradigma](https://colab.research.google.com/github/Rogerio-mack/Machine-Learning-I/blob/main/ML1_introducao.ipynb).

> *Introdução à IA; Definição de IA; Teste de Turing, Quarto Chinês de Searle; IA Forte x IA Fraca; Abordagens Top Down e Bottom Up; Técnicas de IA (Classificação por Abordagem Técnica): IA Clássica x Aprendizado de Máquina x Deep Learning;* 

**2** [**Expert Systems, Rule‑Based Programming**](https://colab.research.google.com/github/Rogerio-mack/IA_2026S1/blob/main/Rule_Based_Programming.ipynb) 

> * [MS AI For Beginners](https://github.com/microsoft/AI-For-Beginners) | [Knowledge Representation and Expert Systems](https://github.com/microsoft/AI-For-Beginners/blob/main/lessons/2-Symbolic/README.md)

> *Sistemas Especialistas; Regras de Produção; Aplicações; Inferência direta (para frente) e reversa;*

**3** [**Algoritmos de Busca, Search Algorithms**](https://colab.research.google.com/github/Rogerio-mack/IA_2026S1/blob/main/Search_Algorithms.ipynb)

> *Algoritmos de Busca; DFS, BFS; Busca Informada e Heurísticas; Busca Gulosa, Dijkstra e A-Star; Aplicações*

**4** [**Algoritmos Genéticos**](https://colab.research.google.com/github/Rogerio-mack/IA_2026S1/blob/main/GeneticAlgorithms.ipynb)

> *Algoritmos genéticos; Fluxo dos algoritmos genéticos; representação das soluções por genes; funções de aptidão e seleção; crossover; mutação; tipos de problemas e aplicações*

**5** [**Aprendizado Supervisionado e Regressão Linear**](https://colab.research.google.com/github/Rogerio-mack/Machine-Learning-I/blob/main/ML2_Regressao.ipynb)

> * [Classificação (Regressão Logística)](https://colab.research.google.com/github/Rogerio-mack/Machine-Learning-I/blob/main/ML3_RegressaoLogistica.ipynb)
>>> - Veja aqui: Regressão Logística, Sobreajuste, Subajuste, Conjuntos de Treinamento e Teste
> * [Classificação: Knn](https://colab.research.google.com/github/Rogerio-mack/Machine-Learning-I/blob/main/ML4_Knn.ipynb)
>>> - Veja aqui: Knn, Matriz de Confusão, TP/TN/FP/FN, Acuracidade, Precisão, Recall e F1 
> * [Árvores de Decisão e Seleção de Atributos](https://colab.research.google.com/github/Rogerio-mack/Machine-Learning-I/blob/main/ML5_DecisionTrees.ipynb)
>>> - Veja aqui: Árvores de Decisão 

> * [**Resumo e Exercício: Aprendizado Supervisionado: Regressão e Classificação**](https://colab.research.google.com/github/Rogerio-mack/IA_2026S1/blob/main/Resumo_ML_supervisionado_scikit_learn.ipynb)
>>> - Veja aqui: Resumo; Aprendizado supervisionado; Tarefas de Classificação e Regressão; Uso de estimadores de scikit-learn;

> Aprendizado supervisionado; Tarefas de Classificação e Regressão; Uso de estimadores de scikit-learn; Regressão Linear; Correlação; Coeficiente de Determinação (R2); Acuracidade; Dilema Viés-Variância: sub e sobreajuste (overfitting); Conjuntos de Treinamento; Conjunto de Teste; Métricas de classificação: acuracidade, matriz de confusão, TP e TN

**6** [**Introdução aos Modelos Neurais I**](https://colab.research.google.com/github/Rogerio-mack/Deep-Learning-I/blob/main/T1.ipynb) 

**7** [**Introdução aos Modelos Neurais II**](https://colab.research.google.com/github/Rogerio-mack/Deep-Learning-I/blob/main/T2.ipynb) 

> *História; Neurônio perceptron; Funções de Ativação; XOR problem; Aprendizado e Algoritmo de Retropropagação; Parâmetros e Hiperparâmetros; Conjunto de Teste e de Validação; Redes MLP; MLPClassifier; Curva de Aprendizado.*

**8** [**Deep Learning Frameworks**](https://colab.research.google.com/github/Rogerio-mack/Deep-Learning-I/blob/main/T3.ipynb) | [**Keras Sequential Model**](https://colab.research.google.com/github/Rogerio-mack/Deep-Learning-I/blob/main/T4.ipynb) 



