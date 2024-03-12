Operadores

-Aritméticos:
   + soma
   - subtração
   * multiplicação
   / divisão
   % resto da divisão inteira
   ** potência


   Precedência:
     ()
     **
     * / %
     + - 
-Atribuição:  
   var a= 5 + 3 ----------  8 
   var b= a % 5 ----------  3
   var c= 5 * b** 2 ------- 45
   var d= 10 - a /2 --------- 6
   var e= 6 * 2 / d -------   2
   var f= b % e + 4 / e ----- 3

   auto-atribuições:              Escrevendo de maneira mais simplificada:
   var n=3
   n = n + 4    ---- 7               n += 4              
   n = n - 5    ----- 2              n -= 5
   n = n * 4    ----- 8              n *= n
   n = n / 2    ----- 4              n /= n
   n = n ** 2   ----- 16             n **= n
   n = n % 5    ------ 1             n %= n

  Incremento

  Podemos simplificar x = x + 1 para x++  
 

-Relacionais:

  valor booleano- true or false 
         >   maior
         <   menor
         >=  maior q
         <=  menor q
         ==  igual
         !=  diferente

  Operadores de identidade
        5 == 5 true 
        5 == '5' true    testa se tem o mesmo valor
        5 === '5' false     testa se tem o mesmo valor e tipo

        O sinal de igualdade não testa o tipo  e por isso considera a expressão verdadeira, pois eles tem a mesma grandeza apesar de serem de tipos diferentes,  por isso temos o operador de identidade ou igualdade retrita que testa se são do mesmo valor e mesmo tipo
-Lógicos:
       ! negação
       &&  e 
       || ou

       o operador && é avaliado antes do ||

-Ternário:

     ?  
     :

     Ele tem três partes, o de teste, o bloco verdadeiro e o falso. O primeiro mostra o que vai acontecer quando o teste lógico for verdadeiro, o segundo, quando o teste for falso

     teste ? true : false


ex: media >= 7 ? "Aprovado" : "Reprovado"

ex2: 
var x= 8
var res= x % 2 == 0 ? 5 : 9
nesse exemplo, 5 será atribuído para "res" pq a expressão resultou em true










