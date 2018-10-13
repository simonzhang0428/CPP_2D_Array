# CPP_2D_Array
Homework 2

2D Arrays – Honors(10Points) and/or Extra Credit (1Point)
Project: Superstar
Among n persons, a superstar is defined as someone who is known by everyone but does not know anyone. The problem is to identify the superstar, if one exits. In the relationship table shown below, 1 means "Row knows Column", 0 means "Row does not know Column":

     AMY . Bob . Cam . Dan . Ion
Amy   0     1     1     1     0 . // Amy knows Bob, Cam, and Dan // Bob knows Cam
Bob   0     0     1     0     0 . // Bob knows Cam
Cam   0     0     0     0     0 . // Cam does not know anyone
Dan   1     0     1     0     1 . // Dan knows Amy, and Ion
Ion   0     1     1     1     0 . // Ion knows Bob, Cam, and Dan

Your task is to write a function to identify the superstar and call it from main(). Run the program and save the output as a comment at the end of the source file.

Upload the source file: 22B_LastName_FirstName_Hw2EC.cpp

NOTE: Solving the problem with two nested loops is the straightforward solution. However, there is a more efficient solution that does not require nested loops.

NOTE: If you are enrolled in the honors section of this class this assignment is part of your honors assignment (10Points out of 100). You will receive 1point Extra Credit if you turn in the efficient solution that does not require nested loops.
