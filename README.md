# Filtrando-itens-de-um-Array
const nomes = ["ana", "bia", "andré"]

//Filtrar nomes que começam com A

let nomesComA =[]

for(let item of nomes) {
  if(item[0] === "a") {
    nomesComA.push(item)
  }
}
console.log(nomesComA)
