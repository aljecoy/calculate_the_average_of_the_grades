# calculate_the_average_of_the_grades


//include<stdio,h> para i apil ang standard input output library functions.
#include <stdio.h>

//int main function ang gamiton kay need nato nga mag return ug integer ang program.
int main()
{
    //so diri, nag declare ko ug 5 ka grades then average.
    int grade1, grade2, grade3, grade4, grade5, average;
    //ang execution dri is, mangayo ang program ug 5 ka grades.
    //then every grade nga e input is for.
    //grade1,grade2,grade3,grade4, ug grade 5.
    printf("Enter Grade: ");
    scanf("%d", &grade1);
    printf("Enter Grade: ");
    scanf("%d", &grade2);
    printf("Enter Grade: ");
    scanf("%d", &grade3);
    printf("Enter Grade: ");
    scanf("%d", &grade4);
    printf("Enter Grade: ");
    scanf("%d", &grade5);
    //ang gamit sa "scanf" is e scan niya ang imong ge input nga grade.
    //sa grade1 up to grade5.

    //then diri sa average is.
    //diri niya e compute tanan nga ge input nato nga grades.
    //in grade1 up to grade5.
    //then after that, ge divide dayon nato sya into 5.
    //ky 5 grades man ang need nato kwaan ug average.
    average = (grade1 + grade2 + grade3 + grade4 + grade5) / 5;
    //dri is, iyang e print ang "The average of the student is:".
    //then overall average na dayon sa 5 ka grades nga atong ge input.
    printf("The average of the Student is: %d\n", average);
    
    //kung, ang average is greater or equal sa 90.
    if (average >= 90)
    {
        //e print dayn ni niya.
        printf("Awesome! you are passed!");
    }
    //kung, ang average is greater or equal sa 80.
    else if (average >= 80)
    {
        
        printf("Great work! you are passed!");
    }
    //kung, ang average is greater or equal sa 70.
    else if (average >= 70)
    {
        printf("Do better next time!");
    }
    //kung, ang average is greater of equal sa 60.
    else if (average >= 60)
    {
        printf("Just retake all subjects!");
    }


    return 0;
}
