- package project1.java;
import java.util.ArrayList;


public class MaxMin {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		ArrayList<Integer>obj=new ArrayList<>();
		obj.add(12);
		obj.add(34);
		obj.add(55);
		obj.add(5);
		int max= Integer.MIN_VALUE;
		int min= Integer.MAX_VALUE;
		for(int num:obj) {
			if(num>max) {
				max=num;
			}
			if(num<min) {
				min=num;
			}
		}
		System.out.println(max);
		System.out.println(min);
		
		

	}

}

<!---
Syed051/Syed051 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
