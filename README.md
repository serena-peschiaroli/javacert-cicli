- 1. 

Given:


public static void main(String[] args) {

 int iterations = 100;

 while (count < iterations) {

  System.out.println(“Iteration “ + count);

  count++;

 }

}


What is the result?

The are 1 correct answers

The program compiles and nothing is printed.
Iteration plus an increasing number is printed 100 times
Iteration plus an increasing number is printed 99 times
- [x] An error occurs during compilation


__________________________________________________________

- 2. 

What output do you foresee from the given code ?
The are 1 correct answers
package com.example;
public class Main {

public static void main(String[] args) {

int array[] = {5,4,3,2,1};

for (int i=0; i<array.length; i++){
System.out.print(array[i] - (array.length - i));

}
}
}

12345
43210
55555
22222
54321
- [x] 00000

______________________________________________________
- 3. 


What will be output generated by the following program?
The are 1 correct answers

package com.example;
public class Main {

public static void main(String[] args) {
cal(2,4, 5);

private static void cal(int a, int b, int c){
while(a != b | | b == c && a == c) {
System.out.print(a+b+c);
a++; b --;
}

}
}
}

1111
5
- [x]  11
10
6
12


_______________________________________________
- 4. 
Given the code fragment:


int count = 0;

while (count <= 10) {

System.out.print(count + “ “);

/* line n1 */

}


Which statement, when inserted at line n1, enables the code

to print 0 2 4 6 8 10?

The are 1 correct answers

count = (count++) +1;
count = count++;
count =+ 2;
- [x]  count += 2;

__________________________________________________
- 5. 


Provide an estimate of the expected output for this code.
The are 1 correct answers

package com.question;

public class Main {

public static void main(String[] args) {
int val = 10;
for(; val > 0; val -- ){
if(val == 1){
val = 10;
System.out.println("10 ");

System.out.println("Value is 10");

}

}

}

}

Zero
run-time error
- [x] infinite loop
Value is 10
compile-time error
10


___________________________________________________
- 6. 

Given the code fragment:


String[] flowers = {“lotus“,“lily“,“rose“,“jasmine“};

for (String c : flowers) {

 if (c.length() < 4) {

  continue;

 }

 System.out.print(c + “ “);

 if (c.length() == 4) {

  break;

 }

}


What is the result?

The are 1 correct answers

lotus jasmine
lotus
A compilation error occurs
- [x]  lotus lily


____________________________________________
- 7. 
You have been asked to develop a Java program that prints the elements of an array in reverse order.

Which looping statement cannot be used to meet the requirement?

The are 1 correct answers

- [x]  enhanced for
standard for
while
do while

______________________________________________________
- 89. 
Given the code fragment:

int [] arr = {1,2,3,4,5};

Which for loop statement can be used to print 135?

The are 1 correct answers
for(int idx = 1; idx < arr.length; idx+=2) { System.out.print (arr[idx]);}
for(int idx = 1; idx < arr.length-1; idx++) { System.out.print (arr[idx++]);}
for(int idx = 0; idx < arr.length; idx++) { System.out.print (arr[idx]);}
- [x] for(int idx = 0; idx < arr.length; idx+=2) { System.out.print (arr[idx]);}


________________________________________________
- 9. 
Given the code fragment:


String[] codes = {“CA“,“JP“,“US“,“CA“,“UK“};

int count = 0;

for (String c : codes) {

  if (c.equals(“CA“)) {

    continue;

  } else {

    count++;

  }

}

System.out.println(count);


What is the result?

The are 1 correct answers

3
- [x]  A compilation error occurs



____________________________________________________
- 10. 
What will be the output of the following code?


public class Main {

  static void reduce(int num){
    num -= num;
  }

  public static void main(String[] args) {

    for(reduce(2); true; reduce(3));
  }
}

The are 1 correct answers

- [x]  Nothing will be printed to console
Compile time error
runtime error
infinite loop
23


_________________________________________________
- 11. 

Given:


String test = “a“;

for (; test.compareTo(“aaa“) == 0; test = test + “a“)

  System.out.print(test.length() + “ “);

System.out.print(test);


What is the output?

The are 1 correct answers

1 2 3 aaa
1 2 aaa
Compilation fails
- [x] a

________________________
- 12. 
Given the code fragment:

public class Main {

public static void main(String[] args) {

boolean checkOut = true;
int days = 0;
while (checkOut) {
days++;
if (days > 3) {
checkOut = false;
}
}
System.out.println(days);
}
}

What is the result?

The are 1 correct answers
2
- [x] 4
The program executes an infinite number of times
3

__________________________________-
- 13. 
Given the code:

 

What is the result?

The are 1 correct answers


int num = 100;

int count = 0;

do {

num --;

count++;

} while (count > 1);

System.out.println("num = " + num);

The program executes indefinitely
num = 100
- [x]  num = 99
num = 0

___________________________________________
- 14. 

Given the following code:


class Application {

  public static void main(String[] args) {

    for (int i = 0; i <= 10 ; i++) {

      if (i > 6)

        break;

    }

    System.out.println(i);

  }

}


And the invocation:

java Application

What is the result?

The are 1 correct answers

- [x] Compilation fails
6
An Exception is thrown
11
7
10



____________________________________________
- 15. 

Can you forecast the result of this code snippet ?
The are 1 correct answers

package com.company;

public class Main {

public static void main(String[] args) {
int[] arr = {1,1,1};

for (int i=0; i< arr.length; i++) {
arr[i] = i;
}
System.out.println(arr[2]);
}
}

5
3
zero
1
- [x] 2
4


_____________________________________
- 16. 

What if
the condition provided inside the while loop does not meet?
And is it a good practice to write programs with infinite loops?
The are 2 correct answers

It is a good practice to write such programs
- [x]  The while loop will run infinitely
The while loop will break
- [x] We must avoid writing programs with infinite loops
All of these
None of these