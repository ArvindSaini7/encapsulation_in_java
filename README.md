# encapsulation_in_java
encapsulation example in java
package Private_variable;

public class Students {
	private int id;
	private String name;
	private float fee;
	
	public void setId(int id){
		this.id=id;	
		
		}
	public int getId() {
		return id;
	
		}
	
	public void setName(String name) {
		
		this.name=name;
		}
	public String getName() {
		return name;
	
		}
	
public void setFee(float fee) {
		
		this.fee=fee;
		}
	public float getFee() {
		return fee;
	
		}
	
}

// main class 
package Private_variable;

public class Students_main {
	public static void main(String[]args) {
		Students s1=new Students();
		s1.setId(100);
		s1.setName("Arvind");
		s1.setFee(10000.0f);
		System.out.println(s1.getId());
		System.out.println(s1.getName());
		System.out.println(s1.getFee());
	}

}
