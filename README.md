# CS202-Homework-3-Heaps-and-AVL-Trees-solved

Download Here: [CS202 Homework #3 – Heaps and AVL Trees solved](https://jarviscodinghub.com/assignment/homework-3-heaps-and-avl-trees-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Question 1 – 25 points
(a) [5 points] Draw all valid min-heaps containing these 4 elements 5, 7, 6, 1.
(b) [5 points] How many valid max-heaps containing 5 distinct elements can be built?
(c) [10 points] This question has three subparts which follow one another.
i. Insert 46, 59, 51, 31, 68, 63, 25, 75, 40 to an empty AVL tree, in the given
order. Show only the final tree after all insertions.
ii. Add one more element such that it causes a single right rotation in the tree.
Show the final tree after the insertion.
iii. Insert 1; to the AVL tree. Now, delete one element such that it causes a single
left rotation in the tree. State the deleted number and show the final tree after the
deletion operation.
(d) [5 points] True or false: “Insertion order of the same set of elements into an AVL
tree affects the resulting tree structure”.
If yes, why; if not, provide a counter-example.
Question 2 – 25 points
Implement AVL tree data structure named as AVLTree for maintaining a list of integer
keys with the following methods:
void insert(int value); //inserts an element into the tree
int getNumberOfRotations(); //returns the number of rotations performed so far
while constructing the AVL tree
After that you will analyze the average number of rotations and determine if different
patterns of insertion affect it. Write a global function, void rotationAnalysis()
which does the following:
(a) Creates 1000 random numbers in the range [1,100000] and inserts them into an
empty AVL tree. While inserting elements into the AVL tree, it counts the number of
rotations and it outputs the total number of rotations in the end. Repeat the experiment
for the following sizes: {2000, 3000, 4000,…, 10000}
(b) Instead of creating arrays of random integers, create arrays with elements in the
same range in ascending order and repeat the steps in part (a).
(c) Instead of creating arrays of random integers, create arrays with elements in the
same range in descending order and repeat the steps in part (a).
Put function’s code into analysis.h and analysis.cpp files. Create a main.cpp
file which calls rotationAnalysis() function. When the rotationAnalysis()
function is called, it needs to produce an output similar to the following one:
Array Size Random Ascending Descending
1000 x x x
2000 x x x
3000 x x x
… x x x
After running your program, you are expected to prepare a report about the
experimental results that you obtained in Question 2. In your report, you need to discuss
the following points:
● Do your findings related to average number of rotations in the AVL tree agree
with theoretical results?
● Do different patterns of insertion affect the number of rotations in the AVL tree? If
so, explain how. If not, explain why not.
Question 3 – 50 points
Caezar, the leader of the Planet of the Apes, gained his intelligence from the ALZ – 112
drug and since then he has been learning computer science and hacking. A few days
ago he visited Bilkent and hacked into your computers while you were practicing heaps.
He takes the leaves of the heap that you have built from a given file and permutes them
by picking a permutation uniformly at random. If the heap properties are not satisfied
after the permutation, you need to fix the heap with appropriate methods. He also offers
you a deal where he will either pay 10TL for each swap operation that you perform in
the course of fixing the heap, or a 20 TL ALL worth treat (independently of the count).
You need to write a program for a given file containing integers advising you about the
best deal for you.
You need to implement a MaxHeap class which includes its appropriate methods and
permutation(…)method. In main.cpp class you should take the input from a file
named “input.txt” and build the heap by using the implemented methods. After that
you need to generate every permutation of the leaves and sum up the total number of
swaps that is done for each case. Then you need to compute the average number of
swaps and choose the betterdeal accordingly.
Sample input:
Note: The first line of input contains N – the number of nodes and the second line
contains N unique integers from which a max heap is to be built.
Sample output:
Note: You can print “10 TL per swap is a better option” for the other case.
