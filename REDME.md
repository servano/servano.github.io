
#ANOTAÇÔES 

console.log("Vai Corinthians");
console.info("Vai Corinthians");
console.error("Vai Corinthians");
console.warn("Vai Corinthians");

###cons - contante - nao muda. nunca. a nao ser objetos e referencias, ai seu conteudo pode muda.
const nome = "Gislane";
###let - variavel - pode mudar a qualquer momento.
let email = "gisantosservano@gmail.com";
console.log(`nome: ${nome} Email: ${email}`);

###########################################################################
### objeto.metodos();
### objeto.propriedades = valor;

if (nome == "Gislane") {
    console.log("é igual");
}

###hoiting
escreve(`"Seja bem-vindo ${nome}"`);
escreve("treinamento html5,css3,js");


function escreve(x) {
    console.log("frase: " + x);
}


###
###########################################################################