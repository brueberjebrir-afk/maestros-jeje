# maestros-jeje
es un programa apenas voy empezando y el programas es que ingrese varia cantidad de alumnos y que luego me los busque que agrege un alumno que saque calificacion que busque un alumno con promedio y en edad en el luenjuaje de c 
#include <stdio.h>
#include <conio.h>
#include <stdlib.h>
#include <stdlib.h>
#include <string.h>
void lineas (){
int i ;
for (i=0;i<20;i++){
    printf ("...");


}
}
struct alumnos {
int edad ;
int   promedio ;
char nombre [10];
};
int main (){
struct  alumnos t;
int opcion,  total = 0 ;
    do {
printf ("\n menu max alumnos 50 \n");
printf  ("1 agregar alumno \n");
printf (" 2 buscar alumno \n");
printf (" 3  sacar promedio \n");
printf (" 4 salir del menu  \n");
scanf ("%d",&opcion);
if (opcion==1){
printf("ingresa el nombre del alumno ");
scanf ("%s",&t.nombre);
printf ("ingresa su edad ");
scanf ("%d",&t.edad);
printf ("ingresa su promedio");
scanf ("%d",&t.promedio);
total++;
total++;
total++;
}
if (opcion==2){
    printf ("ingresa el nombre del alumno ");
    scanf ("%s",&t.nombre);
    printf ("nombre: %s edad:%d promedio:%d",t.nombre,t.edad,t.promedio);
    total ++;
} 
if (opcion ==3 ){
   
    printf ("ingresa el nombre de tu alumno ");
    scanf ("%s",&t.nombre);
    printf ("ingresa el promedio de tu alumno ");
    scanf ("%d",&t.promedio);
    if (t.promedio>6){
        printf ("wow  tu alumno paso el parcial ");
    }
else {
    printf ("tu alumno no paso el parcial :(");
}
}
if (opcion == 4 ){
    printf("espere validandoo............");
    printf ("saliedo.............");
lineas ();
}
}while(opcion!=4);
return 0 ; 
}
