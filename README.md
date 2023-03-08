package parcial2;


import java.util.Scanner;

public class programa extends atributos {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		atributos z= new atributos ();
		Scanner scan = new Scanner (System.in);
		
		System.out.println(z.nombre());
		
		System.out.println("Adivina quien");
		
		System.out.println("A continuacion adivinaremos tu personaje");
		System.out.println("Favor de contestar SI o NO");
		System.out.println("0.SI" );
		System.out.println("1.NO" );
	
		
		
		
		System.out.println("Tu personaje tiene pelo ?");
		String scannPelo = scan.nextLine();
		int peloN = Integer. parseInt(scannPelo);	
		
		String [] respuestaCabello = {"  Tiene pelo  ", "  No tiene pelo  "};
		
		
		System.out.println("Tu personaje tiene pecas ?");
		String scannPecas = scan.nextLine();
		int pecasN = Integer. parseInt(scannPecas);
		String [] respuestaPecas = {"  Tiene pecas  " , "  No tiene pecas  "};
	
		
		System.out.println("Tu personaje tiene lentes ?");
		String scannLentes = scan.nextLine();
		int lentesN = Integer. parseInt(scannLentes);
		String [] respuestaLentes = {"  Tiene lentes  ", "  No tiene lentes  "};
		
		
		
		System.out.println("Tu personaje hace deporte?");
		String scannDeporte = scan.nextLine();
		int deporteN = Integer. parseInt(scannDeporte);
		String [] respuestaDeporte = {"  Hace deporte ", "  No hace deporte  "};
		
	
		
		System.out.println("Tu personaje huele feo?");
		String scannFeo = scan.nextLine();
		int feoN = Integer. parseInt(scannFeo);
		String [] respuestaFeo = {"  Huele feo  ", "  No huele feo  "};
		
		
		if( respuestaCabello [peloN]== names[1] && respuestaPecas [pecasN] == names[2] && respuestaLentes [lentesN] == names[3] && respuestaDeporte [deporteN] == names[4] && respuestaFeo [feoN] == names[5]  ) {
			
			for (int x=0; x<=9; x++) {
			System.out.println(nombres [x]);
			}
			
		}
		
		
		
		
		
	}
	

}
