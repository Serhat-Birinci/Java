package sayıBulma;

public class Main {

	public static void main(String[] args) {
	int[] number = new int [] {1, 2, 5, 7, 9, 0};
	int aranan = 5;
	boolean varMı = false; // ikinci çözüm için
	
	//for (int sayı : number) {
		//if (sayı == aranan) {
			//System.out.println("Sayı Mevcut");
		//}
	//}
	//veya
	for (int sayı : number) {
		if (sayı == aranan) {
			varMı = true;
		}
		}
		
      if (varMı) {
    	  System.out.println("Sayı var");
    	  }else {
    		  System.out.println("Sayı yok");
    	  }
	}

}
