# An empirical study on bug severity estimation using source code metrics and static analysis

* Ehsan Mashhadi, Shaiful Chowdhury, Somayeh Modaberi, Hadi Hemmati, Gias Uddin, An empirical study on bug severity estimation using source code metrics and static analysis, Journal of Systems and Software, Volume 217, 2024, 112179, ISSN 0164-1212, doi: [10.1016/j.jss.2024.112179](https://doi.org/10.1016/j.jss.2024.112179)

# Fichamento de Conteúdo

O estudo tem enfoque na manutenção de software, especificamente na detecção e previsão de bugs, com um foco particular na severidade dos bugs e em como métricas de código e ferramentas de análise estática podem ser utilizadas para prever a ocorrência e a gravidade desses bugs. O artigo busca responder às seguintes questões de pesquisa: As métricas de código-fonte são bons indicadores de bugs e de sua severidade?; Qual é a capacidade das ferramentas de análise estática em encontrar bugs e prever sua severidade?; Quais são as características dos bugs com diferentes níveis de severidade?
Para responder a essas questões, os autores utilizaram dois conjuntos de dados amplamente reconhecidos na área de engenharia de software: Defects4J e Bugs.jar, que contêm bugs reais de projetos Java de código aberto. Foram analisados 19 projetos, totalizando 1668 bugs (3358 métodos bugados). Além disso, foram estudados 140 bugs selecionados aleatoriamente para uma análise qualitativa, com o objetivo de entender quando e por que as métricas de código e as ferramentas de análise estática falham em distinguir a severidade dos bugs.
As métricas de código utilizadas no estudo incluem Linhas de Código, Complexidade de McCabe, Complexidade de McClure, Profundidade de Blocos Aninhados, Indentação Proxy, FanOut, Legibilidade, Dificuldade e Esforço de Halstead, e Índice de Manutenabilidade. As ferramentas de análise estática selecionadas foram SpotBugs e Infer, ambas amplamente utilizadas em pesquisas e na prática.
Em conclusão, o estudo verificou que as métricas de código são bons indicadores da presença de bugs, mas não são eficazes na previsão da severidade dos bugs. As ferramentas de análise estática, por sua vez, mostraram-se limitadas na detecção de muitos tipos de bugs e na avaliação precisa de sua severidade, frequentemente atribuindo valores fixos de severidade sem considerar o contexto do software. A análise qualitativa revelou que a severidade dos bugs está mais relacionada às especificações do software do que à complexidade do código, e que bugs de baixa severidade podem existir em métodos complexos, enquanto bugs de alta severidade podem ocorrer em métodos simples.

## Fichamento Bibliográfico

   - **Severidade de Bugs**  Refere-se ao impacto que ele tem no funcionamento do sistema. Bugs de alta severidade podem causar falhas críticas, como travamentos do sistema ou perda de dados, enquanto bugs de baixa severidade têm um impacto menor. (página 1).
   
   - **Ferramentas de Análise Estática** Usadas para detectar bugs e problemas potenciais no código sem executá-lo. Essas ferramentas utilizam técnicas como correspondência de padrões e análise de fluxo de dados para identificar bugs com base em regras predefinidas. (página 6).

   - **Métricas de Código-Fonte** Medidas quantitativas usadas para avaliar características do código, como complexidade, legibilidade e manutenibilidade. (página 4).


# Fichamento de Citações

- _"The results show that most of the code metrics (e.g., Lines of Code, McCabe, McClure, Nested Block Depth, Proxy Indentation, FanOut, Readability, Difficulty, and Effort) are good indicators of buggyness, but they perform quite poorly for predicting bug severity."_

- _"Results show that the studied static analysis tools (SpotBugs, and Infer) are not yet powerful enough to find many bug types, and in many cases, they mislabel the bug severity."_

- _"We found no direct relationship between method complexity and its severity value. Many low-severity bugs exist in the quite complex methods according to the code metrics, but these functions handle trivial functionalities, such as GUI, or they do not lead to a crash or unauthorized access."_

- _"Critical bugs may cause a system to crash completely or cause non-recoverable conditions such as data loss. High-severity bugs affect major system components that prevent users from working with some parts of the system."_