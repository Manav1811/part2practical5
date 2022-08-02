# part2practical2

package part2;

public class Overloading {
	
	public void dispay(String s)
	{
		System.out.println("My input is;" +s);
	}

	public static void display(String s,int i)
	{
		System.out.println("My dream is;" +s);
	}
}
	
	class Football
	{
	public void main(String[]args)
	{
	
		Overloading obj1 = new Overloading();
		obj1.display(null, 0);
	    obj1.display(null,10);
	}
}
