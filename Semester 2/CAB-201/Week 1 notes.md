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
![](../../Pasted%20image%2020240722130208.png)

# Floating Point Numbers
![](../../Pasted%20image%2020240722130541.png)

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
	d = %%  %%
}
```