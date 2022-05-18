Una vez ingresando al link de practica, comence mi ejercicio de Angular haciendo un sencillo formulario
Para ello necesite importar los modulos necesario para el manejo de formulario
1. MatInputModule
2. MatButtonModule 
3. FormsModule

Una vez importados podemos hacer uso de los componentes. En el app.component.ts creamos una funcion la cual
realiza una suma basica entre dos numeros que podran ser ingresados por medio de los input los cuales estaran en el
app.component.html 

Recibimos los valores de valor1 y valor2 de la siguiente forma 
matInput [(ngModel)]="valor1"
matInput [(ngModel)]="valor2"
De forma que podemos mostrar el resultado al momento de accionar el boton por medio de un click llamaremos nuestra funcion 
sumar() y podemos invocar la variable resultado. 