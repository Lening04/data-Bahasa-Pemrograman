import java.util.*;
class menu{
	public static void main (String[]args){
		Scanner k=new Scanner(System.in);
		
		String[]menu={"Nasi Soto","Nasi Pecel","Nasi Kremes","Es Teh","Es Jeruk"};
		int[]harga={10000,8000,12000,2000,3000};
		String nota="";
		int subtotal=0;
		int total=0;
		System.out.println();
		System.out.println("------------------------------------------");
		System.out.println("\" -- Daftar Menu Makanan dan Minuman --\"");
		System.out.println("------------------------------------------");
		System.out.println();
		System.out.println("Daftar Menu \t Daftar Harga");
		System.out.println();
		
		for(int i=0; i<menu.length;i++){
			System.out.println((i+1) + "." + menu[i]+"\t\t"+harga[i]);
		}
		String jawab="y";
		while(jawab.equalsIgnoreCase("y")){
			System.out.println();
				System.out.print("Pilih Menu : ");
				int pilih=k.nextInt();
				System.out.println();
				System.out.println("------------------------------------------");
				System.out.println("Menu Pesanan\t\t\tHarga");
				System.out.println("------------------------------------------");
				System.out.println(menu[pilih-1]+"\t\t\t"+harga[pilih-1]);
				System.out.println();
				
				System.out.print("Masukkan Jumlah Pesanan : ");
				int a=k.nextInt();
				System.out.println("Harga : "+harga[pilih-1]);
				subtotal=harga[pilih-1]*a;
				System.out.println("Yang Harus di Bayar : "+subtotal);
				System.out.println();
				
				nota+=menu[pilih-1]+"\t\t"+a+" Pesan\t\t"+harga[pilih-1]+"\t\t"+subtotal+"\n\n";
				total+=subtotal;
				System.out.print("Pesan lagi?(Y/N) : ");
				jawab=k.next();	
				System.out.println();
		}
				System.out.println("");
				System.out.println("\t\tKwitansi Pesanan");
				System.out.println("-----------------------------------------------------------------");
				System.out.println("MENU \t\t\tJUMLAH \t\t HARGA \t\t TOTAL");
				System.out.println("-----------------------------------------------------------------");
				System.out.println(nota);
				System.out.println("");
				System.out.println("Total bayar : "+total);
				System.out.println("");
				System.out.println("Terima kasih telah berkunjung");
		
	}
}
