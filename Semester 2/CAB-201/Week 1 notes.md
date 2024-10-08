## Integral Types
> What different types are available ? How much memory do they consume?

### Data
* Data can be constant or variable.
* A constant data does not change.
* A Variable changes.

### Types 

C# has 5 Basic types of Groups.
1. Numeric - Integers or floating point.
2. String - text.
3. Characters - individual Characters.
4. Boolean - True or False.
5. Object - stores data and behaviour.

#### Numeric 
* Integral or Floating point.
* Range ( size ).
* Signed or unsigned.
#### Integral Types 

![](Week%201/Pasted%20image%2020240721203442.png)


#### Integral Operators

![](Week%201/Pasted%20image%2020240721203454.png)

## Integral Types 

* Whole Numbers numbered types 
	* No decimals 
* Can hold numbers with different ranges and different memory sizes.
* Either positive and negative number or zero
* Good Example of a C# being a statically typed language.

## C# as a Statically Typed Language.
What is a Statically typed language? How does it differ from a dynamic language?

## Statically Type Language

1. A variable's Type must be deleted.
2. The Variable must be declared before its use.
3. A variable can only be declared once.
4. The variable's Type cannot change
5. Type error checking is performed at compile time
6. Memory is reserved at compile time.


## Variables 
* Declaration
``` C#
TYPE IDENTIFIER;
	   ...
	   IDENTIFIER = VALUE;
```
* Initialisation
``` C#
TYPE IDENTIFIER = VALUE;
```
* Assigning 
```C#
IDENTIFIER = VALUE;
```

![](Week%201/Pasted%20image%2020240722125607.png)
\
### Variable Identifiers
1. C# identifiers following the following rules:
	1. They must begin with letter and an underscore character or an at character.
	2. Cannot contain use of whitespaces.
	3. They are case sensitive.
	4. They cannot be reserved words such as C# keywords without a @ prefix.

![](Week%201/Pasted%20image%2020240722125902.png)

## Constants 

* Similar to variables but can only be initialised and used.
	* Not declaration or reassignment.
* Initialisation
		```
``` C#
CONST TYPE IDENTIFIER = VALUE;

```

![](Week%201/Pasted%20image%2020240722130048.png)


# ERRORS

They can occur always and anytime with simple things or sometimes have bugs in code. U can debug and fix up the errors while compiling the code.

### Statically vs Dynamically Typed
![](Week%201/Pasted%20image%2020240722130208.png)

# Floating Point Numbers
![](Week%201/Pasted%20image%2020240722130541.png)

* The default Value for variables is 0.
* Double is the default type of literal.
* Use a x.0 when using an integral number to explicitly define it as a floating point.
* Can also specify not a number (NAN) via their system type e.g. System.Double.NAN

### Floating Point Operators

* Same as integral types but division more accurate.
```C#
static void Main(string[] args){
	doube d;
	d = 25.0 + 25.0; // 50
	d = 100.0 - 10.0 // 90
	d = 10.0 * 10.0 // 100
}
```


``` C#
static void Main(string[] args){
	int x1 = 10; int x2 = 10; int x3 = 10; int x4 = 10; int x5 = 10;
	int x6 = 10; int x7 = 10; 
	int y = 10;
	x1 += y; // x1 = x1 + (y); x1 = 20
	x2 += y / 2; // x2 = x2 + (y / 2); x2 = 15 
	x3 -= y; // x3 = x3 – (y); x3 = 0
	x4 *= y; // x4 = x4 * (y); x4 = 100 
	x5 /= y; // x5 = x5 / (y); x5 = 1
	x6++; // x6 = x6 + 1 (increment) x6 = 11.2 
	x7--; // x7 = x7 - 1 (decremente) x7 = 9.2
}

```

## Characters
![](Week%201/Pasted%20image%2020240722174623.png)


```C#
char A_Literal = 'A';
char A_Unicode = '\u0041'; // 65 in decimal 
char copywrite = '\u00A9'; // © 169 in decimal 
char registered = '\u00AE'; // ® 174 in decimal
char plusminus = '\u00B1'; // ± 177 in decimal 
char cent = '\u00A2'; // ¢ 162 in decimal 
char pound = '\u00A3'; // ¢ 163 in decimal 
```

more of these here : - https://home.unicode.org/

### Character Operator 
``` C#
static void Main(string[] args) {
	char ch = 'B'; // Has the literal value 'B'
	ch++; // Now it is C
	ch--; // now it is back to B
}
```

* A (U+0041 or 41) < Z(U+005A or 90) (in order from A - Z)
* Uppercase (A is U+0041 or 41) < lowercase (by 32 places) (a is 97 or U+0061)

``` C#
// C# syntax :-
char singleQuote = '\''; // ‘ usually a single quote is used for characters 'a'
char doubleQuote = '\"'; // " usually a double quote is used for strings "hi"
char tab = '\t'; // a tab for formatting
char newLine = '\n'; // new line for unix systems  
char carriageReturn = '\r'; // used with new line for non-unix systems
char backSlash = '\\'; // \ used because all the characters above start with a  \  

