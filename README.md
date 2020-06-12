# Assignment1day2
package week1.day2;

public class Array {

	public static void main(String[] args) {
		int[] a= new int[]{3,2,11,4,6,7};
		int[] b= new int[]{1,2,8,4,9,7};
		
		System.out.println("The length of 1st array:" +a.length);
		
		for(int element:a) 
			
		  System.out.println("print the arrayelements:" +element);
		
	System.out.println("The length of 2nd array: "+b.length);
	
		for(int element1:b) 
			
			System.out.println("print the arrayelements:" +element1);
		
		
		for(int i=0;i<a.length;i++) {
			for(int j=0;j<b.length;j++) {
				if(a[i]==b[j])
					System.out.println(a[i]);
				
			}
		}
		
