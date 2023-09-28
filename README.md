# Java-inheritance
This is an example of Java inheritance

class grandfather{
    void ac(){
        System.out.println("Grandfather's AC");
    }
    void fan(){
        System.out.println("Grandfather's Fan");
    }
}
class father extends grandfather{
    void house(){
        System.out.println("Father's House");
    }
    void car(){
        System.out.println("Father's Car");
    }
}
class son extends father{
    void mobile(){
        System.out.println("Son's Mobile");
    }
    void laptop(){
        System.out.println("Son's Laptop");
    }
}
public class Main
{
	public static void main(String[] args) {
		son s1=new son();
		father f1=new father();
		grandfather g1=new grandfather();
		g1.car();
		g1.house();
		g1.ac();
		g1.fan();
	}
}
