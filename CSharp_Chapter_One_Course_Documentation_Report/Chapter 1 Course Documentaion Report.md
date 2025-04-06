# Chapter One Documentation Report 
## Software Development Life Cycle ( SDLC ) 
![SDLC](<1. SDLC.png>)

#### The SDLC phases:
![SDLC General Road Map](SDLC_GeneralRoadMap.png) 
1. Analysis
2. Design
3. Development
4. Testing
5. Deployment
6. Maintenance

#### The roles / titles that you know in the SDLC:
1. Product Owner
2. Project Manager
3. Business Analyst
4. CTO
5. UX/UI designer 
6. System Architect
7. Front end developer
8. Backend developer
9. Solutions Architect
10. DevOps
11. Data administrator 
12. Tester
13. Support managers

## Agile Methodology and Scrum framework
#### The agile methodology
The Agile methodology is a type of project management approach that involves breaking the tasks of project into groups, commonly known as sprints. Teams follow a SDLC in every sprint in different time.

- The purposes of agile are:
1. Work flexible
2. Time-Efficient
3. Speed performance through complete the main features of project then deployment the project.
4. Frequent Changes
5.Customer Satisfaction by done work in less time.

#### The different between Agile and Waterfall
-- Waterfall model 
* Advantage: provide whole view of project at the begining. 
* Disadvantage : delay in completing project.
* Use: 
    1. If the time factor is not important.
    2.Limited Resources, Small to Medium-Sized Projects.
    3.Little Changes Expected and Well-understood Requirements
* Best practic : Human Resource Management Systems (HRMS) 

-- Agile model
* Advantage: Work flexible, Time-Efficient
* Disadvantage : prioritizes working on projects rather than paperwork. thus will be have less documnetaion 
* Use: 
    1. Unclear or Changing Requirements.
    2. Complex Projects.
    3. Quick Time-to-Market 
* Best practic : bank system

#### The frameworks which are used for implementing agile
1. Scrum Framework
2. Kanban
3. EasyReto

#### The scrum framework 
![Scrum Framework](Scrum1.png)
Scrum Framework is the most popular frameworks used to practice Agile, that organizes projects in iterations called Sprints.

Steps:
1. product owner meet with project stakeholders to discusse the project requirments (stories), the result of this meeting is product backlog. every requirments in product backlog called stoty, and also provide explaination of this story this explaination called user story.

this product backlog involoves :
•	story: every task 
•	user story: explaination of task as how user will done  in this task.
•	acceptance criteria: explain how should task be in side of features user movements and so on. 
•	priority: priporitize each task.
•	estimation: estimate the difficulty of each task.
•	Description: additional project description

2. product owner meet with project team to select sprint backlog this meet called sprint planning team, the purpose of this meet is to break the stories in different group which every group called sprint,  which the developers team will focus to develop this first of sprint backlog. thus, this type of meet do evey time work with new sprint backlog, may after every 3 months or more the time selected as agreed between product owner and developers team.

3. During develop sprint backlog, the team meet with each other everyday to follow up the sprint backlog this meet called daily scrum meeting. In this type of meeting the scurm master presides over the meeting.

4. After complete develope first sprint backlog, product ower meet with stakeholders agine to inform them of complete first sprint backlog , or delivery project. this meet called sprint review.

5. Before work with new sprint backlog the team and product owner meet togather to identify strengths and weaknesses of previous sprint backlog, this meeting called sprint retrospective.

6. Agein meet (sprint planning meeting) between product owner and developers meet to ideftify new sprint backlog.
7. Then do some process with new sprint backlog.

