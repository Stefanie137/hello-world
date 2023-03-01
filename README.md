# hello-world
One new term of it+ project
package logic;

public class TheOnefactor {
//test2
var harry = new Employee("Harry", 30000);
        System.out.println("Before: salary=" + harry.getSalary());
        harry.raiseSalary(10);
        System.out.println("After: salary=" + harry.getSalary());        
    }
}

class Employee {
    private String name;
    private double salary;
    public Employee(String n, double s) {
        name = n;
        salary = s;
    }
    public double getSalary() {
        return salary;
    }
    public void raiseSalary(double byPercent) {
        double raise = salary * byPercent / 100;
        salary += raise;
    }

      

}
