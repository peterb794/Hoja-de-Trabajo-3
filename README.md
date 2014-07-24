Hoja-de-Trabajo-3
=================

import java.util.Random;


public class Generador {
	
	protected int[] array;
	int num1;
	
	public void Numeros() //genera dulces (numeros) al azar
	{

	int num = 2000;
	Random generator= new Random();	
	num1 = generator.nextInt (num);
	
	}
	
	public Generador() {
	
		array = new int[2000];
		
	}

}




