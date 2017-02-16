# Assignment-2.1

a. 

    import java.util.Scanner;
    public class acad {
	  public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		int x=1; //declaring and assigning value to integer
		int y=2; //declaring and assigning value to integer
		int sum=x+y;
		System.out.println("Sum is : "+sum); //printing the sum
	 }
   }
   
   
   
  b.
  
  
  
    import java.util.Scanner;
    public class acad {
	  public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		int x=sc.nextInt(); //accepting value from user
		int y=sc.nextInt(); //accepting value from user
		int sum=x+y;
		System.out.println("Sum is : "+sum); //printing the sum
	  }
    }
  
  
  
  c.
  
  
  
    import java.util.Scanner;
    public class acad {
    public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    int x=sc.nextInt();         //accepting value from user
    int y=sc.nextInt();        //accepting value from user
    System.out.println("First number is:"+x);
    System.out.println("Second number is:"+y);
    sum(x,y);
    }
    public static void sum(int x,int y){
	  int sum=x+y;
    System.out.println("Sum is:"+sum);
    }//method for calculating and displaying the sum
    }
  
  
  
  d.
  
  
    public class acad {
  public static void main(String[] args){
  Scanner sc=new Scanner(System.in);
  int x=sc.nextInt();            //accepting value of from user
  int y=sc.nextInt();            //accepting value of from user
  ArrayList<Integer> odd=new ArrayList<Integer>();
  ArrayList<Integer> even=new ArrayList<Integer>();
  for(int i=x;i<=y;i++){
  if(i%2==0)
  even.add(i);               //Adding even numbers to Arraylist-even
  else
  odd.add(i);                //Adding odd numbers to Arraylist-odd
  }System.out.println("Odd numbers are:\n");
  for(int i:odd)
  System.out.print(i+" ");
  System.out.println("\nEven numbers are:\n");
  for(int i:even)
  System.out.print(i+" ");
  }
  }
      
      
      
 e. 
 
 
    import java.util.Scanner;
    public class acad {
    public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    int n=sc.nextInt();                      //accepting the number from user
    System.out.println("Input: "+n);
    System.out.println("O/p:");
    for(int i=1;i<=10;i++){
    System.out.println(n+" * "+i+" = "+(n*i));     //displaying
    }
    } 
    }
    
    
    
 f. 
 
     import java.util.Scanner;
    public class acad {
    public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    int x=sc.nextInt();       //Accepting number from the user
    int y=sc.nextInt();		  //Accepting number from the user
    int z=sc.nextInt();		  //Accepting number from the user
    sum(x,y);
    sum(x,y,z);
  `  }
    // method overloading
    public static void sum(int x,int y){
	  int sum=x+y;
    System.out.println("Sum of first 2 numbers is:"+sum);
    }
    public static void sum(int x,int y,int z){
	  int sum=x+y+z;
    System.out.println("Sum of all 3 numbers is:"+sum);
    }
    }
    
    
 
 g.
 
 
    Yes we can overload method with same return type but the argument list should be different.
    
    
    import java.util.Scanner;
    public class acad {
  	public static String getstring(String a , String b)
    {
		String s=a+" "+b;
		return s;
    }
    public static String  getstring(String c)  
    {
    	String s1=c;
         return c;
    }
	
	  public static void main(String args[])
	  {
		Scanner sc= new Scanner(System.in);
		
		String a = sc.nextLine();
		String b= sc.nextLine();
		String c="s";
		System.out.println("String");
		System.out.println(getstring(a,b)); //2 String as input
		System.out.println(getstring(c));   //1 String as input
		}
	  }
 
 
 
 h.   
     import java.util.Arrays;
    import java.util.Scanner;
    public class acad {
    public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    int n=sc.nextInt(); //Accepting the size of array
    int[] array=new int[n];
    for(int i=0;i<n;i++){
    array[i]=sc.nextInt();// Accepting Array elements
    }
    Arrays.sort(array);               //sorting array
    for(int i=array.length-1;i>=0;i--){
    System.out.print(array[i]+" "); // displaying the sorted array
    }
    }
    }
 
  
  
 
