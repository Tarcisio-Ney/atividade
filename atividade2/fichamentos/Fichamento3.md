# An empirical study on bug severity estimation using source code metrics and static analysis

Ehsan Mashhadi, Shaiful Chowdhury, Somayeh Modaberi, Hadi Hemmati, Gias Uddin, An empirical study on bug severity estimation using source code metrics and static analysis, Journal of Systems and Software, Volume 217, 2024, 112179, ISSN 0164-1212, doi: [10.1016/j.jss.2024.112179](https://doi.org/10.1016/j.jss.2024.112179).

# Fichamento de Conteúdo

Os autores do artigo têm como tema central a manutenção de software e os desafios associados à detecção e correção de bugs, especialmente aqueles de alta severidade. O estudo destaca que a manutenção de software é uma das fases mais desafiadoras e caras do ciclo de vida do desenvolvimento de software, e que a correção de bugs graves é particularmente complexa, pois pode levar a falhas críticas no sistema, como perda de dados ou indisponibilidade. Nesse sentido, o estudo buscou investigar três focos principais de pesquisa: (i) se métricas de código-fonte são bons indicadores de bugs e sua severidade; (ii) qual a capacidade das ferramentas de análise estática em detectar bugs e prever sua severidade; e (iii) quais são as características dos bugs com diferentes níveis de severidade.
Para realizar a pesquisa, os autores utilizaram dois conjuntos de dados populares (Defects4J e Bugs.jar), que contêm bugs reais de projetos Java de código aberto. Foram analisados 19 projetos, totalizando 1668 bugs (3358 métodos bugados), além de uma amostra qualitativa de 140 bugs. As ferramentas de análise estática estudadas foram SpotBugs e Facebook Infer, que foram avaliadas quanto à sua capacidade de detectar bugs e prever sua severidade. Além disso, foram utilizadas métricas de código, como Linhas de Código (LOC), Complexidade de McCabe e Métricas de Halstead, para investigar sua relação com a presença e severidade de bugs.
Os resultados mostraram que, embora as métricas de código sejam bons indicadores da presença de bugs, elas têm desempenho ruim na previsão da severidade dos bugs. As ferramentas de análise estática, por sua vez, demonstraram limitações na detecção de certos tipos de bugs e na avaliação precisa de sua severidade, muitas vezes atribuindo valores fixos de severidade sem considerar o contexto do software. Além disso, o estudo revelou que a severidade dos bugs está mais relacionada às especificações do software do que à complexidade do código, e que muitos bugs de baixa severidade estão presentes em métodos complexos que lidam com funcionalidades triviais.

## Fichamento Bibliográfico

   - **Modelos de Linguagem de Grande Escala (LLMs)** São sistemas de inteligência artificial treinados em grandes volumes de dados textuais, capazes de entender e gerar código-fonte ou texto. (página 18)

   - **Métricas de Código no Nível de Método** Medidas quantitativas aplicadas a métodos individuais para avaliar características como complexidade, tamanho, legibilidade e esforço de manutenção. (página 3)

   - **Unificação de Rótulos de Severidade** Processo de mapear rótulos de severidade brutos (RSL) para categorias padronizadas (USL), como "Crítico", "Alto", "Médio" e "Baixo". (página 4)



# Fichamento de Citações

- _"Critical bugs may cause a system to crash completely or cause non-recoverable conditions such as data loss. High-severity bugs affect major system components that prevent users from working with some parts of the system."_

- _"Our results suggest that code metrics are good indicators of bug-prone methods. Our results are interesting because the true effectiveness of code metrics has been historically debated."_

- _"We observed that existing static bug detection tools perform extremely poorly in detecting real-world bugs. These tools suffer from both false positives and false negatives, confirming earlier findings."_

- _"Results show that the studied static analysis tools (SpotBugs, and Infer) are not yet powerful enough to find many bug types, and in many cases, they mislabel the bug severity. "_