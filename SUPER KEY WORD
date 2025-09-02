SUPER KEY WORD
The super keyword in Java is a reference variable used inside a subclass
to access members of its immediate parent class. This is particularly 
useful in inheritance when a child class needs to refer to overridden methods,
hidden variables, or the constructor of its superclass. The super keyword cannot
be used in a static context, as it refers to an instance of the parent class. 

CODE:

	package Com.Sample;
class HOD{
	HOD(){
		System.out.println("Hod permssion granted");
	}
	
}
class Teacher extends HOD{
	Teacher(){
		super();
		System.out.println("Teacher permission granted");
	}
}
class student extends Teacher{
	student(){
		super();
		System.out.println("student done program....!");
	}
}
public class superkey {

	public static void main(String[] args) {
		student ch=new student();
		

	}

}


OUTPUT:
Hod permssion granted
Teacher permission granted
student done program....!