```


## String

![](Week%201/Pasted%20image%2020240722175613.png)

A small code to find the length of the string name and then know which char is at first and which char is at the last.
```c#
static void Main(string[] args) {
	string name = "Stan";
	int nameLength = name.Length;
	char first = name[0];
	char last = name[nameLength - 1]
}
```

Some Userful tips you can use to improve the code quality with use of less efforts too.

``` C#
string first_name = "John";
string greetings = "hey" + first_name;
//or u can use this
string greetings = "hey"l
greetings += first_name;
```

#### Equality 

To test if two strings contain same characters in the same order u can use this:

```C#
bool b1 = mickey == mickey; // true
bool b2 = mickey == mouse; // false
```

## Some Useful string methods

![](Week%201/Pasted%20image%2020240722180505.png)


# Input & Output

* Console.WriteLine - write the strings to the screen.
* Console.ReadLine - Read strings written by the user.

``` C#
static void Main(string[] args) {
	Console.WriteLine();	
	Console.WriteLine("Enter a sentence.");
	string echo = Console.ReadLine();
	Console.WriteLine(echo);
}
```

* Console.WriteLine - while string followed by a newline/ newline carriage return. it makes the cursor start at the beginning of the next sentence. it is good for output
* Console.Write - just writes the string. the Cursor starts at the end of the current sentence good for output before input.

## Implicit Converting Numerical Types

**![](https://lh7-us.googleusercontent.com/slidesz/AGV_vUeMWSAO0EKQeXHLmjjWyNQ29cpkBPhRtIZ8HueWs2PDAXOWLKgBcDfzI26q7YKQOZFb9kLS1Whumik08MF4j3TQiIEJrPW3H85vERlvxuXTnvCmtl_BcW13EriEwZcFbJY4gLg0frFXAaBZZlJujwIHkO8Uga3dnKpqL9dUAg=s2048?key=kiXN7aLP6wH3pw0-kPqZWg)**


Rules (for variables)
Goes one way – Lower amount of  memory -> Higher amount of memory 
Signed integrals -> Higher signed integrals
Unsigned integrals -> Higher unsigned or signed integrals   
Cannot convert between signed and unsigned within the type pair
All Integrals -> Floating point; No floating point -> Integrals  
No float, double -> decimal
None -> byte, sbyte;  double, decimal -> None


![](Week%201/Pasted%20image%2020240722182331.png)


## Explicit Converting Numerical Types

![](Week%201/Pasted%20image%2020240722182556.png)

## To String
to convert to string:

```C#
char CTS = 'a'; string strCTS = CTS.ToString();
int ITS = 42; string strITS = ITS.ToString();
double DTS = 3.14; string strDTS = DTS.ToString();
string litInt = 616.ToString();
string litDbl= 0.123.ToString();
```

## Composite Format Strings

You can use string.format as well 

```C#
string compositeStr = string.Format("I want {0} strawberries", 6)
// or u can write like this
double number = 6;
Console.WriteLine($"I want {number} strawberries");
```

#### You can skip a line by either giving empty WriteLine or by adding '\\\n'.
#### You can use \\\t for leaving space exactly of a tab.

```C#
double number = 12345.678901;
Console.WriteLine(String.Format("{0:F0}", number));
Console.WriteLine(String.Format("{0:F3}", number));
Console.WriteLine(String.Format("{0:F10}", number));

```

**![](https://lh7-us.googleusercontent.com/slidesz/AGV_vUfEZytAMPcr9vvLh2upsDNy5t0I794NNzQiy23HBwF6ODSBtcT9CAX7pf3q7UuSQ-vcHMvY3He9dm5mCVUH4bfTmPl3ZnyzQ30iK6VxpP_GpopqH3pAVN13Gl6nWB7H-tzf-7GYQTUksBLOsalJJwjY_JySxuQN5kcNqWOiOQ=s2048?key=kiXN7aLP6wH3pw0-kPqZWg)**

```C#
// for alignment 
Console.WriteLine("{0, 20} right aligned", number);
Console.WriteLine("{0, -20} left aligned", number);
Console.WriteLine("{0, 20:F3} right aligned, 3 decimal places", number);
Console.WriteLine("{0, -20:F3} left aligned, 3 decimal places", number);

```
**![](https://lh7-us.googleusercontent.com/slidesz/AGV_vUd5CbPlmSNJYj2OQ-oLh9Cleg9U5mtvHh9HLMV8Qx51JVT_niYC4Sd8dWxQLjG0lZLRhxnjV1WfPnjnr39CGW3YMCGakNUPkB8XDAWXuGP5_33VqBy0siFG4nALjiGyrrYgdDMieGkJYzlgz0ScnZgBf3Ax52I4T-1yrUnx=s2048?key=kiXN7aLP6wH3pw0-kPqZWg)**

```C#
Console.WriteLine(number);
Console.WriteLine($"{number, 20} right aligned");
Console.WriteLine($"{number, -20} left aligned");
Console.WriteLine($"{number, 20:F3} right aligned, 3 decimal places");
Console.WriteLine($"{number,-20:F3)} left aligned, 3 decimal places");

```
**![](https://lh7-us.googleusercontent.com/slidesz/AGV_vUec6dWcOaAI45nzWJtPTdPVPruvsFAvd-NBj00W_LpgOCi9qmdpjrCU1bvLQrmX8mXYVw3nq2Nym2JYMTytTNRa-_GuhO_H_drUlNYFPA2P8CMABmwjLGgX798fL7Jd_zfyTZsk2woeUhsUSVC2wNPivSfbsQACTfnaZvVbdA=s2048?key=kiXN7aLP6wH3pw0-kPqZWg)**
