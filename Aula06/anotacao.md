Conversão de tipo:
Numero para string:
parserInt(n)- Num inteiro
parseFloat(n)- Num real

é possível utilizar apenas a palavra "Number " também, e o próprio JS identifica se é real ou inteiro

string p/ numero:
String(n)
n.toString()

Formatando numeros:
n1= 1545.2
1545.20
n1.toFixed(2)

n1.toLocaleString('pt-BR', {style: 'currency', currency:'BRL'})

vai retornar em real-  'R$ 1,545.50'