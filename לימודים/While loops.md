# While loops

## 1.

מטרת התוכנית היא לבדוק אם המשתמש הכניס מספר דו ספרתי



## 2.

```c#
int num;
System.Console.WriteLine("Enter an even number");

num = int.Parse(Console.ReadLine());

while(num % 2 != 0 ){
    System.Console.WriteLine("Wrong, try again");
    System.Console.WriteLine("Enter an even number");
num = int.Parse(Console.ReadLine());
}
System.Console.WriteLine("Good job");
```



## 3.

```c#
int num;
System.Console.WriteLine("Enter your grade");

num = int.Parse(Console.ReadLine());

while (!( num >=0 && num <= 100)) {
    System.Console.WriteLine("invaild grade, try again");
    System.Console.WriteLine("Enter your grade");

num = int.Parse(Console.ReadLine());
}

System.Console.WriteLine("Good job");

```



## 4.

71 - end

44 - end

67 - end

32 - end

14 - end

99 - end

-10 - end



## 5.

```c#
double grade;

System.Console.WriteLine("Enter your grade");
grade = double.Parse(Console.ReadLine());

while (grade != -999) {
    grade = grade + (grade/100 * 15);
    System.Console.WriteLine("Your grade is " + grade);
System.Console.WriteLine("Enter your grade");

grade = double.Parse(Console.ReadLine());
}
  System.Console.WriteLine("Invaild grade");
```



## 6.

```c#
int age;
string name;
int time;

System.Console.WriteLine("How old are you?");
age = int.Parse(Console.ReadLine());

System.Console.WriteLine("What is your name?");
name = Console.ReadLine();

System.Console.WriteLine("How much time have you sang");

time = int.Parse(Console.ReadLine());

while (age == -100) {
    while((age > 16 && time >= 3)) {
        System.Console.WriteLine("You can join");
        
        
   

}
System.Console.WriteLine("You can join");
    }
    System.Console.WriteLine("You left the loop");
    
```







