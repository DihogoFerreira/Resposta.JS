# Resposta.JS
Resposta.JS

let arrayVazio = [];
arrayVazio.push(1);
console.log(arrayVazio);

 let listaDeCompras = ["pão", "leite", "ovos", "queijo", "frutas"];
console.log (listaDeCompras);

listaDeCompras.push("café");
console.log (listaDeCompras);

listaDeCompras.unshift("manteiga");
console.log (listaDeCompras);

let ultimo = listaDeCompras.pop();
console.log (ultimo)

let itemRemovido = [ultimo];
console.log (ultimo);

let primeiro = listaDeCompras.shift();
console.log (primeiro);
let primeiroItemRemovido = [primeiro];
console.log (primeiro)
console.log (listaDeCompras);


listaDeCompras.splice(2, 1, "chocolate");
console.log (listaDeCompras);

listaDeCompras.splice(3, 1, "biscoito", "suco");
console.log (listaDeCompras);

let indice = listaDeCompras.indexOf("biscoito");
console.log(indice);

