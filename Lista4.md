1. Considere P(x) como o predicado “x <= 4”. Quais são os valores verdade das proposições
abaixo?

	a) P(0) **→ retorna a representação “0 ≤ 4”, que é igual ao símbolo de verdade T**
	
	b) P(4) **→ retorna a representação “4 ≤ 4”, que é igual ao símbolo de verdade T**
	
	c) P(6) **→ retorna a representação “6 ≤ 4”, que é igual ao símbolo de verdade F**
2. Considere P(x) como o predicado “a palavra x contém a letra ‘a’.”. Quais são os valores
verdade das proposições abaixo?

	a) P(orange) **→ valor verdade retornado será T, pois entre ‘r’ e ‘n’ temos um ‘a’.**
	
	b) P(lemon) **→ valor verdade retornado será F.**    
	
	c) P(true) **→ considerando que temos como predicado a palavra, seu retorno será F.**
	
	d) P(false) **→ considerando que temos como predicado a palavra, seu retorno será T.**
    
3. Considere Q(x,y) como o predicado “x é a capital de y”. Quais são os valores verdade das
proposições abaixo?

	a) Q(Denver, Colorado) **→ valor verdade retornado será T,**
	
	b) Q(Detroit, Michigan) **→ valor verdade retornado será F, tendo em vista que a capital é Lansing.**
	
	c) Q(Massachusetts, Boston) **→ valor verdade retornado será F, tendo em vista que na verdade Boston é a capital de Massachisetts.**
	
	d) Q(Nova York, Nova York) **→ valor verdade retornado será F, tendo em vista que a capital é Albany.**
	
4. Constate o valor de x depois que o comando if P(x) then x:=1 for executada, em que P(x) é a
proposição “x>1”, se o valor de x, quando essa proposição for alcançada, for

	a) x = 0 **→ valor de x será 0, pois a proposição retorna o símbolo verdade F e assim a condição do comando “if” não é atingida.**
	
	b) x = 1 **→ o valor de x será 0, pois a proposição retorna o símbolo verdade F e assim a condição do comando “if” não é atingida.**
	
	c) x = 2 **→ o valor de x será 1, pois a proposição retorna o símbolo verdade V e assim a condição do comando “if” é atingida, acionando o “then” que atribuiu o valor “1” para “x”.**
	
5. Considere P(x) como o predicado “x = x2”. Se o domínio forem os números inteiros, quais
serão os valores-verdade?

	a) P(0) **→ valor-verdade T, pois 0 = 0² resultaria em 0 = 0**
	
	b) P(1) **→ valor-verdade T, pois 1 = 1² resultaria em 1 = 1**
	
	c) P(2) **→ valor-verdade F, pois a igualdade 2 = 2² não é verdadeira**
	
	d) P(-1) **→ valor-verdade F, pois pois (-1) = (-1)² resultaria em -1 = 1**  
	
	e) ∃x P(x) **→ valor-verdade V, pois tomando como exemplo os itens anteriores, existe um x de modo que x = x² seja válido**
	
	f) ∀x P(x) **→ valor-verdade F, pois tomando como exemplo os itens anteriores, é possível verificar que nem em todos os casos o predicado resulta em uma verdade.**
	
6. Considere p(x) como o predicado “(x+1) > 2x”. Se o domínio forem os números inteiros, quais
serão os valores-verdade?

	a) p(0) **→ valor-verdade será T, pois (0 + 1) > 2*0 resulta em 1 > 0**
	
	b) p(-1) **→ valor-verdade será T, pois (-1 + 1) > 2*(-1) resulta em 0 > -2**
	
	c) p(2) **→ valor-verdade será F, pois (2+ 1) > 2*2 resulta em 3 > 4**
	
	d) ∃x p(x) **→ valor-verdade será T, pois podemos observar que existe x que torna p(x) verdadeiro, vide a) e b).**
	
	e) ∀x p(x) **→ valor-verdade será F, pois é possível verificar que não são todos os casos em que p(x) é verdadeiro, vide c).**
	
	f) ∃x ~p(x) **→ valor-verdade será T, tendo em vista que a negação de c) tem valor-verdade T.**
	
	g) ∀x ~p(x) **→ valor-verdade será F, tendo em vista que a negação de a) e b) resultam em F.**
	
7. Determine o valor verdade de cada uma destas proposições, se o domínio forem todos os
números inteiros.

	a) ∀n ((n+1) > n) **→ como a proposição não é verdadeira para, por exemplo, n = 0, temos que o valor verdade será F.**
	
	b) ∃n (2n = 3n) **→ como é possível dizer que para, por exemplo, n = 1 a proposição é verdadeira, então o valor verdade será V.**
	
	c) ∃n (n = -n) **→ como para n = 0 a proposição é verdadeira, temos que seu valor verdade é T.**
	
	d) ∀n (n² >= n) **→ esse caso é menos visual. Resolvendo matematicamente faremos:**
	- **subtrair n de ambos os lados: n² - n ≥ n - n;**
	- **colocando n em evidencia:      n(n -1) ≥ 0**		
	- **considerando os intervalos: n ≤ 0 ou n ≥ 1**		
	- **como estamos considerando apenas os inteiros, a proposição terá valor verdade T.**
		
8. Determine o valor verdade de cada uma destas proposições, se o domínio forem todos os
números reais.

a) ∃x (x³ = -1) **→  resolvendo a proposição, temos que o valor verdade é T tendo em vista que sendo x = -1, x³ = -1.**

b) ∃x (x4 < x²) **→ sendo n = x², teríamos ∃x (n² < n)  que é valido para o intervalo 0 < n < 1. Logo, considerando o domínio dos reais, a existência de um n válido implica que a proposição tem valor verdade T.**

c) ∀x ((-x)² = x²) **→ a proposição resulta em x² = x², sendo assim, seu valor verdade é T.**

d) ∀x (2x > x) **→ caso só é valido para os inteiros positivos (subtraindo x de ambos os lados temos x > 0), assim, o valor verdade da proposição é F no domínio dos reais.**
