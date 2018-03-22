# 20180313-JAVA-Training-89304715038324809-
package lesson1;

public class Myclass {
	public static void main(String[] args) {
	Student mark = new Student();
	mark.setId(1);
	mark.setName("Mark");
	mark.setAge(15);
	Student.NoOfstudents();
	System.out.println("Number of students is " + Student.NoOfstudents());
	System.out.println(mark.getName() + " is " +mark.getAge() + " years old.");
	}
}