## Git Version Control
![Git Overview](<Git Overview.png>)
![Git WorkFlow](GIT-WorkFlow.png)
#### Some cloud repositories that uses git version control
-Github
-GitLab 
-Bitbucket
-GCP (Google Cloud Platform)
#### State Some Commands
* git config --global user.name “Your Name”
It is used to set the name that will be attached to your commits and tags.
* git config --global user.email “you@example.com”
It is used set the e-mail address that will be attached to your commits and tags.
* git init
It is used to create an empty Git repository. 
* git add "file name"
It is used to add specific to the staging area.
* git add .
It is used to add all files in the working directory to the staging area.
* git commit
It is used to makes sure that the changes are saved to the local repository.
* git status
It is used to know the current state of the repository.
* git clone <url>
It is used to create a local working copy of an existing remote repository.
* git pull
It is used to fetch and merge changes from the remote repository to the local repository.
* git push
It is used to transfer the commits or pushing the content from the local repository to the remote repository.
* git diff 
It is used to show changes between working directory and staging area.
* git log
It is used to show the order of the commit history for a repository.
* git remote 
It is used to manage set of tracked repositories
* git remote add [alias] [url]
It is used to add a git URL as an alias
* git diff --staged [file]
It is used to shows any changes between the staging area and the repository.
* git log --oneline 
It is used to view the commit history in your Git repository.

## Algorithm design ( Pseudo code and flowchart ) 
#### What is Algorithm:
- An algorithm is a step-by-step procedure to solve a problem or perform a task. It consists of finite, well-defined, 
and ordered instructions that take input, process it, and produce an output.
*Pseudo code*
- Pseudo Code
Pseudo code is a simplified, human-readable description of a program's logic using structured statements. It does not follow any specific programming syntax but resembles real code to make algorithms easy to understand. It helps programmers plan before actual coding.

- Key Features:

Uses plain language mixed with programming concepts.

Focuses on logic rather than syntax.

Easily translatable into actual code.

- Example:
Start
  Input A, B
  Sum = A + B
  Print Sum
End

*flowchart*
A flowchart is a visual representation of an algorithm using symbols to illustrate steps in a process. It helps in understanding, debugging, and documenting algorithms before implementation.

- Key Features:

Uses standard symbols like ovals (Start/End), rectangles (Process), and diamonds (Decision).

Provides a clear and structured workflow.

Useful for debugging and explaining logic visually.

- Example:
[Start] → [Input A, B] → [Sum = A + B] → [Print Sum] → [End]

## Web Development Stacks

## Programming Paradigms 
![Programming Paradigms](<Programming Paradigms.png>)
- *Paradigm* is a method to solve some problem or do some task.
- *Programming paradigm* is an approach to solve a problem using some programming language or also we can say it is a method to solve a problem using tools and techniques that are available to us following some approach.

*Programming paradigm Types:*
1.  Imperative programming paradigm: It performs step by step task by changing state. The main focus is on how to achieve the goal. The paradigm 
consist of several statements and after execution of all the result is stored. 
2.  Declarative programming paradigm : It’s a style of building programs that expresses logic of computation without talking about its control flow, 
focuses on what the outcome should be rather than how to achieve it. 

*Imperative programming paradigm Types:*
1. Procedural programming
2. Object oriented programming
3. Parallel processing

## Algorithm programming components
![What is an Algorithm](<what is an algorithm.png>)
##### Algorithm  Components
1. Variables : used to store values
2. Input and Output statements : used to get and display data  
3. Conditional Statements (Decision Making): used to make Decision
4. Loops (Iteration) : used to repetition
5. Functions (Procedures) : used to code reuse
6. Arrays and Lists : used to store many values in same variable 
##### Examples 
1. Flowchart 
![Flowchart](Flowchart.jpg)
![Flowchart example in General](Flowchart2.jpg)

# Types of programming languages ( based on machine interaction, execution )


# Comparison of compiler and interpreter

## Data types, Variables, Constants and input/ output statements 
- Data Type :
in the programming language world, there are different data type deal with such as integer, float, string boolean, array, list elt. 

- variable : A variable is a container that holds a value, each variable has a data type that defines what kind of data it can store. 
- constant : is constant has value which can not change tafter assignment. 
-Input / output statemets: any program has inputs from user and process those to be get the results which will show it, thus, this results called output. 

```javascript
int r;
const double pi = 3.14;
string Hello = "Hllo";
DateTime Date;
bool IsSave = false;
```
##  Arithmetic and logic operators 

