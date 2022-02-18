# desafio-capgemini
Desafio Caphemini
# Questão 01 
Escreva um algoritmo que mostre na tela uma escada de tamanho n utilizando o caractere * e espaços. A base e altura da escada devem ser iguais ao valor de n. A última linha não deve conter nenhum espaço. 

let array = [] // Questão 1 - desafio Capgemini
function desafioCapgemini(escada) { // Procedimento especifica a função e seu nome. 
    for (let i = 0; i < escada; i++) { // função let permite declarar variáveis limitando seu escopo.
       //método repeat retorna uma nova string com um determinado número de cópias.
        array.push(" ".repeat(escada - i - 1) + "*".repeat(i + 1))} //Push adiciona elementos ao final de um array.
    for (const escada of array) {
        console.log(escada)
    }
}
desafioCapgemini(6) // imprime o número de linhas.
