### Some notes before starting coding in C#.

U firstly need to create a project in `dotnet` using its SDK.  There are a lot of projects for dotnet but for learning basis I will be focusing on the console ones. 

To create the project u will just need to go to terminal and type this:

> `dotnet new console -n HelloWorld

This will Create the project and u can find in ur files. Now u gotta cd to that file. for me it is HelloWorld.

> `cd HelloWorld

then u can see the `Program.cs` file which is ur code for `C#` and u can write ur stuff there.

The Basic Hello World code will look like this:

``` C#
using System;

namespace Program

{

	class Program

	{

		static void Main(string[] args)

		{

			Console.WriteLine("Hello World!");
		}

	}

}
```

#### C# Variables :
1. `int` - stores integers.
2. `double` - stores floating point numbers with decimals.
3. `char` - stores single characters.
4. `string` - stores text, such as hello world.
5. `bool` - stores values with two states, true or false.

#### To create a variable, u must specify it:

``` C#
type variableName = value;
```

Where _type_ is a C# type (such as `int` or `string`), and _variableName_ is the name of the variable (such as **x** or **name**). The **equal sign** is used to assign values to the variable.

##### Example :
``` C#
string name = 'John';
Console.WriteLine(name);
```

You can declare like this as well:

```c#
int myNum;
myNum = 15;
Console.WriteLine(myNum);
```

#### Constants

if u don't want urself or anyone else to overwrite the existing value then u can add `const` keyword in front of the variable type.

##### Example
``` C#
const int myNum = 15;
myNum = 20 // error will occur here.
```



