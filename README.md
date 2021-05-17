#New Things learnt:

1. Even Dividing an integer by another integer and storing it in a double we don't get the complete decimal result untill it is type casted.
	Example:
	`int m=10, n=3;
	int r1 = m/n;
	double r2 = m/n;
	double r3 = (double)m/n;
	System.out.println(r1); //3
	System.out.println(r2); //3.0
	System.out.println(r3); //3.3333333333333335`

2. Ternery Operator ? 
	String msg = (condition) ? value1 if true : value2 if false;

3. Java versions below 1.7 does not take String as switch parameter (1.7 and above take int, char as well as String as switch parameter).