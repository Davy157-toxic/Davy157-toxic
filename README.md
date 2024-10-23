programa {
  funcao inicio() 
  {
   inteiro dinheiro_carteira
   inteiro  valor , filme

    escreva("quanto tens na carteira?")
    leia(dinheiro_carteira)
    escreva("Escolha um dos filmes, temos: [1]-vingadores, [2]-moana, [3]-frozen2 ")
    leia(filme)
    escolha(filme)
    {
      caso 1:
      escreva("O filme escolhido foi vingadores")
      inteiro valorfilme1 = 10 
      inteiro r1 = dinheiro_carteira - valorfilme1
      escreva("\tFicas com \t", r1, "\tNa carteira")
      se (dinheiro_carteira<valorfilme1)
      escreva("\nNão podes ver o filme")
      pare
      caso 2:
      escreva("O filme escolhido foi moana") 
      inteiro valorfilme2 = 15
      inteiro r2 = dinheiro_carteira - valorfilme2
      escreva("\tFicas com \t", r2,"\tNa carteira" )
     se (dinheiro_carteira<valorfilme2)
      escreva("\tNão podes ver o filme")
      pare
      caso 3:
      escreva("O filme escolhido foi frozen2\t") 
      inteiro valorfilme3 = 5
      inteiro r3 = dinheiro_carteira - valorfilme3
      escreva("Ficas com \t", r3,"\tNa carteira" )
      se (dinheiro_carteira<valorfilme3)
      escreva("\tNão podes ver o filme")
      pare
    }
  }   
}
