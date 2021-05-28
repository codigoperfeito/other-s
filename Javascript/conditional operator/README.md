![image](https://user-images.githubusercontent.com/78365951/119541578-f33a5e00-bd64-11eb-8bc0-16eae52cf99b.png)


# Operador condicional ternário (?:)


*(PT/BR)*<br>
- Primeiro exemplo é um operador condicional basico que pode substituir o 'if' em alguns momentos, ele é um operador condicional que utiliza a "?" para dividir o parametro das condições e ":" para o resultado das condições, observe o exemplo a baixo.
  <br>
### 1º Exemplo: Sem variavel 📝<br> 
  
``` true ==  true ? 'true' : 'false'; // o valor que será retornado é 'true' porque está dentro da condição.  ```

### 2º Exemplo: Com variaveis 📝

``var x = 'hello';`` <br>
``x = x + (x == 'hello' ? " world" : 'is incorrect');``

<br> **o valor que será retornado é 'hello world' porque está dentro da condição.**

### mesma coisa de outra forma. 📝

`` let x = 'hello'; `` <br>
`` if (x == 'hello'){ `` <br>
`` x += ' world'; `` <br>
`` }else{ `` <br>
`` x += 'x not\'s true'; `` <br>
`` } `` <br>

### 3nd Example: with 2 varibles 📝

``var nome = "David", idade = 30;`` <br>
``idade > 18 ? (``<br>
``    alert("OK, você pode entrar na festa."),``<br>
``    console.log(nome + " entrou!")``<br>
``) : (``<br>
``    alert("Desculpe, você não pode entrar na festa!"),``<br>
``    console.log(nome + " não entrou!")``<br>
``);`` <br>


- Logo nós podemos observar como nos exemplos a cima que a condicional "?;" pode ser uma ferramenta muito util e utilizada para optimizar nosso código deixando-o mais limpo e agil.

### exercicio 

[clique aqui e acesse o nosso exercicio](https://github.com/codigoperfeito/Exercises/tree/main/Javascript/exercises-7#exercicio-da-aula-de-condicionais-tern%C3%A1rias)


# Ternary Conditional operator (?:)

*(EN/US)*<br>
- First example is a basic conditional operator that can replace the 'if' in a few moments, it is a conditional operator that uses a "?" to divide the parameter of the conditions and ":" for the result of the conditions, observe the example below.
<h3>1nd Example: Without variable</h3>
  
``  true ==  true ? 'true' : 'false'; // the value to be returned is "true" because it is within the condition. `` <br> 

### 2nd Example: With variables 📝

``var x = 'hello';`` <br>
``x = x + (x == 'hello' ? " world" : 'is incorrect');``
<br> ** the value that will be returned is 'hello world' because it is within the condition. **

### same thing in another way. 📝

`` let x = 'hello'; `` <br>
`` if (x == 'hello'){ `` <br>
`` x += ' world'; `` <br>
`` }else{ `` <br>
`` x += 'x not\'s true'; `` <br>
`` } `` <br>

### 3nd Example: with 2 varibles 📝

``var name = "David", age = 30;`` <br>
``age > 18 ? (``<br>
``    alert("OK, you can join the party."),``<br>
``    console.log(name + " came in!")``<br>
``) : (``<br>
``    alert("Sorry, you don't join the party!"),``<br>
``    console.log(nome + " didn't join the party!")``<br>
``);`` <br>

- Then we can see how in the examples above that the conditional "?:" Can be a very useful tool and used to optimize our code leaving it cleaner and faster.

### exercise

[click here and access our exercise](https://github.com/codigoperfeito/Exercises/tree/main/Javascript/exercises-7#exercicio-da-aula-de-condacionais-tern%C3%A1rias)
