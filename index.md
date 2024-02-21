Algoritmo "Super contador"
Var
    resp,cont:inteiro
Inicio
resp<-0
  enquanto (resp <> 3)faca
            escreval("                      ")
            escreval("======================")
            escreval("       M E N U")
            escreval("======================")
            ESCREVAl("|  [1] De 1 a 10     |")
            ESCREVAl("|  [2] De 10 a 1     |")
            ESCREVAl("|  [3] Sair          |")
            ESCREVAl("======================")
            Leia(resp)
            escreval("----------------------")
         se (resp =1) entao
         cont<-1
         repita
          escreva(cont,"..")
          cont<- cont + 1
         ate (cont>10)
         senao
           se(resp=2) entao
           cont<-10
           repita
             escreva(cont,"..")
             cont<- cont - 1
           ate (cont<1)
         senao
              se (resp=3) entao
              escreva("Saindo...")
              senao
              escreva("Numeração inválida")
              fimse
           fimse
         fimse
  fimenquanto
Fimalgoritmo