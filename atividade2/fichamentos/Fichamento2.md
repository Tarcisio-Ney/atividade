# Detecting Software Vulnerabilities in Android Using Static Analysis

R. Dhaya and M. Poongodi, "Detecting software vulnerabilities in android using static analysis," 2014 IEEE International Conference on Advanced Communications, Control and Computing Technologies, Ramanathapuram, India, 2014, pp. 915-918, doi: [10.1109/ICACCCT.2014.7019227](https://doi.org/10.1109/ICACCCT.2014.7019227).

# Fichamento de Conteúdo

O estudo apresentou um método que caracteriza aplicativois movéis como maliciosos ou benignos. Os autores propuseram técnicas dew prevenção contra malwares que se baseiam em análises estáticas e no modelo N-gram para dispositivos móveis. Essa abordagem foi escolhida pois a maior parte das empresas atuais utilizam técnicas baseadas na detecção da assinatura dos malwares para se previnirem, o que acabva sendo ineficiente contra novos tipos de vírus.
Os métodos escolhidos consistiam em realizar engenharia reversa no código-fonte nos arquivos .apk dos projetos utilizando ferramentas apropriadas como: Dex2jar, JD-GUI e Apktool. Na segunda etápa foram extraidas as caracteristicas que classificavam os aplicativos como benignos ou maliciosos. Entre as informações coletadas estavam chamadas de API, fluxo de chamadas e uso de memória do dispositivo e as vulnerabilidades testadas foram injeção de SQL, exposição de senhas, operações DML inseguras e stack traces reveladas. Após as extração o modelo N-gram era aplicado nas caracteristicas coletadas, detectando as assinaturas presentes. Por fim o sistema separa os códigos benignos dos maliciosos e os salva em um arquivo .csv.


## Fichamento Bibliográfico

   - **N-gram analysis** É um tipo de modelo probabilístico. Utilizando o conceito de modelo de cadeia de Markov, em que uma sequência de elementos de uma sequência de dados de entrada é utilizada para prever o próximo item. (página 2).
   
   - **Assinatura**  É um padrão binário do código de um determinado vírus que pode ser composto por strings ou binários. Grande parte das empresas utiliza métodos que identificam esse padrão, assim detectando os malwares. (página 1).

   - **Engenharia Reversa**  A engenharia reversa é uma técnica usada para examinar um código já existente com o objetivo de identificar vulnerabilidades ou comportamentos maliciosos em um software permitindo reconstruir o código-fonte a partir de arquivos executáveis. (página 2).



# Fichamento de Citações

- _"Android platform is becoming very popular today and it is getting more vulnerable because it is an open source and easy to develop the applications freely."_

- _"Static approach assists to recognize the vulnerabilities such as SQL injection, Data Manipulation Language (DML), Password, Cookie poisoning, etc"_

- _"Rapid growth of the malwares in every year in android based mobile devices"_

- _"The test set application's codes are compared with training set application which is already trained to the machine and it contains many examples collected from the public resources. "_