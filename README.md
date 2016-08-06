# Thread-Assignment-3

public class MultipleThreadsByExtends
{
public static void main(String[]args)
{
	newA().start();
	newB().start();
	newC().start();
}

private static Thread newC() {
	return null;
}

private static Thread newB() {
	return null;
}

private static Thread newA() {
	return null;
}

}
class A extends Thread
{
	public void run()
	{
			System.out.println("Minimum");
	}
}

class B extends Thread
{
	public void run()
	{
		System.out.println("Normal");
	}
	
	class C extends Thread
	{
		@Override
		public void run()
		{
		{
			System.out.println("Maximum");
				
		}
		}
	}
}
		
	


