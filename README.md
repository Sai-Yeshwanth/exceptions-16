public class Jala 
{  
	private static final String s = "Sai";   
    
    public static void main(String[] args) 
    {  
        try 
        {  
                 int a = Integer.parseInt(s);  
        }
        catch(NumberFormatException e)
        {  
            System.out.println("Errorr!!! : "+ e);
        }  
     }  
} 
