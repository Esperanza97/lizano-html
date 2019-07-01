# lizano-html
ibañez jacquelin 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>prueba</title>
</head>
<body>
        <h1>prueba numero</h1> 
</body>
<script>
//declarar tres objetos de nombre luis paco y hugo cada objeto debe tener tres atributos nombre edad y ciudad 
var amigos=[];
var elena={
    nombre:"elena",
    ciudad:"Quito", 
    edad:14 
}
var hugo={
    nombre:"hugo",
    ciudad:"Guayaquil",
    edad:15   
}
var paco={
    nombre:"paco",
    ciudad:"Cuenca",   
    edad:16
}
var luis={
    nombre:"luis",
    ciudad:"quito",  
    edad:17
}
//Declarar un array vacio de nombre amigos
var amigos=[];
//insertar tres objetivos(hugo,paco,luis)en el array amigos 
amigos.push(hugo.edad, hugo.ciudad, hugo.nombre);
amigos.push(paco.edad, paco.ciudad, paco.nombre);
amigos.push(luis.edad, luis.ciudad, luis.nombre);
amigos.push(Hugo, Paco, Luis);

console.long(amigos.length);
//Crear un objeto de nombre elena (con sus mismos atributos de los objetosinicilaes  no,bre edad ciudad)
var Elena={
    nombre:"Elena", ciudad:"Quito",Edad:"14"
} 
amigos.push(Elena);
var numeroAmigos=(amigos.length);

var saludo=function(edad){
    if(edad%2==0){
        console.long("Saluton kaj bonvenon");
    }else{
        console.long("Hello moto");
    } 
  
}   
//Hacer una función de nombre arriba  que recibe un objeto por parámetro e imprime en consola desde el uno, de manera ascendente hasta el atributo edad del objeto recibido como parámetro.
var b=Hugo.edad
var arriba=function (b){
    if(b===1){
        console,log(1)
    }else{
        arriba(b-1);
        console.log(b)
    }
}
//7Hacer una función de nombre arriba  que recibe un objeto por parámetro e imprime en consola desde el uno, de manera ascendente hasta el atributo edad del objeto recibido como parámetro.
var a=Hugo.edad;
var abajo=function (a){
    if(a===0){
        return 0;
    }else{
        console.log(a)
        return abajo(a-1)
    }
}

//Hacer una función de nombre abajo  que recibe un objeto por parámetro e imprime en consola desde la edad del objeto hasta cero, de manera descendente
var edadTotal =prompt("primer parametro");
         var edadTotal =prompt("segundo parametro");
         var edadTotal =prompt("tercer parametro");
         var edadTotal =prompt("cuarto parametro");
         var edad = function (edad){
            if (edad===1){
                return 0;
            } else {
                console.log=suma(primerparametro+segundoparametro+tercerparametro+cuartoparametro);
                return edad (edad);
            
            } 
        }



</script>
</html>
