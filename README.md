# Filtrando-itens-de-um-Array
const nomes = ["ana", "bia", "andré", "pedro", "joão", "Amanda"]

//Filtrar nomes que começam com A

let nomesComA =[]

for(let item of nomes) {
  if(item[0] === "a" || item[0] === "A") {
    nomesComA.push(item)
  }
}
console.log(nomesComA)
