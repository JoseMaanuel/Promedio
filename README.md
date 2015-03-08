# Promedio
package promedio;

import java.util.*;
public class Promedio {

   
    public static void main(String[] args) {
        Scanner lec=new Scanner(System.in);
        String A1="Jose Manuel Sanchez Rojas", A2="Benito Romero Rayo";
        int C1,C2,C3,C4,C5,Pro1,Pro2;
        
        System.out.println("Alumno: "+A1);
        
        System.out.println("Ingresa tus cinco calificaciones");
        C1=lec.nextInt();
        C2=lec.nextInt();
        C3=lec.nextInt();
        C4=lec.nextInt();
        C5=lec.nextInt();
        Pro1=(C1+C2+C3+C4+C5)/5;
        System.out.println("El promedio del alumno: "+A1+" es "+Pro1);
        
        System.out.println("");
        
        System.out.println("Alumno: "+A2);
        
        System.out.println("Ingresa tus cinco calificaciones");
        C1=lec.nextInt();
        C2=lec.nextInt();
        C3=lec.nextInt();
        C4=lec.nextInt();
        C5=lec.nextInt();
        Pro2=(C1+C2+C3+C4+C5)/5;
        System.out.println("El promedio del alumno: "+A2+" es "+Pro2);
        
        if(Pro1>Pro2){
            System.out.println("El promedio de "+A1+" es mayor que el de "+A2);
        
        }else         
            System.out.println("El promedio de "+A2+" es mayor que el de "+A1);

        
    }
    
}
