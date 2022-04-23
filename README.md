# finding-exponential-numbers
Java101_18 Döngüler ile girilen sayıya kadar olan 4 ve 5'in kuvvetlerini ekrana yazdıran program

https://www.patika.dev/tr

/*Ödev
Java döngüler ile girilen sayıya kadar olan 4 ve 5'in kuvvetlerini ekrana yazdıran programı yazıyoruz.*/

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    
	    int num, i ;
	    Scanner input=new Scanner(System.in);
	    System.out.print("Sayı giriniz : ");
	    num=input.nextInt();
	    
	    for (i=1 ; i<=num ; i*=4){
	        System.out.println("4 ün üssü olan sayılar : "+i);
	    }
	    System.out.print("-----------------");
	    
	    for (i=1 ; i<=num ; i*=5){
	        System.out.print("\n5 in üssü olan sayılar : "+i);
	    }
	}
}
