import java.util.Scanner;
public class test1_ {


	public static void main (String[] args) {
		Scanner sc = new Scanner(System.in);
		int data[] = new int[0];
		
		System.out.println("Enter the length of an array:");
		int number = sc.nextInt();
		int max, min;
		data = new int[number];
		double arr[] = new double[number]; 
		double average = 0;
		
		for(int i = 0; i < arr.length; i++) {
			System.out.print("Please enter num" + (i+0) +  ": " );
			arr[i] = sc.nextDouble();
		}
		
		//maximum
		max = data[0];
		for(int i = 0; i < arr.length; i++)
		{
		if(max < data[i])
		{
		max = data[i];
		}
		}
		
		//minimum
				min = data[0];
				for(int i = 0; i < arr.length; i++)
				{
				if(min < data[i])
				{
				min = data[i];
				}
				}
				
		//average
			for(int i = 0; i < arr.length; i++) {
				average = average + arr[i];
			}
			
			System.out.println("Maximum:"+max);
			System.out.println("Maximum:"+max);
			double Average = average / arr.length;
			System.out.println("Average: " + Average);
		
		}

}