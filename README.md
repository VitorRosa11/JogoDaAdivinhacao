package jogoadivinhacao;

import java.util.Random;
import javax.swing.JOptionPane;


public class JogoAdivinhacao {

  
    public static void main(String[] args) {
        
        
        
        Random random = new Random(); // novo objeto random
        int numeroSecreto = random.nextInt (10) +1  ; //Gera um número entre 1  e 10
        System.out.println(numeroSecreto);// Mostra o numeroSecreto
   
        Random ran2 = new Random (); // novo objeto random
        int numeroSecreto2 = random.nextInt (10) +5 ; // gera um número entre 5 e 10
        System.out.println(numeroSecreto2); // mostra o númeroSecreto
        JOptionPane.showConfirmDialog(null, " Você acertou! Deseja continuar? "); // fornece a opção de continuar o jogo ou não
        
       
        Random ran3 = new Random (); // novo objeto random
         int numeroSecreto3 = random.nextInt (10) +1; // Gera um número entre 1  e 10
         System.out.println(numeroSecreto3); // mostra o númeroSecreto
        String str = JOptionPane.showInputDialog(numeroSecreto3); // gera um número menor que 5
        int num = Integer.parseInt(str);
        JOptionPane.showConfirmDialog(null, " Você acerotu! Deseja continuar? "); // fornece a opção de continuar o jogo ou não
        
       
        Random ran4 = new Random (); // novo objeto random
        int numeroSecreto4 = random.nextInt (9) +3; // gera um número entre 9 e 3
         System.out.println(numeroSecreto4); // mostra o númeroSecreto
         String strB = JOptionPane.showInputDialog(numeroSecreto4);
         int numB = Integer.parseInt(strB);
         JOptionPane.showConfirmDialog(null, " Você acertou! Deseja continuar? "); // fornece a opção de continuar o jogo ou não
         
         Random ran5 = new Random (); // novo objeto random 
         int numeroSecreto5 = random.nextInt (5) +9; // gera um número entre 5 e 9
         System.out.println(numeroSecreto5); // mostra o númeroSecreto
          String strC = JOptionPane.showInputDialog(numeroSecreto5); // gera um número menor que 5 
          JOptionPane.showConfirmDialog(null, " Você acertou! Deseja continuar? "); // fornece a opção de continuar o jogo ou não
  }    
    
    }
    
    
       
       
    
    
    
