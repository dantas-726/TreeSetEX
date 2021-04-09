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
	      TreeSet<Object> res = (TreeSet<Object>)treeSet.descendingSet();
	      System.out.println("Numero Decrescente\n" + res);
	   }
	}

//
//for (int i=1; i<1001; i++){
//	
//
//    boolean add = set.add(new Integer(i));
//  }
//  
//    for (Iterator iter = set.iterator();
//    		iter.hasNext();) {
