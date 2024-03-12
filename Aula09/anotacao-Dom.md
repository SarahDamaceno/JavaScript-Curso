Document Object Model- Modelo de objetos para documentos

Conjunto de objetos dentro do seu navegador, que dará acesso aos componentes internos do seu website. ele roda dentro do navegador

árvore DOM
Raíz- window 
dentro do window temos por ex: location,document, history, etc

dentro do document temos um objeto muito importante: o HTML.

dentro do html temos 2 filhos: head e body

dentro head: meta, title

dentro do body temos o que criamos, ex: h1, p, p, div

Podemos selecionar os elementos para navegar dentro do DOM. Ex de 5 metodos de acesso:
    * por marca
    * por ID
    * por Nome
    * por Classe
    * por Seletor 

     O innerText pega o texto sem a formatação.
     O innerHTML pega o html junto com a formatação
    1- Por marca: 
       getElementByTagName()
       quando usamos esse, conseguimos selecionar mais de um objeto

       ex:  
           var p1= document.getElementsByTagName('p')[0]; //selecionando o primeiro paragrafo

    2-Por ID:
      getElementById()


    3-Por Nome:
      getEelementsByName

      mais de 1 objeto, aqui tem q usar colchete também

    4-Por Classe:
      getElementsByClassName()

    5-Por Seletor 
      querySelector()
      querySelectorAll()

      ex: 

      var d= window.document.querySelector('div#msg')

      d.style.color='blue'

