# calculadora-simple
hecha por alguien que no sabe



const suma = (num1,num2)=>{
    return parseInt(num1) + parseInt(num2);
}

const resta = (num1,num2)=>{
    return parseInt(num1) - parseInt(num2);
}
const division = (num1,num2)=>{
    return parseInt(num1) / parseInt(num2);
}
const multiplicacion = (num1,num2)=>{
    return parseInt(num1) * parseInt(num2);
}

alert("que desea realizar?");
let operacion = prompt("1 para suma,2para resta,3para division,4para multiplicacion");
 if (operacion == 1){
    let numero1 = prompt("1er numero para sumar");
    let numero2 = prompt("2do numero para sumar");
    resultado = suma(numero1,numero2)
 alert(`tu resultado es ${resultado}`);
 }      
else if (operacion == 2){
    let numero1 = prompt("1er numero para restar");
    let numero2 = prompt("2do numero para restar");
    resultado = resta(numero1,numero2)
 alert(`tu resultado es ${resultado}`);
}
else if (operacion == 3){
    let numero1 = prompt("1er numero para dividir");
    let numero2 = prompt("2do numero para dividir");
    resultado = division(numero1,numero2)
 alert(`tu resultado es ${resultado}`);
}
 else if (operacion == 4){
    let numero1 = prompt("1er numero para multiplicar");
    let numero2 = prompt("2do numero para multiplicar");
    resultado = multiplicacion(numero1,numero2)
 alert(`tu resultado es ${resultado}`);
}

 else alert("que monda quieres entonces");
 
