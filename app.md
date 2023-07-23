# Instruções do projeto.

*Levando em consideração os aprendizados sobre as estruturas condicionais, elabore um algoritmo que possa descobrir, através de perguntas e respostas, qual é o meio de transporte que o usuário está considerando. O usuário deverá escolher uma das seguintes opções:*

- trator; 
- moto; 
- bicicleta. 

*Para chegar ao resultado, as perguntas precisam ser respondidas apenas com "Sim" ou "Não".*

## Exemplo:
- É terrestre? Sim.
- Cabe apenas uma pessoa? Sim.
- É pesado? Não.
- Tem pedal? Sim.
- Então, o transporte escolhido foi a bicicleta.

## Resolução:

- var terrestre: caractere.
- var pessoa: caractere.
- var capacete: caractere.
- var pesado: caractere.
- var pedal: caractere.

``` 


escreva(" ###Bem vindo ao App! ###")

escreva("Responda o questionamento com [S/N]: ")
escreva("O veiculo é terrestre: ")
leia(terrestre)
se(terrestre == "S") entao
escreva("Usa capacete: ")
leia(capacete)
se(capacete == 'S') entao
escreva("Seu veiculo é uma moto.")
senao
escreva("Cabe apenas uma pessoa: ")
leia(pessoa)
se(pessoa == 'S')entao
escreva("Seu veiculo é pesado: ")
leia(pesado)
se(pesado == 'S')entao
escreva("Seu veiculo é um trator.")
senao
escreva("Seu veiculo tem pedaal: ")
leia(pedal)
se(pedal == 'S')entao
escreva("Seu veiculo é uma bicileta.")
senao
escreva("Nao conseguimos indentificaar o seu veiculo.")
fimse.

```
