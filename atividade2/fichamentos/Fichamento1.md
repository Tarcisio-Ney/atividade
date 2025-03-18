# Would static analysis tools help developers with code reviews

S. Panichella, V. Arnaoudova, M. Di Penta and G. Antoniol, "Would static analysis tools help developers with code reviews?," 2015 IEEE 22nd International Conference on Software Analysis, Evolution, and Reengineering (SANER), Montreal, QC, Canada, 2015, pp. 161-170, doi: [10.1109/SANER.2015.7081826](https://doi.org/10.1109/SANER.2015.7081826).

# Fichamento de Conteúdo

Os autores do artigo tem com tema central do artigo as ferramentas de análise estática de código e como essas podem deixar ruidos ao serem utilizadas, outrossim como os desenvolvedores se comportam ao entrarem em contato com esses ruidos gerados pelas ferramentas que estão utiulizando. Nesse sentido, o estudo buscou investigar três três focos principais de pesquisa, esses são: se os alertas gerados por ferramentas de análise estática são removidos durante as revisões de código; (ii) quais tipos de alertas os desenvolvedores prestam mais atenção durante as revisões de código; e (iii) se há evidências qualitativas de tratamento de alertas em repositórios de software e/ou comentários de revisões.
Para realizar a pesquisa os autores utilizaram duas ferramentas de análise estática, sendo elas CheckStyle e PMD, e extrairam dados de 6 repositórios do Gerrit. Para ser feita a comparação apenas três dos repositórios escolhidos os desenvolvedores utilizaram ferramentas de análise estática. Por fim é feita uma análise qualitativa dos dados obtidos, afim de fornecer evidências do comportamento dos desenvolvedores.
Por fim o estudo concluiu que os desenvolvedores tendem a focar na resolução de problemas especificos e que frequentemente mais de 50%, em alguns casos até 100%, desses erros são resolvidos. As ferramentas de análise estática podem ser úteis durante o processo de desenvolvimento. Em outras palavras, a remoção de certos alertas antes de enviar um patch pode ajudar a reduzir a carga durante o processo de revisão.


## Fichamento Bibliográfico

   - **Revisões Modernas de Código** Um método menos formal de realizar revisões de código por pares afim de melhorar a qualidade do software, corrigindo bugs e facilitando a manutenção do código. (página 1)

   - **Gerrit** Ferramenta de revisão de código integrada ao Git, que permite aos desenvolvedores enviar patches para revisão, receber feedback de revisores e verificadores, e integrar as alterações ao repositório principal após aprovação. (página 3)

   - **Teste de Tukey’s HSD** Teste estatístico utilizado para comparar múltiplos grupos após a realização de uma Análise de Variância (ANOVA). (página 4)



# Fichamento de Citações

- _"During code reviews, developers try to improve software quality in different ways, for example, fixing bugs or making the code easier to be maintained."_

- _"If properly used, static analysis tools can provide a useful support during the development process. In other words, the removal of certain warnings before submitting a patch could help reducing the burden during the review process."_

- _"Qualitative analysis of the code review comments also show that developers take care of warnings reported by static analyzers"_

- _"We found that some specific categories of warnings, for example imports, regular expression, and type resolution were in general removed more than others across all projects, and likely deserve more attention by developers. "_