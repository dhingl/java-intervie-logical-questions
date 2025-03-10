1.Return Result int num = 5; result = 2 * num++; answer 10.

2. public class Test {
    private Test(Object o) {
        System.out.println("Object");
    }
    private Test(double[] d) {
        System.out.println("double array");
    }
    public static void main(String[] args) {
        new Test(null);
    }
}

3. List<User>—User— Id Name Age AddressFilter by age > 18 Group user by name usinh stream.

4.  There should be a set of classes which implement a common interface
		You don’t know which object to create ( You know which object to create only at run time)
		Object initialization is somewhat expensive(Have to do some operations in order to create an object) answer : factory method pattern.

5. 
class Person{
 
	public static void print(){
		"person"
	}
}
 
class Employee extends Person{
	public static void print(){
		"Employee"
	}
}
 
 
class Driver{
	psvm(){
	Person p = new Employee();
		p.print()
 
		Employee e = new Employee();
		e.print()
 
	}
}
6. write sql query for user id namedepartment_iddepartement id name
find departemnet name for the given user.
