# Easy

Nesse arquivo existem alguns desafios para:

- Tipos de dados com javascript
- Condicionais
- Loops
- Functions e arrow functions

Ao clicar no titulo você poderá ver um repositório auxiliar com exemplos da linguagem

## Tipos de dados

### [Boolean](https://github.com/SerraZ3/introducao-js-com-node#boolean)

1º Declare uma variável chamada `status` onde ela receberá uma valor booleano qualquer. Após isso imprima `Ativo` caso o `status` seja verdadeiro e `Desativado` caso o `status` seja falso.

2º Em um sistema de gerenciamento de clientes existem dois tipos de usuários, usuário adminstrador e usuário comum. Para identificar qual o tipo de usuário está acessando a plataforma uma variável chamada `administrador` foi criada. Seu valor é do tipo booleano. Imprima na tela `O usuário é administrador` caso `administrador` seja verdadeiro e `O usuário é comum` caso `administrador` seja falso.

### [Number](https://github.com/SerraZ3/introducao-js-com-node#number)

1º Raul Seixas nasceu a 10.000 anos atrás e afirmou que não havia nada nesse mundo que ele não saiba demais. Crie uma variável que recebe a idade de um ser milenar e imprima "Não tem nada nesse mundo que eu não saiba demais" caso sua idade seja igual ou maior que 10.000 anos e imprima "Ainda existe muita coisa que eu não sei" caso sua idade seja menor que 10.000 nos.

2º João foi comprar um rango no mercado e levou consigo R$30.00. Lá ele comprou leite (R$4.50), pão (R$5.30) e mortadela (R$8,45). Crie uma variável que receberá o valor total de João e outras 3 chamada `leite`, `pao` e `mortadela` que receberá o seu valor respectivo. Em seguida subtraia o valor da compra do João do seu total e imprima na tela o valor gasto para ele e em seguida o seu troco.

3º O IMC é reconhecido como padrão internacional para avaliar o grau de sobrepeso e obesidade. É calculado dividindo o peso (em kg) pela altura elevada (em metros) ao quadrado. Luana deseja automatizar esse processo e pediu sua ajuda. Para isso deve criar duas variáveis, uma para peso e outra para altura. Em seguida imprima na tela `Seu IMC é: X` onde no lugar de X aparecerá o IMC da pessoa.

### [String](https://github.com/SerraZ3/introducao-js-com-node#string)

1º Crie três variáveis (nome, sobrenome e profissão) e em seguida imprima a seguinte frase `Oi sou o NOME SOBRENOME e trabalho com PROFISSÃO` substituindo o valor das palavras em maiúsculo pelo valor das variáveis. Para esse exercício deve usar as três formas de declaração e concatenação de string (aspas simples, aspas duplas e template string)

2º Lucas queria saber qual de seus 15 irmãos tem o nome com a maior e a menor quantidade de letras. Para isso pediu ajuda para você criar um programa que receba um nome e imprima o tamanho do seu nome.

3º Ricardo tem uma plataforma de usuários e gostaria que seus usuários tenham foto de perfil, mas nem todos os usuários tem foto de perfil. No lugar da foto, você, como um gênio da computação, decidiu por as iniciais do nome e sobrenome de cada usuário. Para isso crie duas variávei (nome e sobrenome) e imprima a junção da primera letra de cada uma.

4º Seu chefe é um cara muito calmo, mas as vezes ele fica estranhamente estressado e começa a gritar. Para zoar um pouco ele você deve criar um programa que imprimia a frase `estou muito puuuuuto` toda em maiusculo (uppercase) e em seguida `ESTOU MAIS CALMO AGORAAAA` em minusculo (lowercase).

5º `O rato roeu a roupa do rei de roma` é uma frase que irrita todos os estilistas do mundo pois eles odeiam a ideia de sua criação sendo roida. Para solucionar esse problema você deve pegar a frase `O rato roeu a roupa do rei de roma` remover a parte `a roupa do rei de roma` e em seguida colocar a frase `uma queijada de leve e não a roupa do rei` fazendo a frase final ficar assim `O rato roeu uma queijada de leve e não a roupa do rei`. Diga: busque por `slice()`

