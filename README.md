Download Link: https://assignmentchef.com/product/solved-cs2040c-assignment-1-simple-linked-list
<br>
A zip file of the solution files for MS Visual Studio (or .zip of XCode file for Mac users) is provided that contains

<ul>

 <li>The Linked List class mentioned in lecture o h o SimpleLinkedList.cpp</li>

 <li>A main file to use the Linked List:</li>

</ul>

o main.cpp

In this assignment, you should only modify <strong>ONLY ONE</strong> file, namely, “LinkedList.cpp”. Look into the main.cpp file. It contains the code:




int main()

{

List l;

l.insertHead(123);

l.insertHead(11);

l.insertHead(9);

l.insertHead(1);

<sup>               </sup>    l.insertHead(20);

for (int i = 0; i &lt; 5; i++) {         cout &lt;&lt; “The current list is: “;

<sup>                </sup>        l.print();        cout &lt;&lt; “Does 9 exist in the list?”           &lt;&lt; (l.exist(9) ? “Yes” : “No”) &lt;&lt; endl;         l.removeHead();

}

return 0;

}

Five numbers are inserted into a linked list and it prints the list five times with one element (the head) is removed for each time. Here is the sample output for your program that it supposed to be:




At the same time, it checks if the number 9 is in the list by the function exist().

<h1>Tasks (Graded)</h1>

<ol>

 <li>Implement the print() member function of the class List such that it will print out all the list element(s) with cout</li>

 <li>Implement the exist(int n) member function of the class List such that it will return 1 if n is in the list, or 0 otherwise.</li>

 <li>Submit your code by pasting the two functions to coursemology. Remember to “finalize” your submission after you are done. But you can only “finalize” once, remember to do so only if you are done completely.</li>

</ol>

For more details in how to complete the assignment, please refer to the Power Point slides in the workbin in IVLE.

<h1>Extra Tasks (Not Graded)</h1>

If you are looking for extra challenges, you could try the followings by yourself.

<strong>Other Member Functions of class List </strong>

You can add and implement the following functions:

<ul>

 <li>headItem() that will return the first item in the list if the list is not empty.</li>

 <li>empty() that will return 1 if the list has nothing, and 0 otherwise.</li>

 <li>tailItem() that will return the last item in the list if the list is not empty.</li>

 <li>removeTail() that will removes the last item of the list if the list is not empty.</li>

</ul>

<strong>Create A Project of Your Own </strong>

You can try to create a MSVS solution or XCode project of your own. You can use the .h and .cpp files in this assignment, or some finished assignments from your previous courses. Additionally, you could try to divide your previous code into .h and .cpp files.


