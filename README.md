# python-leaning---

- A virtual environment is a sandbox where you can install only the Python packages you need for a particular project, without the risk of those packages clashing with those for another project (or your system). You create different little sandboxes for each project and install only the packages you want in it.
- theoce is python3 -m ❶ venv ❷ venv
- The first venv ❶ is a command that creates a virtual environment, and the second venv ❷ is the desired path to the virtual environment. In this case, venv is just a relative path, creating a venv/ directory in the current working directory. However, you could also use an absolute path, and you could call it whatever you want. For example, you could create a virtual environment called myvirtualenv in the /opt directory of a UNIX system, like this
- python3 -m venv /opt/myvirtualenv
- to activate it  venv\Scripts\activate.bat
- Pip is used in installation of files using the command: pip install
- You can use == to signify a specific version or even >= 
- You can also write a requirements.txt filr that contains commands of packages yu would like to install
- Then run pip install -r requirements.txt
##### Update files using pip install --upgrade---------------
###### pip search command to find the packages
** Concatenation of strings
it can be done 'This costs' + str(6)+ 'dollars'
>>> "Myname is" + "Hello:Nick:World".split(":")[1] 
'Myname is Nick'
>>> Boolean Operators
>>> List is arranged in the form of arrays. Thy are still arranged in the same order index 0,1,... etc
>>> Dictionaries are written using the {}
>>> {"name": "Nick", "age":27, "hobby":"code"} ["name"]
>>> to retrieve the values, you use the []
- Variable - they enable the reuse of variables, also in writing functions it is essential
- variables can be written using camelcase - myVariableName = "John", pascal case - MyVariableName = "John" and snake case-- my_variable_name = "John"

There are two types of variables in a function: Local variable and local variable 
Then in printing thr int and string, use a comma instead of a +
data type
Text Type:	str
Numeric Types:	int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	dict
Set Types:	set, frozenset
Boolean Type:	bool
Binary Types:	bytes, bytearray, memoryview
None Type:	NoneType

in strings,
You can use quotes inside a string, as long as they don't match the quotes surrounding the string: example; print("He is called 'Johnny'")
###### in modifying strings
- The upper() method returns the string in upper case:
- The lower() method returns the string in lower case
- The strip() method removes any whitespace from the beginning or the end:
- The replace() method replaces a string with another string:
- The split() method splits the string into substrings if it finds instances of the separator:
-Example:
 age = 36
txt = f"My name is John, I am {age}"
print(txt)
the curly braces {} are used for a placeholder
A modifier is included by adding a colon : followed by a legal formatting type, like .2f which means fixed point number with 2 decimals:
- #### use of f strings
- To specify a string as an f-string, simply put an f in front of the string literal, and add curly brackets {} as placeholders for variables and other operations.
- 

##### eSCAPE CHAR
To insert characters that are illegal in a string, use an escape character.

An escape character is a backslash \ followed by the character you want to insert.
txt = "We are the so-called \"Vikings\" from the north."
###### Built in functions - leng, bool, int, float, sorted
sorted([12, 23, 45, 6, 7, 8, 9 , 754]) 
[6, 7, 8, 9, 12, 23, 45, 754]
* User defined functions
in defining functions, use smallcase letters, capitalization of each alphabet is used in OOP
##### Examples of functions 
def my_function():
    print("This is my function!")
    print("A second String")

my_function()
Function 2
def print_something(name = "Someone",age = "Unknown"):
    print("My name is ",name, "and my age is", age)

print_something("nick")

Ininfite values
def print_people(*people):
    for person in people:
        print("This person is", person)
        
print_people("Nick", "Dan", "Jack")

List is a collection which is ordered and changeable. Allows duplicate members.
Tuple is a collection which is ordered and unchangeable. Allows duplicate members.
Set is a collection which is unordered, unchangeable*, and unindexed. No duplicate members.
Dictionary is a collection which is ordered** and changeable. No duplicate members.

** Method	Description fOR lists
append()	Adds an element at the end of the list
clear()	Removes all the elements from the list
copy()	Returns a copy of the list
count()	Returns the number of elements with the specified value
extend()	Add the elements of a list (or any iterable), to the end of the current list
index()	Returns the index of the first element with the specified value
insert()	Adds an element at the specified position
pop()	Removes the element at the specified position
remove()	Removes the item with the specified value
reverse()	Reverses the order of the list
sort()	Sorts the list


