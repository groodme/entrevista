# Prova de Conhecimentos

Este repositório apresenta uma pequena prova de conhecimentos aplicada aos candidatos para uma vaga em desenvolvimento de software na Grood.Me.

A intenção desta prova é medir seu conhecimento em programação de computadores e uso de ferramentas de desenvolvimento de software. Serão avaliados a sua lógica, clareza de pensamento e a organização do seu código, bem como o uso de boas práticas de desenvolvimento.

# Instruções

- Faça um fork deste repositório.
- Crie um branch com o seu nome. 
- Dentro do diretório _src_ coloque a sua solução.
- Salve em _src/DOC.md_ a documentação da sua solução.
- Ao terminar, faça um pull request com toda a sua solução.

A documentação da sua solução deverá conter instruções sobre como construir e executar sua solução. Deverá, também, conter a documentação sobre como usar a sua solução.

Ao realizar o fork, você terá 48 horas para avaliar, projetar, desenvolver e realizar o pull request.

Caso o pull request não seja realizado em 48 horas, você estará automaticamente desclassificado. 

Caso não consiga cumprir o desafio dentro das 48 horas, justifique por que não conseguiu dentro do arquivo _DOC.md_ e faça o pull request dentro do prazo para que o que você fez seja avaliado.

Não é preciso usar um SGDB para salvar os dados. Pode-se manter o Sqlite padrão para sua solução. 

Utilize apenas o Django. Não use apps prontos do Pypi.
# Especificação do desafio

Crie um site Django que tenha as seguintes funcionalidades:

- Criação de conta
- Login/Logout
- CRUD de frases com até 240 caracteres

As frases são apresentadas na home page, mesmo para usuários não conectados. Os usuários conectados podem criar, editar e apagar suas próprias frases. 