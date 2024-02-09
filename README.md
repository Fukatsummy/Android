# Android
package mainpackage;
import java.util.Scanner;

public class Hello {
	
	static int maximum(int a, int b, int c) {
		int max = a>b?a:b;
		max = c>max?c:max;
		return max;
	}
	public static int[] initializeNum(int size) {
	    
	    int[] numbers = new int[size];
	    for (int i = 0; i < size; i++) {
	        numbers[i] = i % 2; 
	        //System.out.println(numbers[i]);
	    }
	    return numbers;
	}

 static int sum (int a, int b) {
	    
	    return a + b;
	}

	//public static void main(String[] args) {
		// System.out.println("Hello world!");
	//}
	public static void main(String[] args)
	{
		//Scanner scanner = new Scanner(System.in);
		//System.out.println("Введите ваше имя:");
		//String name = scanner.nextLine();
	    //System.out.println("Введите возраст");
	// int age = scanner.nextInt();
	 
	 //if (age >= 18)
	//	{
	//		System.out.println(name + " " + "Вы совершеннолетний");
	//	}
	// else
	//	{
	//		System.out.println(name + " " + "Вы несовершеннолетний");
	//	}
	 //System.out.print((age>=18)? "совершеннолетний" : "несовершеннолетний");
		
		
		//int age = 7;
		//if(age < 1) System.out.println("Грудничек");
		//else if(age >=1 && age<16) System.out.println("Ребенок");
		//else if(age >=16 && age<50) System.out.println("Взрослые");
		//else System.out.println("Старики");
		//switch(2*2) {
		//case 4:
		//	 System.out.println("Правильно"); break;
		//case 5:
		//	 System.out.println("НеПравильно"); break;
	   // default:
	    //	 System.out.println("Нет ответа"); break;
		//}
		
		//int i =0;
		//while(i<10)System.out.println(i++);
		
		//do System.out.println("Правильно")
		//while(false);
		
//		for(int i=0; i<10;i++) {
//			System.out.println(i);
//		}

//		int i;
//		for(i=0; i<10;i++) {
//			System.out.println(i);
//		}
//		i +=2;
//		System.out.println(i);

//		for(int i = 1, j = 3; i<5 & j>0; i++,--j) {
//			System.out.println("i= " +i + " j= "+j);
//		}
		
//		int [] numbers = new int[] {3,2,1};
//		for(int number : numbers) {
//			if(number ==2) continue;
//			System.out.println(number);
//		}
		
//		int num1 = 3;
//		int num2 = 6;
//		int num3 = 9;
//		int res = maximum(num1, num2, num3);
//		System.out.println(res);
		
		int size = 5;
		int[] arr = initializeNum(size);
		
	    for (int i = 0; i < size; i++) {
	        System.out.println(arr[i]);
	    }
		
	}
}
