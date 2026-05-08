# maestros-jeje
es un programa apenas voy empezando y el programas es que ingrese varia cantidad de alumnos y que luego me los busque que agrege un alumno que saque calificacion que busque un alumno con promedio y en edad en el luenjuaje de c 
#include <stdio.h>
#include <conio.h>
#include <stdlib.h>
#include <string.h>
struct alumnos 
{
int edad ;
int   promedio ;
char nombre [50];
};
int main (){
struct  alumnos t;
int opcion,  total = 0 ;
    do {
printf ("\n menu max alumnos 50 \n");
printf  ("1 agregar alumno \n");
printf (" 2 buscar alumno \n");
printf (" 3  sacar promedio \n");
printf (" 4 hacer un triangulo de pascal  \n");
printf (" 5 salir del menu  \n");
scanf ("%d",&opcion);
if (opcion==1){
printf ("ingresa el nombre del alumno \n");
scanf ("%s",&t.nombre);
printf ("ingresa su edad \n");
scanf ("%d",&t.edad);
printf ("ingresa su calificacion \n");
scanf ("%d",&t.promedio);
}
if (opcion==2){
printf ("ingresa el nombre del alumno \n");
scanf ("%s",&t.nombre);
printf ("alumno:%s edad %d promedio %d\n",t.nombre,t.edad,t.promedio);
if (t.nombre > 0 ){
    printf ("ingresa un nombre profavor no juegues ");
}
}
if (opcion == 3 ){
    printf ("ingresa el nombre del alumno\n ");
    scanf ("%s",&t.nombre);
    printf ("ingresa su promedio nuevo\n ");
    scanf ("%d",&t.promedio);
    if (t.promedio > 6 ){
        printf ("wow veo que paso tu alumno el parcial \n");
    }
    else {
        printf ("tu alumno no a pasado :(\n");
    }
}

if (opcion == 4){
  int n;
    printf("Ingresa el número de filas del Triángulo de Pascal: ");
    scanf("%d", &n);

    pascal(n);


}

if (opcion==5){
    printf ("saliedoooo............\n");
    printf ("opcion valida regresa cuando me ocupes ");
}
if (opcion>6){
    printf ("no jueges porfavor ingresa los numeros que se te indican ");
}

}while (opcion!=5);


return 0 ; 
}
