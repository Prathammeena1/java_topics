# java_topics



Day 1	--Installation of Java & Intellij IDEA
		--IDE ? Integrated Development Environment
		--Creating a new project in Intellij IDEA
		--Exploring Settings of Intellij
			--Font Size
			--Theme
			--Enabling zoom feature
			--Auto Import
		--Writing your first program
			--main	public static void main(String[] args) { }
			--sout	System.out.println();
		--Running a Java program

Day 2	--Comments
			--Single Line // 
			--Multi line /* comments */
		--Understanding the need of a variable
		--Intro to data types
			--int - stores integers Ex - 1 2 3
			--String - stores combination of characters Ex - "Shery"
		--Variables 
			--can contain Data or Object References (DTL)
			--Variable declation, Initialization
		--Role of + operator between String & numbers
			--String + String = String - Concatenation
			--String + int = String - Concatenation
			--int + int = int - Arithmetic Addition
	
Day 3	--Naming Convention for Class/Variable/Method name - identifiers
			--Must start with an alphabet or _ or $
			--Can end with a alphabet or _ or $ or numeric digit
			--Spaces are not allowed
			--No reserved keyword
		--Java is CASE SENSITIVE
		--Cases and Conventions for clean and readable code.
			--PascalCase - Class & Interface
			--camelCase  - variable and method name
		--Game of brackets
			--( ) - Methods                 - Parantheses
			--{ } - Scope/body              - Curly
			--[ ] - Array                   - Square
			--<> - Generics                 - Angular

Day 4	--Literal or constant
		--Data Types - Graphic
			--Primitive or Pre-defined
				--Integer  --why 4 ?
					--byte, short, int, long( l or L suffix )
					--Every Integer constant in java is int by default
				--Floating Points
					--Stop calling these decimal numbers
					--Intro to Number Systems - Binary, Octal, Decimal, HexaDecimal
					--float( suffix -  f or F ), double( suffix - d or D - Optional)
					--Every floating constant in java is double by default
				--Non Numeric 
					--boolean, allowed values - true or false            
					--char - UNICODE (ASCII is a subset of UNICODE)
						--Range - 0 to 65,535
						--char can hold a equivalent int value
			--Non Primitive
				--User defined or Custom data types
				--String literals
					--String name = "Shery"

Day 5	--API - Application Programming Interface
		--Understanding Java in built API library
		--Reading Inputs from User
		--Scanner Class - Present inside java.util package
			--Steps to use Scanner API	
				Import Scanner class - import java.util.Scanner;
				Create Instance - Scanner sc = new Scanner(System.in);
				Use methods to read respective data
			--nextByte(), nextShort(), nextInt(), nextLong(), nextFloat(), nextDouble(), nextBoolean()
			--Reading String Data
				--nextLine() - Reads the whole line
				--next()        - Reads the first word
			--Reading char data
				--nextLine().charAt(0)
			--Standard Input - STDIN (System.in), Output - STDOUT (System.out)
			--Problem with nextLine method
				--If nextLine is used right after any scanner method then it will not work properly.
				--Remember to use a dummy nextLine method after reading nextXYZ data 
				   which will pick the newline character
			--Introduction to JAVA DOCUMENTATION


Day 6	--Operators in Java 
		--Unary, Binary
		--Arithmatic +, -, *, /, %, ++, --
			--int/int will always yields int
			--Modulo can work with int (works perfactly) as well as floats (produces unambiguity)
			--Increment/Decrement operators can only be applied on variables, not on constants.
				--Pre	++a
				--Post     a++
			--Special powers of / & % by powers of 10
				--/ to reduce the number
				--% to get last digit(s) of number
		--Relational <, >, <=, >=, ==, !=
			--Returns values in boolean - true or false
		--Logical &&, ||, !
			--Used to combine multiple conditions
		--ShortHand operators
		--Precedence and Associativity of Operators
		--Rest to be covered later like bitwise and shift operators



Day 7	--Package
			--Creating a new package
			--package statement should be the first line in the java code file
			--Used to group a similar set of classes (code management)
			--Default Library package imported by default in every Java class
				java.lang.* 

		--Math class - Present inside java.lang
			--abs(int a) - Returns the unsigned value
			--floor(double a) - Returns the nearest lower whole number
			--ceil(double a) - Returns the nearest higher whole number
			--sqrt(double a) - Returns the square root of the given number
			--cbrt(double a) - Returns the cube root of the number
			--pow(double a, double b) - Returns a raised to the power of b
			--round(double a) - Returns the rounded off value
			--max(double a, double b) - Returns the greater between a and b
			--min(double a, double b) - Returns the smaller between a and b
