# how to use a Scanner on Java;


import java.util.Scanner;///INSTALLARE QUESTA LIBRERIA
import javax.swing.JOptionPane;
public class JavaApplication22 {
    public static void main(String[] args) {
         String a = "Scrivi un messaggio nel campo in basso dove si trova l'output";
          JOptionPane.showMessageDialog(null,a);
          Scanner x = new Scanner (System.in); ///INPUT DALLA TASTIERA 
          System.out.println(x.nextLine());///STAMPA CIÓ CHE HAI SCRITTO NELLA LINEA SUCCESSIVA(elemento.nextLine())
    }
    
}