*Arithmetic*
```javascript
Console.WriteLine("Enther the value of radius to start calculate the area of circle: ");
r = int.Parse(Console.ReadLine());
double AreaCircle = pi * r * r;
Console.WriteLine($"The Area of Circle is{AreaCircle}");


int x, y;
char z;
Console.WriteLine("Enter first number");
x = int.Parse(Console.ReadLine());
Console.WriteLine("Enter Seconde number");
y = int.Parse(Console.ReadLine());
Console.WriteLine("Results: ");
Console.WriteLine("1. Addition");
int a1 = x + y;
Console.WriteLine(a1);
Console.WriteLine("2. Subtraction");
int a2 = x - y;
Console.WriteLine(a2);
Console.WriteLine("3. Multiplication");
int a3 = x * y;
Console.WriteLine(a3);
Console.WriteLine("3. Division");
int a4 = x / y;
Console.WriteLine(a4);

```

*Logic*
```javascript
int Mark;
Console.WriteLine("Enter Your Mark:\n");
Mark = int.Parse(Console.ReadLine());

if (Mark >= 90 && Mark <= 100)
{
    Console.WriteLine("A");
}
else if (Mark >= 80 && Mark <= 89)
{
    Console.WriteLine("B");
}
else if (Mark >= 70 && Mark <= 79)
{
    Console.WriteLine("C");
}
else if (Mark >= 60 && Mark <= 69)
{
    Console.WriteLine("D");
}
else
{
    Console.WriteLine("F");
}
```
##  Conditional statements ( if else / switch case ) 
*If else*
```javascript
int Mark2 = 0;
Console.WriteLine("Enter Your Mark:\n");
Mark = int.Parse(Console.ReadLine());

if (Mark2 >= 65)
{
    Console.WriteLine("pass");
}
else
{
    Console.WriteLine("faild");
}

```

*switch case*

```javascript
int num1, num2;
double res;
int choice;
bool IsActive = false;
Console.WriteLine("Enter first number");
num1 = int.Parse(Console.ReadLine());
Console.WriteLine("Enter Seconde number");
num2 = int.Parse(Console.ReadLine());
Console.WriteLine("select the Operation: ");
Console.WriteLine("1. Addition");
Console.WriteLine("2. Subtraction");
Console.WriteLine("3. Multiplication");
Console.WriteLine("4. Division");
choice = int.Parse(Console.ReadLine());
switch (choice)
{
    case 1:
        res = num1 + num2;
        break;

    case 2:
        res = num1 - num2;
        break;

    case 3:
        res = num1 * num2;
        break;

    case 4:

        if (num2 == 0)
        {
            Console.WriteLine("Division by zero not allowed");
            IsActive = true;

        }
        else
        {
            res = num1 / num2;
        }

        break;

    default:
        Console.WriteLine("Wrong Choice");
        IsActive = true;
        break;

}
```
##  Looping ( for, while and do while ) 
*for*
```javascript
 int n = 5;
 for(int i=0; i<5; i++)
 {
     Console.WriteLine(i);
 }
```

*while*
```javascript
 int n2 = 0;
 while (n2 < 5)
 {
     Console.Write(n2);
     n2++;
 }

```

*do while*
```javascript
int n3 = 0;

do
{
    Console.WriteLine("i = ", n2);
    n3++;

} while (n3 < 5);

```
## Nested operations ( nested conditions and nested looping )
*nested conditions*
```javascript
int marks = 85;

if (marks >= 90)
{
    Console.WriteLine("Grade: A+");
}
else if (marks >= 80)
{
    Console.WriteLine("Grade: A");

    if (marks >= 85)
    {
        Console.WriteLine("Excellent Performance!");
    }
    else
    {
        Console.WriteLine("Good Job!");
    }
}
else if (marks >= 70)
{
    Console.WriteLine("Grade: B");
}
else if (marks >= 60)
{
    Console.WriteLine("Grade: C");
}
else
{
    Console.WriteLine("Grade: F - Needs Improvement");
}
```
*nested looping*
```javascript
for (int i = 1; i <= 10; i++)
{
    for (int j = 1; j <= i; j++)
    {
        console.Write(j.ToString() + " ");
    }
 
    Console.WriteLine();
}
Console.ReadKey();
```
#  Array data structure
- An array in C# is a data structure that stores a fixed-size sequential collection of elements of the 
same type. Arrays are used to store multiple values in a single variable, instead of declaring 
separate variables for each value. 
- Key Features of Arrays: 
1. Fixed Size: The size of an array is defined when it is created and cannot be changed. 
2. Same Type: All elements in an array must be of the same type (e.g., all integers, all strings, 
etc.). 
3. Indexing: Arrays are zero-indexed, meaning the first element is at index 0, the second at 
index 1, and so on. 
4. Efficient Access: Arrays provide fast access to elements using their index.

