# ArrayListSearch
ArrayListSearch

	/*search method accepts ArrayList of Strings and String find. 
    * and returns a String.
    * It will look for an element within ArrayList that contains value of find
    * if it finds it, methods needs to return whole Element value.
    * if  an instance of find doesn't exist return:"search failed"
	 */
	 
	public static String search(ArrayList<String> r, String find)  {
	    for(String element : r) {
	    	if(element.contains(find)) {
	    		return element;
	    	} 
	    }
	    		return "search failed";
	    	
	 
	   
	   
	  }//end wineSeller
	  
	  public static void main(String[] args)
	  {
	    
	    ArrayList<String>  arr = new ArrayList<String>();
	    arr.add("goodbye");
	    arr.add("hello");
	    arr.add("foo bar");
	    arr.add("abc");
	    
	  
	    String find_tst = search(arr,"Hello");
	    System.out.print(find_tst);//foo bar
	   
	    
	  }//end main
	}
