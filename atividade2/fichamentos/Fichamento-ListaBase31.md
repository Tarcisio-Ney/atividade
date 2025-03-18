# Tool Choice Matters: JavaScript Quality Assurance Tools and Usage Outcomes in GitHub Projects

D. Kavaler, A. Trockman, B. Vasilescu and V. Filkov, "Tool Choice Matters: JavaScript Quality Assurance Tools and Usage Outcomes in GitHub Projects," 2019 IEEE/ACM 41st International Conference on Software Engineering (ICSE), Montreal, QC, Canada, 2019, pp. 476-487, doi: [10.1109/ICSE.2019.00060](https://doi.org/10.1109/ICSE.2019.00060).

# Fichamento de Conteúdo

O estudo tem enfoque na Integração Contínua (CI) e Entrega Contínua (CD), principalmente no quesito de automação de software, e em como  ferramentas de alta qualidade tem democratizado o acesso a pipelines de automação. Nesse sentido o artigo busca responder a seguinte questão: Dado um conjunto de dados suficientemente grande de traços de pipelines de CI (Integração Contínua), podemos contextualizar e quantificar o benefício de incorporar uma ferramenta específica em um pipeline?
Para responder essa questão os autores extrairam de um conjunto de dados de pacotes npm do JavaScript a adoção de três classes de ferramentas de garantia mais utilizadas, são elas: linters, gerenciadores de dependências e ferramentas de cobertura de código. Com isso foram exploradas multiplas ferramentas em cada uma das três classes, iodentificando suas diferenças fundamentais. Utilizando esses dados e análises qualitativas de discussões em issues e pull requests no GitHub foram desenvolvidos métodos estatisticos para avaliar as diferentes ferramentas de automação nos quesitos de: Prevalência de issues; churn de código; número de pull requests; número de contribuidores.
Em conclusão, o estudo verificou que os projetos frequentemente trocam de ferramentas dentro da mesma categoria de tarefa, sugerindo uma necessidade de mudança ou que a primeira ferramenta escolhida não era adequada. Além disso, apenas algumas ferramentas dentro de uma mesma categoria demonstram ser geralmente benéficas para a maioria dos projetos que as utilizam. Por fim foi identificado durante as análises do artigo que as ferramentas standardJS, coveralls e david se destacaram dentre as demais.

## Fichamento Bibliográfico

   - **Linters** São ferramentas de análise estática de código que são utilizadas para definir um padrão de codificação em todo projeto. (página 2).
   
   - **Trade-offs** As implicações práticas de escolher uma ferramenta em vez de outra, como o esforço de configuração, a sobrecarga de manutenção e o impacto na qualidade do código. (página 3).

   - **Dependency Managers** São ferramentas que ajudam a manter as dependências do projeto atualizadas e seguras, notificando sobre novas versões. (página 3).


# Fichamento de Citações

- _"A viable automation pipeline typically contains more than one tool, strung together in some order of task accomplishment"_

- _"Developers want powerful and highly configurable systems, yet simple and easy to use"_

- _"It is apparent that the majority of projects appear to adopt one tool and stick with it. This may be due to a prevalence of a “set it and forget it” mentality"_

- _"Dependency management tools may cause developers to suffer from notification fatigue, when they issue too many automated warnings. "_