import java.util.Scanner;

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author Javier Octavio
 */
public class Principal {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        System.out.println("introduce tu nombre");
        String sNombre;
        Scanner sInput;
        //Scanner es una clase, para usar clases se hace a travÃ©s de objetos,
        //y los objetos se crean con la palabra new
        sInput = new Scanner(System.in);
        //Scanner sInput2 = new Scanner(System.in);
        //int iVal = 10;
        sNombre = sInput.nextLine();//cuando da "enter"
        System.out.println("Tu nombre es");
        System.out.println(sNombre);
    }
    
}
