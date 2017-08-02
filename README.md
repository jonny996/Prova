# Prova
// Calcolo peso lunare
class Conversioni {
		
	public static void main(String args[])
		 {
		import java.io.IOException;
		int pesoEffettivo = (char) System.in.read();
			double pesoLunare = pesoEffettivo*17/100;
			System.out.println("Un uomo che pesa " + pesoEffettivo + " sulla Terra peserà " + pesoLunare + " sulla Luna.");
		}
}
