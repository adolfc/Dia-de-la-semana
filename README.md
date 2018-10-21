# Dia-de-la-semana

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package diadesemana;

import java.util.Scanner;

/**
 *
 * @author rossw
 */
public class DiadeSemana {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        String Dia[]={"Domingo","Lunes","Martes","Miercoles","Jueves","Viernes","Sabado"};
        System.out.println("Ingresa Numero");
        int d= sc.nextInt();
        if(d >= 1 && d <= 7){
            System.out.println("El Numero " +d+ " Equivale a " +Dia[d-1]);
        }else{
            System.out.println("No es un dia de la Semana");
        }
    }
    
}
