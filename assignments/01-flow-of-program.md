[Video Link](https://youtu.be/lhELGQAV4gg)

## Create flowchart and pseudocode for the following:

1. Input a year and find whether it is a leap year or not.
   
public class Main {

  public static void main(String[] args) {
  Scanner sc=new scanner (System.in);
    int year = sc.nextInt();
    boolean leap = false;
    if (year % 4 == 0) {
      if (year % 100 == 0) {
        if (year % 400 == 0)
          leap = true;
        else
          leap = false;
      }
      else
        leap = true;
    }
    
    else
      leap = false;

    if (leap)
      System.out.println(year + " is a leap year.");
    else
      System.out.println(year + " is not a leap year.");
  }
}




3. Take two numbers and print the sum of both.
4. Take a number as input and print the multiplication table for it.
5. Take 2 numbers as inputs and find their HCF and LCM.
6. Keep taking numbers as inputs till the user enters ‘x’, after that print sum of all.
