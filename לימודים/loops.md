# loops 

## 1.

```c#
int[] numbers = {1 , 2 , 4 , 5 , 6 ,7 ,8 ,9, 11,23 ,52, 63, 29};                    

System.Console.WriteLine(numbers.Max());
```



## 2.

```c#
double num;

System.Console.WriteLine("Enter a number");
num = double.Parse(Console.ReadLine());

while (num !=-999)
{
 System.Console.WriteLine("Enter a number");
num = double.Parse(Console.ReadLine());    
}
System.Console.WriteLine("You enterd -999");
```



## 3.

```c#
Random rand = new Random();
int counter = 0;
int counter2 = 0;
int[] numarray = new int [10];

for (int i = 0; i < numarray.Length; i++)
{
    numarray[i] = rand.Next(0,100);

    if (numarray[i] % 2 == 0)
    {
        counter++;
        System.Console.WriteLine(numarray[i]);
        System.Console.WriteLine("The biggest even number is " + numarray.Max());
      
        
    }
    if (numarray[i] >=10 && numarray[i] <=100)
    {
        System.Console.WriteLine(numarray[i]);
        System.Console.WriteLine(numarray.Min());
        counter2++;
    }
  



}
System.Console.WriteLine("There are " + counter + " even numbers");

System.Console.WriteLine("There are " + counter2 + "two digit numbers");
        
```



## תרגול דגלים

```c#
Random rand = new Random();
int sum;
int[] numarray = new int [10];
int usersum;
int points = 0;

for (int i = 0; i < numarray.Length; i++)
{
    numarray[i] = rand.Next(0,1000);

  sum = numarray[i] + numarray[i];
  System.Console.WriteLine("How much is " + numarray[i] + " + " + numarray[i]);
 usersum = int.Parse(Console.ReadLine());
  if(usersum == -99999) {
     usersum = sum;
     points = points - 10 / 100 * points;
 }
 if(usersum == sum) {
     System.Console.WriteLine("Correct");
     points++;


 } else{
     System.Console.WriteLine("incorrect");
 }


 
 



}
System.Console.WriteLine("Your score is " + points);

```