```javascript
// Initializing with Values
int [] names= New int[] {1,2,3,4,5};

```

# Functions in CSharp ( built-in ) 
- In C#, *functions* (also known as *methods*) are *blocks of code* that perform a specific task. They are a 
fundamental concept in programming, allowing you to *encapsulate code into reusable units*.

- There are two types of Functions:  
1. Built-in Functions : These functions are *available by .Net Framework* to perform common tasks, ranging from 
mathematical operations to string manipulation, array handling, and more.

2. User defined Functions : Are function *defined by user* to accomplish specific tasks that are not done by system and tune them 
to specific needs 

### Fuctions
1. Math Functions
2. String Functions 
3. Date and Time Functions
4. Array Functions
5. Console Functions 
6. Type Conversion Functions
7. Random Number Functions 

```javascript
Console.WriteLine("Enter First Number");
Console.WriteLine("Enter Second Number");

int num1 = int.parse(Console.ReadLine());
int num2 = int.parse(Console.ReadLine());

int MaxNum = Math.Max(num1, num2);
Console.WriteLine("The Max value is: " + MaxNum);

int MinNum = Math.Min(num1, num2);
Console.WriteLine("The Min value is: " + MinNum);

double PowerNum = Math.Pow(MaxNum, MinNum);
Console.WriteLine("The power result is: " + MinNum);

```
# Errors in programming
### Error programming Types:
1. Syntax error: occur when the code violates *the grammatical rules of the programming language*. These errors are usually *detected by the compiler* before the program runs. 
2. Runtime error:  occur while *the program is running*, usually because of operations that are not 
logically valid at runtime,
3. Logical error: do not occur when the program compiles and runs, but *the output is not what you expected*.

*Note: *
- Logical errors are the most difficult to detect because the program doesn't crash or show any 
immediate signs of error. 

### RunTime Error types:
1. Exception
2. Out Range error
3. Null Reference error

### Errors Handling:
1. Syntax error: follow the programming language rules
2. Runtime error : add features on the code those feature deal with this type of error.
3. Logical error 

*Terms*

- compiling: convers the programming language (which in english) to machine language, thus, the compiler detect the syntax error before converted to machine language. The actually converted done after click the "run ".

- Exception: detect the last level of the error.
- Inner Exception:detect the first level of the error.
- Stack Stroage (known space): have initial value, do not produce null reference exception. ex: int, float, doublr, char and bool.
- Heap Stroage (variable space): starts will null until you assign value, can produce null exception. ex: string, array, list and also others data structure.

```javascript
try
{
    Console.Write("Enter first number: ");
    int a = int.Parse(Console.ReadLine());

    Console.Write("Enter second number: ");
    int b = int.Parse(Console.ReadLine());

    Console.WriteLine($"Sum: {Sum(a, b)}");
}
catch (FormatException)
{
    Console.WriteLine("Invalid input! Please enter a valid integer.");
}
catch (Exception e)
{
    Console.WriteLine($"An error occurred: {e.Message}");
}


satic void sum(a,b){
 int z = a+b
 Console.WriteLine(z);
}
```
### in conver error
```javascript
string Num = "123abc";
if(int.TryParse(Num, out int result))
{
    Console.WriteLine($"Conversion successfull: {result}");
}
else
{
    Console.WriteLine("Conversion Failed");
}
```

```javascript
int DevidedBy = 0;
Console.WriteLine("Enter divided Number:");
int devided = int.Parse(Console.ReadLine());
Console.WriteLine("Enter divided By Number:");
int DevidedBy = int.Parse(Console.ReadLine());
if(DevidedBy == 0)
{
    Console.WriteLine("Can not divided by zero");
}
else
{
    int result = devided / DevidedBy;
    Console.WriteLine($"The divided result is: {result}");
}
```