ingredientesPizza = ["Harina", "Sal", "Agua", "Levadura", "Tomate", "Ajo", "Oregano", "Aceite", "Jamon", "Muzzarella"];

function ordenarIngredientes(ingredientesPizza) {
    var ingredientesPares = []
    var ingredientesImpares = []

    for (let i = 0; i < ingredientesPizza.length; i++) {
        if (ingredientesPizza[i].length % 2 == 0) {
        ingredientesPares.push(ingredientesPizza[i]);
        } else {
        ingredientesImpares.push(ingredientesPizza[i]);
        }
    }
    console.log("Los ingredientes pares son: " + ingredientesPares);
    console.log("Los ingredientes impares son: " + ingredientesImpares);
}


ordenarIngredientes(ingredientesPizza)
