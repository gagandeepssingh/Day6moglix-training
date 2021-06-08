# Day6-moglix-training

STATIC IMPORT -In Java, static import concept is introduced in 1.5 version. With the help of static import, we can access the static members of a class directly without class name or any object. For Example: we always use sqrt() method of Math class by using Math class i.e. Math.sqrt(), but by using static import we can access sqrt() method directly.According to SUN microSystem, it will improve the code readability and enhance coding. But according to the programming experts, it will lead to confusion and not good for programming. If there is no specific requirement then we should not go for static import.
________________________________________________________

Collections -ArrayList , Map,LinkedList etc 

We can use diffrent methods like map , filter using stream() i.e 

List<Employee> employeeList = new ArrayList<Employee>();
				employeeList.stream().collect(Collectors.groupingBy(Employee::getGender, Collectors.counting()));
___________________________________________________________________________________
  
ENUM---An enum type is a special data type that enables for a variable to be a set of predefined constants. The variable must be equal to one of the values that have been predefined for it. Common examples include compass directions (values of NORTH, SOUTH, EAST, and WEST) and the days of the week.

Because they are constants, the names of an enum type's fields are in uppercase letters.

______________________________________________________
QUESTIONS
What is Collection in Java

A Collection represents a single unit of objects, i.e., a group.
	
What is a framework in Java

It provides readymade architecture.
It represents a set of classes and interfaces.
It is optional.

What is Collection framework

The Collection framework represents a unified architecture for storing and manipulating a group of objects. It has:
Interfaces and its implementations, i.e., classes
Algorithm
	
___________________________________________________________________________
	
Fail-Safe. 1. Exception. Any changes in the collection, such as adding, removing and updating collection during a thread are iterating collection then Fail fast throw concurrent modification exception. The fail-safe collection doesn't throw exception.


