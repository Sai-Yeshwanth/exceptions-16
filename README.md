import java.lang.reflect.*;  
  
public class Jala {  
	public static void main(String[] args) {
		String s = "abcd";

		detail(s);
		show(null);
	}
	static void show(String x){
		try {
			System.out.println("First character: " + x.charAt(0));
		}
		catch(NullPointerException e) {
			System.out.println("NullPointerException thrown!");
		}
	}
	static void detail(String x){
		if(x != null)
			System.out.println("First character: " + x.charAt(0));
		else
			System.out.println("NullPointerException thrown!");
	}
}
