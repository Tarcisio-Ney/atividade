# What Code Is Deliberately Excluded from Test Coverage and Why?

A. Hora, "What Code Is Deliberately Excluded from Test Coverage and Why?," 2021 IEEE/ACM 18th International Conference on Mining Software Repositories (MSR), Madrid, Spain, 2021, pp. 392-402, doi: [10.1109/MSR52588.2021.00051](https://doi.org/10.1109/MSR52588.2021.00051).

# Fichamento de Conteúdo

O estudo analisou as práticas de exclusão de código nos relatórios de cobertura de testes, investigando quais partes do código são excluídas e os motivos dessas exclusões. A motivação desse estudo surgiu da necessidade de compreender como as exclusões afetam a precisão dos relatórios de cobertura, uma vez que algumas partes do código são deliberadamente ignoradas pelos desenvolvedores.
Os autores realizaram uma análise empírica em 55 projetos populares em Python que utilizam medição de cobertura de testes. Primeiramente, foram extraídas informações sobre a utilização da funcionalidade de exclusão de código. Em seguida, commits e comentários no código foram analisados para identificar os motivos que levaram às exclusões. Os principais resultados mostraram que mais de um terço dos projetos analisados (20 de 55) utilizam a exclusão de cobertura, somando 534 casos identificados. 
Com base nesses achados, os autores discutem várias implicações para desenvolvedores e pesquisadores, como a melhoria de ferramentas de cobertura de testes para exigir justificativas obrigatórias ao excluir trechos de código, a definição de diretrizes para documentação das exclusões, e o desenvolvimento de métodos para detectar vieses em relatórios de cobertura. Essas melhorias podem contribuir para relatórios mais precisos e para o aprimoramento das práticas de revisão de código.

## Fichamento Bibliográfico

   - **cobertura de testes** É a métrica que indica a porcentagem de código que é coberta pelos testes, ou seja, quais partes de um programa são realmente executadas durante a execução dos testes. (página 1).
   
   - **Exclusão de Código** Prática de marcar partes do código que não devem ser consideradas nos relatórios de cobertura de testes. (página 1).

   - **Cobertura**  Ferramenta para Java que mede a cobertura de código. Ela ajuda a identificar áreas não testadas em aplicações Java. (página 2).


# Fichamento de Citações

- _"assessing and detecting code coverage exclusion practices can improve code review workflow by eliminating possible noisy code."_

- _"Software testing is a key activity in modern software development. Test coverage is largely adopted nowadays to support software testing"_

- _"In practice, not all code is equally important for coverage analysis."_

- _"We have seen that developers tend to exclude code that is hard to test from coverage, such as complex and non-deterministic snippets "_