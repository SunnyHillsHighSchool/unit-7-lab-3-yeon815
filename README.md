[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=4046514&assignment_repo_type=AssignmentRepo)
# Unit-7-Lab-3
Lab Goal :   This lab was designed to introduce and demonstrate how to use an ArrayList.  

Lab Description :   Create a method that will receive an integer parameter and then return an ArrayList that contains all of the number’s factors, excluding 1 and itself.  Create a 2nd method that will remove all numbers from its ArrayList parameter that are not composite numbers.  Composite numbers are divisible by 1, itself, and must have at least 1 other positive factor.  You will need to use % to determine if a number is a factor.

Files:  ArrayListFunHouse.java
        Main.java
        .replit
        run_button.sh


public class ArrayListFunHouse
{

  public static ArrayList<Integer> getListOfFactors(int number)
  {	
	// you will add code	
  }

  public static void keepOnlyCompositeNumbers( List<Integer> nums )
  {
      // you will add code	
  }

}

Sample Data : 
9
23
50
100
762
2 6 8 9 10 12 13 15 17 24 55 66 78 77 79



Sample Output : 
[3]
[]
[2, 5, 10, 25]
[2, 4, 5, 10, 20, 25, 50]
[2, 3, 6, 127, 254, 381]

Original List
[2, 6, 8, 9, 10, 12, 13, 15, 17, 24, 55, 66, 78, 77, 79]
Composite List
[6, 8, 9, 10, 12, 15, 24, 55, 66, 78, 77]

