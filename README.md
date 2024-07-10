# 🛸 Desafio: Aprenda na Prática Programação Orientada a Objetos 🛸

<h2>🛑 Pré-Requisitos</h2>

<p>
✅ Conhecer a sintaxe da Java<br>
✅ Java JDK 11<br>
✅ IDE para desenvolvimento Java (usarei IntelliJ)<br>
✅ Git<br>
✅ Conta no GitHub<br>
</p>

## 👣 Passo-a-Passo

<p>
<strong>	1.</strong> Vamos ABSTRAIR o DOMÍNIO Bootcamp e MODELAR seus ATRIBUTOS E MÉTODOS <br>
<strong>	2.</strong> Criaremos as CLASSES: Bootcamp, Cursos, Mentorias e Devs e vamos relaciona-las <br>
<strong>	3.</strong> As CLASSES Curso, Mentoria e Devs também serão MODELADOS, ou seja, criaremos seus ATRIBUTOS E MÉTODOS <br> 
<strong>	4.</strong> Para que o código fique mais legível e de fácil manutenção, iremos utilizar de algumas das ferramentas que o PARADIGMA DE ORIENTAÇÃO A OBJETOS (POO) nos oferece: ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO <br>
<strong>	5.</strong> E para representar CLASSES que foram criadas e relacionadas, iremos transforma-las em OBJETOS

<table>
  <tr>
    <td>   
        <img height="150em" src="https://github.com/raphaelkauan/AbstrairBootcamp-Desafio/assets/111379005/7621ee63-f957-4d11-bef1-3247a943865d"/>
    </td>
    <td>     
        <img height="150em" src="https://github.com/raphaelkauan/AbstrairBootcamp-Desafio/assets/111379005/15c399ec-5246-4f72-8ae5-589166385f09"/>
    </td>
     <td>      
        <img height="150em" src="https://github.com/raphaelkauan/AbstrairBootcamp-Desafio/assets/111379005/5bbe5dea-7fb6-4dfa-838e-a7ea1a394dd9"/>
    </td>
  </tr>
</table>
</p>

---

<h2> 🎲 Paradigmas de programação orientada a objetos (PARA UMA CRIANÇA ENTENDER) <img height="20em" src="https://img.icons8.com/external-smashingstocks-outline-color-smashing-stocks/256/external-Duckling-seasons-smashingstocks-outline-color-smashing-stocks.png"/>
</h2>

<p>
Programação Orientada a Objetos é um jeito de escrever programas de computador que se baseia na ideia de objetos. Pense em um objeto na vida real, como um brinquedo, por exemplo. Esse brinquedo tem algumas características que o tornam diferente de outros brinquedos, como sua cor, tamanho e forma. Ele também pode fazer algumas coisas, como emitir som ou se mover.

Na programação orientada a objetos, criamos objetos como esses para representar coisas do mundo real no computador. Cada objeto tem suas próprias características (chamadas de atributos) e ações que ele pode realizar (chamadas de métodos).

🔱 Principais pilares do POO: ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO. 🔱
</p>

---

<h3> 🚖 ABSTRAÇÃO:</h3>

<p>
Abstração é como se fosse uma simplificação de algo muito complicado. Imagine que você tem um carrinho de controle remoto com vários botões e funções. Para você brincar com ele, não precisa saber todos os detalhes de como ele funciona, mas apenas as funções mais importantes, como ligar, desligar, ir para frente e para trás. Isso é uma abstração, ou seja, você não precisa entender como o carrinho funciona por dentro, mas apenas o que ele pode fazer. Na programação orientada a objetos, a abstração é usada para criar classes que representam objetos do mundo real de uma forma mais simples e fácil de usar.
</p>

<h3> 🚘 ENCAPSULAMENTO:</h3>

<p>
Encapsulamento em Java é como uma caixa que guarda um tesouro. O tesouro dentro da caixa é importante e precioso, mas só pode ser acessado pelas pessoas que têm a chave da caixa. Do mesmo modo, em Java, podemos colocar nossos dados importantes dentro de uma "caixa" chamada classe e protegê-los para que só possam ser acessados ​​por meio de métodos específicos (as chaves). Isso nos ajuda a manter nossos dados seguros e organizados e evita que outras partes do programa os acessem de forma inadequada ou inesperada.
</p>

<h3> 🚍 HERANÇA:</h3>

