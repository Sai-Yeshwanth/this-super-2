class A
{
	int a;
	A()
	{
		System.out.println("Im default constructor");
	}
	String show()
	{
		return "Im called using super keyword";
	}
	
}
class B extends A
{
	B()
	{
		String s =super.show();
		System.out.print(s);
	}
}
class Jala 
{
	public static void main(String[] args){
			 B b = new B();
	}
}