6º Maria Júlia tem 5 anos e esta aprendendo a contar. Para isso ela está contando o nome do seu pai (`Ricardo Antônio Lopes Lemos Silva Júnior`) e sua mãe (`Joaquina Pereira Freitas Oliveira Silva`). Com preguiça de conferir esse resultado e prevendo que sua filha iria contar nome de outras pessoas Joaquina pediu a você que criasse um programa que recebe um nome e imprime quantas letras esse nome tem. Lembre-se você deve retirar os espaços do nome :wink:

### [Array](https://github.com/SerraZ3/introducao-js-com-node#array)

1º Professor Marcelo com preguiça de verificar a quantidade de alunos que ele possui pediu pra você criar um código que receba um array com a lista de nome dos alunos e imprima a quantidade de alunos nessa lista. Você que é "mais melhor de bom" que o previsto irá imprimir a quantidade de alunos e o primeiro e último aluno

2º Existe um ranking de melhores programadores do Brasil, é uma lista com 300 pessoas. Você deve criar um programa que receba um array com o nome de pessoas e mostrar somente um array com as 3 primeiras posições. Usar `splice`

3º Você foi designado como gerente do Super Mercado Paçoquinha, como primeiro feito você deve criar um programa para o caixa. O programa deve imprimir uma lista com os produtos, mas você deve simular como se fosse um caixa, ou seja, adicionar o nome de cada um dos produtos um por um. Crie a variável `caixa` que será um array vazio e em seguida adicione 5 produtos, um por um, o final do array. Dica: buscar pesquisar por `push`

4º O gerente do Super Mercado Paçoquinha adorou o programa que você fez acima, porém dele deparou com um probleminha. Ele acabou atendendo um cliente que queria alterar o primeiro produto por outro mas seu programa não conseguia fazer isso. Então você como o melhor gerente do Brasil decidiu fazer essa alteração. Para isso você deve retirar o primeiro elemento do array e depois por um novo elemento no inicio do array. Retire do array a baixo o `Pão` e adicione `Cuscuz`. Dica: Busque por `shift` e `unshift`

```js
let caixa = ["Pão", "Mortandela", "Leite", "Ovo", "Manteiga"];
```

5º Você recebeu a proposta multimilionária de atualizar o sistema do Banco do Brasil. Quando você estava atualizando as datas de movimentação de dinheiro percebeu que as datas eram armazenadas da seguinte forma: `let data = [10, 05, 2021]` onde a primeira posição era o dia, depois o mês e a ultima o ano. Então você deve alterar de array para string e pondo no seguinte formato: `let data = "10/05/2021"` para melhorar o banco e virar milhonário. Dica: Busque por `join`

6º A escolinha do Professor Raimundo decidiu automatizar a entrada de alunos. Sempre que um aluno entrar na escola ele deve digitar seu nome e aparecerá na tela o número dele na lista. Para isso você recebeu a lista de alunos:

```js
let alunos = ["Pedro", "Felipe", "Ana Cláudia", "Luiza", "Mariana"]
```

Agora com a lista crie um código que verifique se o aluno existe na lista (caso o aluno exista imprima "Aluno existe" se não "Aluno inexistente") e em seguida, caso exista, deve imprimir a posição dele na lista. Dica: Buscar por `includes`, `indexOf` e `lastIndexOf`

7º O Super Mercado Paçoquinha decidiu melhorar novamente seu sistema de caixa. Dessa vez ele quer substitui qualquer elemento do caixa em qualquer posição. Na lista abaixo você deve buscar por "Leite" e substituir ele por "Cuscuz" e depois substituir "Ovo" por "Biscoito". Para isso você deve criar uma variável chamada `buscarPor` que irá receber "Cuscuz" e em seguida pesquisar se a variável `buscarPor` existe no array. Se existir pegue a posição dela e altere essa posição pelo valor de `buscarPor`, se não imprima "Esse produto não existe na lista". Em seguida repita o processo trocando "Ovo" por "Biscoito". Dica: Buscar por `includes`, `indexOf` e `lastIndexOf`

```js
let caixa = ["Pão", "Mortandela", "Leite", "Ovo", "Manteiga"];
```
