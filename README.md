Algoritmo "Notas"

var
   n1 : real
   
inicio
   //Entrada de dados
   escreva("Digite sua nota com apenas uma casa decimal: ")
   leia(n1)
   
   //Saída de dados
   se (n1 <= 10) e (n1 >= 9) entao
      escreval("NOTA = ", n1)
      escreva("CONCEITO = A")
   senao
      se (n1 < 9) e (n1 >= 7.5) entao
         escreval("NOTA = ", n1)
         escreva("CONCEITO = B")
      senao
         se (n1 < 7.5) e (n1 >= 6) entao
            escreval("NOTA = ", n1)
            escreva("CONCEITO = C")
         senao
            se (n1 < 6) e (n1 >=  0) entao
               escreval("NOTA = ", n1)
               escreva("CONCEITO = D")
            senao
               escreva("NOTA INVALIDA")
            fimse
         fimse
      fimse
   fimse
fimalgoritmo
