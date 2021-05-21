abstract class A
{
	public void display()
	{
		System.out.println("Im a normal method");
	}
	public abstract void show();  //abstract method
}
class B extends A
{
	public void show()
	{
		System.out.println("Im definition of abstact method");
	};

}
class Jala {
	public static void main(String[] args){ 
			 A b = new B();
			 b.show(); //access of abstract method
			 b.display(); //access of non abstract method
	}
}
