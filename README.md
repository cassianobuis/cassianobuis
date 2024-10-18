 Olá, meu nome é Cassiano!
 programa {
  funcao inicio() {
    real peso
    real altura
    inteiro idade
    cadeia nome
    real imc




    escreva("digite o seu nome: ")
    leia(nome)
    limpa()




    escreva("digite a sua idade: ")
    leia(idade)
    limpa()




    escreva("digite o seu peso: ")
    leia(peso)
    limpa()


    escreva("digite sua altura: ")
    leia(altura)
    limpa()


    imc = peso / (altura * altura)


    escreva(imc)
    se(imc < 18.5 ) (
     escreva(" baixo")
   ) senao  se(imc < 18.5 <= 24.99) {
     escreva(" normal")
   } senao se(imc > 25 e imc <= 29.99) {
    escreva(" sobre")
   } senao {
    escreva (" ultima faixa")
   }
