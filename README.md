# Java-e-java.lang-programe-com-a-classe-Object-e-String


Os packages são usados para organizar o código e fazem parte do nome completo da classe (FQN), que é composto pelo nome do package seguido do nome simples da classe. A definição do package deve ser a primeira declaração no código fonte e pode ser importado para facilitar o uso de classes de outros packages. A nomenclatura padrão é usar o nome do domínio da web ao contrário junto com o nome do projeto.

*a nomenclatura padrão é usar o nome do domínio na web ao contrário junto com o nome do projeto, por exemplo:*

* br.com.caelum.geradornotas <br>
* br.com.alura.gnarus <br>
* br.gov.rj.notas <br>
* de.adidas.lager <br>

 Há quatro níveis de visibilidade, que são private, default, protected e public, e esses modificadores podem ser usados na definição da classe, atributo, construtor e método.
 
Javadoc é uma documentação para desenvolvedores que pode ser gerada no Eclipse através de comentários e tags (anotações).
As classes Java padrão também usam o Javadoc. É possível criar nossa própria biblioteca com o JAR (Java Archive) e importá-la em um novo projeto. Além disso, é possível criar um JAR executável.
O pacote java.lang é o único pacote que não precisa ser importado e contém classes fundamentais como String e System. A classe String é imutável e é representada por uma sintaxe literal, e qualquer método de alteração da classe String devolve uma nova String. A classe String é uma CharSequence e para concatenar muitos Strings, deve-se usar a classe StringBuilder. Foram vistos vários métodos da classe String, como trim, charAt, contains, isEmpty, length, indexOf e replace.
