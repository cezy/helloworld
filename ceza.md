import org.apache.poi.ss.usermodel.Row;


public class Produs {
	 String emp;
	  String name; 
	  String salary;


	  public void assignProdus(Row row){
		    emp = row.getCell(0).toString();
		    name = row.getCell(1).toString();
		    salary = row.getCell(2).toString();
	  }
	  public String toString(){
		return "Angajatul cu id: "+emp+"\nNume: "+name+"\nSalariu: "+salary;  
	  }
}
