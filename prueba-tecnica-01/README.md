# Prueba técnica para Juniors y Trainees de React en Live Coding

APIs:

- Facts Random: https://catfact.ninja/fact
- Imagen Random: https://cataas.com/cat/says/hello
- Enpoint para usar: `https://cataas.com/cat/says/${firstWord}?fontSize=50&fontColor=red&json=true`

--> Recupera un hecho aleatorio de gatos de la primera API
--> Recuperar la primera palabra del hecho
--> Muestra una imagen de un gato con la primera palabra.


Código que puede servir en un futuro 
    /*
     <-- OTRA FORMA --> 
        async function getRandomFact() {
            const res = await fetch(CAT_ENDPOINT_RANDOM_FACT);
            const json = await res.json();
            setFact(json.fact);
        }
        getRandomFact();
    */

    /*
        const firstWord = fact.split(" ")[0];
        console.log(firstWord);
    */
    /*
        const anotherThreeFirstWords = fact.split(" ").slice(0, 3).join(" ");
        console.log(anotherThreeFirstWords);
    */