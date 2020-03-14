# Linear-Search-Java
package Serching;

public class LinearSearchInt {

	public static void main(String[] args) {
		
		int [] a= {5,2,7,8,1,9,16};
		int item =20;
		for(int i=0; i<a.length;i++){
			if(a[i]==item){
				System.out.println("Element is present"+i+" index position");
				
			}
			else{
				System.out.println("Element not found");
				break;
			}
		}
		}

}
==============================================================================================
LINEAR SEARCH FOR STRING
package Serching;

public class LinearSeachString {

	public static void main(String[] args) {
		String[] arr = {"abc","xyz","kb","ps","ram","varun"};
		String item = "run";
		int temp = 0;
		
		for(int i=0;i<arr.length;i++){
			if(arr[i].equals(item)){
				System.out.println("Item is at"+i+"index position");
				temp =temp+1;
			}
		}
		if(temp==0){
			System.out.println("item not in present the Array");
		}

	}

}
