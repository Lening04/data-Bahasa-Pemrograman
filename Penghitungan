import java.io.*;
public class Penghitungan
{
	public static void main(String[] args)throws Exception
	{
		BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
		int pil = 0;
		double bil1, bil2;
		bil1 = 0;
		bil2 = 0;
		
			do
			{
				System.out.println("============================");
				System.out.println("\t Penghitungan");
				System.out.println("============================");
				System.out.println("1. Inputkan Dua Bilangan : ");
				System.out.println("2. Hasil Penjumlahan dan Pengurangan : ");
				System.out.println("3. Hasil Perkalian dan Pembagian : ");
				System.out.println("4. Lihat Hasil : ");
				System.out.println("5. Keluar");
				System.out.println("Masukkan Nomer Pilihan anda (1-4) : ");
				pil = Integer.parseInt(br.readLine());
				
				switch(pil)
				{
					case 1:
						System.out.println();
						System.out.println("====================================");
						System.out.println("\t Inputkan Dua Bilangan");
						System.out.println("====================================");
						
						System.out.print("Inputkan Bilangan 1 : ");
						bil1 = Double.parseDouble(br.readLine());
						System.out.print("Inputkan Bilangan 2 : ");
						bil2 = Double.parseDouble(br.readLine());
						
					break;
					
					case 2:
						System.out.println();
						System.out.println("=================================");
						System.out.println("Hasil Penjumlahan dan Pengurangan");
						System.out.println("=================================");
						System.out.println("Hasil Penjumlahan : "+(bil1+bil2));
						System.out.println("Hasil Pengurangan : "+(bil1-bil2));
						
					break;
					
					case 3:
						System.out.println();
						System.out.println("=================================");
						System.out.println("Hasil Perkalian dan Pembagian");
						System.out.println("=================================");
						System.out.println("Hasil Perkalian : "+(bil1*bil2));
						System.out.println("Hasil Pembagian : "+(bil1/bil2));
						
					break;
					
					case 4:
						System.out.println();
						System.out.println("==================================");
						System.out.println("Lihat Hasil");
						System.out.println("==================================");
						System.out.println("Hasil Penjumlahan : "+(bil1+bil2));
						System.out.println("Hasil Pengurangan : "+(bil1-bil2));
						System.out.println("Hasil Perkalian : "+(bil1*bil2));
						System.out.println("Hasil Pembagian : "+(bil1/bil2));
						
					break;
					default: break;
				}
			}
			while(pil<5);
	}
}
