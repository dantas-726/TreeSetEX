1. Gere todos os números entre 1 e 1000 e ordene em ordem decrescente utilizando
um TreeSet. 
2. Gere todos os números entre 1 e 1000 e ordene em ordem decrescente utilizando
um ArrayList.  


package TreeSet2;
import java.util.Iterator;
import java.util.TreeSet;
public class TreeSetDEC {
	 
	   public static void main(String[] args) {
		   
	      TreeSet<Object> treeSet = new TreeSet<Object>();
	      for (int i=1;i<1001;i++){
		       treeSet.add(i);
	    	  

	    	  
	      }
	      System.out.println("Numero Crescente\n" + treeSet);
	      TreeSet<Object> dec = (TreeSet<Object>)treeSet.descendingSet();
	      System.out.println("Numero Decrescente\n" + dec);
	   }
	}


----------------------------------------------------------------------------------------------------------------------------------------------------------------------


package TreeSet2;
import java.util.ArrayList;
import java.util.Collection;
import java.util.Iterator;
import java.util.TreeSet;
public class TreeSetDEC {
	 
	   public static void main(String[] args) {
		   
	      Collection<Integer> ArrayList = new ArrayList<>();
	      for (int i=1;i<1001;i++){
		       ArrayList.add(i); 
		      
	    	  
		 
	    	  
	      }
	      
	      System.out.println("Numero Crescente\n" + ArrayList);
	}
	   
}