<p>
Imagine que você está construindo uma cidade de brinquedo com vários prédios, como escolas, hospitais e casas. Agora, você quer adicionar um novo prédio à sua cidade, mas ele é muito parecido com um dos prédios que você já construiu. Em vez de construir um novo prédio do zero, você pode usar o prédio existente como base e apenas fazer algumas alterações nele para criar o novo prédio. Isso é basicamente o que a herança faz em Java. Em vez de escrever um novo código do zero, podemos criar uma nova classe que é baseada em uma classe já existente, chamada classe pai. A nova classe é chamada classe filha e ela herda todas as características da classe pai. Podemos então adicionar ou substituir algumas características específicas na classe filha, para atender às nossas necessidades.
</p>

<h3> 🚔 POLIMORFISMO:</h3>

<p>
Polimorfismo é como se fosse uma brincadeira de trocar de roupa. Sabe quando você tem uma fantasia de princesa e pode trocar a saia, a blusa e a coroa? Então, imagine que você tem uma caixa de fantasias e pode trocar as peças para criar novas combinações. Na programação, isso é parecido com as classes, que são como as fantasias. Cada classe tem seus próprios métodos e propriedades, como a saia e a blusa da fantasia de princesa. Mas o legal do polimorfismo é que você pode trocar esses métodos e propriedades de uma classe para outra, assim como troca as peças da fantasia.
</p>
<br>

<h2> 🧮 Linguagem de Programação vs Paradigma de Linguagem de Programação</h2>

<p>
<h3> ✨ LINGUAGEM DE PROGRAMAÇÃO:</h3> 
É uma linguagem formal que, através de uma série de instruções, permite que um programador escreva um conjunto de ordens, ações consecutivas, dados e algoritmos para criar programas que controlam o comportamento físico e lógico de uma máquina.<br>
Seguem alguns exemplos de como as linguagens de programação podem ser classificadas:<br>
<br>
🔺 Nível de abstração:<br>
Baixo Nível: Assembly<br>
Médio Nível: C, C++, D, Objective C, etc.<br>
Alto Nível: Java, C#, PHP, Javascript, etc.<br>
Altíssimo Nível: Python, Ruby, Elixir, etc.<br>
<br>
🔺 Paradigma de programação:<br>
Programação Estruturada: C, Pascal, Ada, etc.<br>
Programação Orientada a Objetos: Java, C#, C++, Objective C, D, etc.<br>
Programação Funcional: Lisp, Scheme, Erlang, Elixir, etc.<br>
<br>
🔺 Linguagens classificadas pela arquitetura da aplicação:<br>
Desktop: C, C++, Object Pascal, Java, etc.<br>
Web: PHP, Ruby, Javascript, Java, etc.<br>
<br>
🔺 Tipo de execução:<br>
Linguagens compiladas: C, C++, Pascal, D, GO, etc.<br>
Linguagens Interpretadas: Python, Ruby, PHP, Javascript, etc.<br>
Linguagens Hibridas: Java, Erlang, Elixir, etc.<br>


<h3> ✨ PARADIGMA DE LINGUAGEM DE PROGRAMAÇÃO</h3> 

É um conjunto de características que podem ser utilizados para categorizar determinado grupo de linguagens. Um paradigma pode oferecer técnicas apropriadas para uma aplicação específica.<br>
<br>
<strong>PARADIGMAS PRINCIPAIS e SEUS SUBPARADIGMAS</strong><br>

🔸 <strong>1. Paradigma Imperativo</strong><br>
Neste paradigma, o programa descreve o processamento necessário para solucionar o problema. Assim, o paradigma imperativo é caracterizado por execução sequencial de instruções, pelo uso de variáveis que representam posições de memória e pelo uso de instruções de atribuição que alteram os valores dessas variáveis.<br>
Vejamos alguns Subparadigmas do Paradigma Imperativo e exemplos linguagens de programação que adotam esses subparadigmas.<br>
<br>
🔸  1.1 Paradigma estruturado:  ALGOL 58 e ALGOL 60 <br>
🔸  1.2 Paradigma concorrente: Java e Ada<br>
🔸  1.3 Paradigma Orientado a Objetos: Smalltalk e Java<br>
<br>
🔹 <strong>2. Paradigma Declarativo</strong><br>
Este paradigma é o modelo no qual os resultados são descritos, mas os passos para chegar aos resultados não são estabelecidos.<br>
Vejamos alguns Subparadigmas do Paradigma Declarativo e exemplos linguagens de programação que adotam esses subparadigmas:<br>
<br>
🔹 2.1 Paradigma Funcional: Lisp e Haskell<br>
🔹 2.2 Paradigma Lógico: Prolog<br>
</p>

---

##### Em resumo o paradigma de programação orientada a objetos se baseia em criar objetos com suas próprias características e ações, e combiná-los para criar programas complexos. Isso torna a programação mais organizada e fácil de se entender, permitindo uma maior expressividade na representação de conceitos e estruturas complexas.
