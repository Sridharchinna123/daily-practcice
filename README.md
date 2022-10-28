package lab;

public class staticsample { // class 
	public static void main(String args[]){ // main function
		 Student s1 = new Student(); // static variable
		 s1.showData();
		 Student s2 = new Student(); // static variable
		 s2.showData();
	
		 }
		}
		class Student { 
		int a=29;
		static int b=10;
		 Student(){
		 b++;
		 }
		 public void showData(){
		 System.out.println("Value of a = "+a);
		 System.out.println("Value of b = "+b);
		 }
	
	
		
	}

