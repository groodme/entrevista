# Prova de Conhecimentos

Este repositório apresenta uma pequena prova de conhecimentos aplicada aos candidatos para uma vaga em desenvolvimento de software na Chicletemkt.

A intenção desta prova é medir seu conhecimento em programação de computadores e uso de ferramentas de desenvolvimento de software. Serão avaliados a sua lógica, clareza de pensamento e a organização do seu código.

# Instruções

- Faça um fork deste repositório.
- Crie um branch com o seu nome. 
- Dentro do diretório _src_ coloque a sua solução.
- Salve em _src/DOC.md_ a documentação da sua solução.
- Ao terminar, faça um pull request com toda a sua solução.

A documentação da sua solução deverá conter instruções sobre como construir e executar sua solução. Deverá, também, conter uma rápida documentação sobre como usar a sua solução.

Ao realizar o fork, você terá 48 horas para avaliar, projetar, desenvolver e realizar o pull request.

Caso o pull request não seja realizado em 48 horas, você estará automaticamente desclassificado. 

Caso não consiga cumprir o desafio dentro das 48 horas, justifique por que não conseguiu dentro do arquivo _DOC.md_ e faça o pull request dentro do prazo para que o que você fez seja avaliado.

Não use frameworks ou bibliotecas que implementem a solução do problema. Você pode usar frameworks para implementar entradas de dados, UI e outras características que não fazem parte do problema em si.

# O Problema

Escreva um software que converta um número inteiro sem sinal em sua representação por extenso na língua portuguesa. Na representação por extenso devem ser respeitadas as regras de pontuação. Veja os exemplos:

- _1545_: mil, quinhentos e quarenta e cinco
- _5234123_: cinco milhões, duzentos e trinta e quatro mil e centro e vinte e três
- _2756986456_: dois bilhões, setecentos e cinquenta e seis milhões, novecentos e oitenta e seis mil e quatrocentos e cinquenta e seis.
- _125_: cento e vinte e cinco
- _42_: quarenta e dois
- _112112_: cento e doze mil e cento e doze

A entrada de dados da sua solução deverá validar a entrada, garantindo que a sua rotina receba única e exclusivamente números inteiros positivos. Os números deverão ser fornecidos na base de numeração decimal. Números binários, hexadecimais, octais e caracteres que não representem dígitos deverão ser criticados na sua entrada de dados.