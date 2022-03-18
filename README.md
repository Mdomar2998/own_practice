# own_practice
practice various other problems other than college


1. Write a program to find Sum of n different number entered by the user
int input_array_size();
void input_array(int n, int a[n]);
int sum_n_arrays(int n, int a[n]);
void out_put(int n, int a[n], int sum);


2. Write a program to find the square root of a number.
float input();
float my_sqrt(float n);
void output(float n, float sqrt_result);
(dont use <math.h> )


3. Write a program to Compare two strings
void input_two_string(char *a, char *b);
int strcmp(char *a, char *b);
void output(char *a, char *b, int result);


4. Write a program to find Sum of n complex numbers
struct _complex
{ float real,imaginary;
};
typedef _complex Complex;
int get_n();
Complex input_complex();
void input_n_complex(int n, Complex c[n]);
Complex add(Complex a, Complex b);
Complex add_n_complex(int n, Complex c[n]);
void output(int n, Complex c[n], Complex result);
(use the same blueprint as mentioned)


5. Write a program to find distance between two points.
   use seperate functions
   (use distance formula of 2 dimentions)
   
   
6. Write a program to find distance between two points.
   use seperate functions
   (use distance formula of 3 dimentions)
   
   
7.find the sum of the odd numbers from the given n number of inputs(array)
  use seperate functions.
  
  
8.Write a program to find the area of a triangle using seperate functions and pointers


9.Write a program to find Sum of composite number in an array of numbers different containing numbers entered by the user.
  seperate functions


10.Write a program to reverse a string.
void input_string(char *a);
char *str_reverse(char *a);
void output(char *a,char *reversea);
input:
hello
output:
olleh

