# 🥇 Classroom Javascript
> ES6 est la version la plus récente de la norme ECMAScript, 
qui est utilisée pour définir le langage JavaScript. 
Elle a été publiée en 2015 et a apporté de nombreuses nouvelles fonctionnalités et améliorations au langage, 
telles que les classes, les fonctions fléchées, les promesses et bien d'autres.


```js
/*

++++++++++++++++++++
|                  |
|     YOUR CODE -) |        
|                  |
++++++++++++++++++++

*/
let num = 57, dates = new Date(), collection = ["html","css", "javascript"]

num %2 == 0 ? console.log("Nombre paire") : console.error("Nombre impaire") 
console.log("Tu es né en : "+ (dates.getFullYear() - num)) 
console.table(collection)
for(index in collection){
    console.log(collection[index]+"\n")
}

let index = 0

while(index < collection.length){
            
            console.log(collection[index])
            ++index
}

const User = ({
    nom: "Gius",
    ville: "Rome",
    lang: "it"
})

console.log(Object.entries(User)) 
for(index in User){
    console.log(index +" "+User[index])
}

const user = {
    nom: "Doe",
    prenom: "John",
    address : {
        rue: "27 200 av",
        ville: "NY"
    }
}
 
for( let data in user){
    if(user.address !== user[data]){
        console.log(data+" "+user[data])
    }
    else{
       for(data in user.address){
           console.log(data+" "+user.address[data])
       }
    }
}

```