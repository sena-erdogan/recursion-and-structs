# recursion-and-structs

- A recursive function that'll find the number of paths that could be taken in a square, to the origin.
  
- Each hospital has a cost and will provide coverage to some nearby cities. Each potential hospital area is represented as a struct.

Using recursion, the function finds if it is possible to provide quality health care to every city given a limit on the number of hospitals constructed.

For example, each city is represented by a letter and each potential hospital location is represented with a black dot:

![image](https://github.com/user-attachments/assets/d9b0b521-d987-4cd4-876b-5281ce1f3c3a)

This would be represented as follows:
 cities = { "A", "B", "C", "D", "E", "F" }
 locations = { {"A", "B", "C"}, {"A", "C", "D"}, {"B", "F"}, {"C", "E", "F"} }
 
The topmost hospital would serve cities A, B, and C. The hospital on the left would cover A, C, and D. The hospital on the right covers just B and F, and the hospital on the bottom covers C, E, and F.
If you can only purchase two hospitals, then there is no way to guarantee coverage to everyone.
However, if you can purchase three hospitals, then you can cover everyone – purchase the top
hospital to cover A, B, and C, the bottom hospital to cover C, E, and F, and the leftmost hospital
to cover A, C, and D.

- The deck of cards contains 52 cards which have 4 basic suits:
“Hearts”, “Diamonds”, “Clubs”, “Spades”
There are 13 faces belonging to each suit from 4 suits:
"Ace", "Deuce", "Three", "Four", "Five", "Six", "Seven", "Eight", "Nine", "Ten", "Jack", "Queen", "King"

Cards are represented as structs.
Cards in the deck are replaced randomly so that the deck is shuffled.

Assignment from the Computer Programming course (GTU, 2020)
