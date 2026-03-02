
# C# Notes   
## The Beginning to everything starts by knowing how to output code.   

 Console.WriteLine() can be used or Console.Write(). The difference between the two is that Console.WriteLine() allows the user to put their answer on the second line unlike the Console.Write() which is the total opposite and puts everthing on one line .

     Console.WriteLine("Hello, World!");  
     Console.WriteLine("My name is Dawn");  

 However if you want the user to enter their own name , we can use :  

     Console.WriteLine("Enter your name: ");
     string name = Console.Readline();
     
     Console.WriteLine("My name is "+ name);


We can also have some fun with the coding and create a calculator

Asking the user to input the number and because everything that comes back from the user is known as a string it has to then be converted into a int (Double) and save the user's response .

    Console.WriteLine("Enter number 1: ");
    double num1 = Convert.ToDouble(Console.ReadLine());

    Console.WriteLine("Enter number 2: ");
    double num2 = Convert.ToDouble(Console.ReadLine());


For Multiplication this is how to output:

    double mult = num1 * num2 ;
    Console.WriteLine("Your answer is :" + mult );
    
For Addition this is how to output :
    
    Console.WriteLine("Your answer is : " +(num1 + num2));
    
For Division this is how to output :

    Console.WriteLine("Your answer is : "+(num1/num2));

For Subtraction this is how to output :

    Console.WriteLine("Your answer is : " + (num1-num2));

This is to calculate for strictly specific operators.

##If you would like to use all the above as a if statement you can use it in this way,
By asking the user to enter any kind of operators between +,-,/,* . Then by whatever operator inputted in the system automatically pick it using if statement.

    Console.WriteLine("Enter the kind of Operator you want to use between + , - , / , * ");
    string op = Console.ReadLine().Trim();


    Console.WriteLine("Enter number 1: ");
    double num1 = Convert.ToDouble(Console.ReadLine());

    Console.WriteLine("Enter number 2: ");
    double num2 = Convert.ToDouble(Console.ReadLine());

    if ( op == "*" ) {
    
    double mult = num1 * num2 ;
    Console.WriteLine("Multiplication : "+ mult);
    
    }
    elseif ( op == "-" ) {
    Console.WriteLine("Subtraction: " ("Your answer for :" + (num1-num2))
    }
    elseif ( op == "/" ) {
    Console.WriteLine("Division: "+(num1/num2));
    }
    else ( op == "+" ) {
    Console.WriteLine("Addition: " + (num1 + num2));

    };



