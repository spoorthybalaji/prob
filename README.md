# prob
1. Micro and Array Update
Micro purchased an array A having N integer values. After playing it for a while, he got
bored of it and decided to update value of its element. In one second he can increase
value of each array element by 1. He wants each array element's value to become greater
than or equal to K. Please help Micro to find out the minimum amount of time it will take,
for him to do so.
Input:
First line consists of a single integer, T, denoting the number of test cases.
First line of each test case consists of two space separated integers denoting N and K.
Second line of each test case consists of N space separated integers denoting the array
A.
Output:
For each test case, print the minimum time in which all array elements will become
greater than or equal to K. Print a new line after each test case.




2. Hamiltonian and Lagrangian
Students have become secret admirers of SEGP. They find the course exciting and the
professors amusing. After a superb Mid Semester examination, it’s now time for the
results. The TAs have released the marks of students in the form of an array, where arr[i]
represents the marks of the ith student.
Since you are a curious kid, you want to find all the marks that are not smaller than those
on its right side in the array.
Input Format
The first line of input will contain a single integer n denoting the number of students.
The next line will contain n space separated integers representing the marks of students.
Output Format
Output all the integers separated in the array from left to right that are not smaller than
those on its right side.




3.Frustrated Coders
There are N frustrated coders standing in a circle with a gun in their hands. Each coder
has a skill value S[ i ] and he can only kill those coders that have strictly less skill than
him. One more thing, all the guns have only 1 bullet. This roulette can take place in
any random order. Fortunately, you have the time stone (haaan wo harre wala) and
you can see all possible outcomes of this scenario. Find the outcome where the total
sum of the remaining coder's skill is minimum. Print this sum.
Input Format
The first line contains N the no. of coders
The next line contains N elements where the ith element is theS[ i ] of ith coder.
Output Format
Print a single line containing the minimum sum.




4. Pink Floyd and Happiness
Pink is sad because of some reasons, he wants to cheer up by listening to some songs
from his favorite band, Pink Floyd.
There are N records and Pink will be happy if he listens to them in the ascending
order, i.e., first the song No. 1, then No.2 and so on (He has to listen to all the N songs
to become Happy).
Pink is delivered his records in some given order, he can either add the record to the
Playlist in the delivered order or put some on another table. After being put on the
table only the topmost record can be added to the playlist at any time.
Print whether Pink will be sad or happy after the delivery of the records.
Input Format
N - Number of records followed by
N numbers- order of records.
Output Format
Print "Happy" if the playlist has songs from 1 to N in order else "Sad".




5. Hacker and traffic lights
Zolo is stuck in a traffic due to dysfunctional traffic light. Zolo is a professional hacker
and he can get into the system and change the state of the light. His planet has
different types of traffic lights such that there are N bulbs on the traffic board and
only when all of them are green(G) the cars can pass. there are 2 other states also
which the bulb can show; i.e. Red(R) & Yellow(Y). Note that the lights are designed
such that they follow a state change cyclic pattern as follows:
R------>Y------>G------->R
Once Zolo gets into the system he can select any position i and update all elements
between i to min(N, i + K - 1) by increasing their state by 1.This whole process takes
1 sec and he can repeat this process any no. of times until he gets all lights = G . Find
the minimum time to do the process as Zolo is getting late for work.
Input Format
The first line contains N K
The second line describes the current status of each bulb as an array whose each
element can either be G or Y or R.
Output Format
Print the minimum amount of time required to clear the traffic jam".




6. Remove Friends
After getting her PhD, Christie has become a celebrity at her university, and her
Facebook profile is full of friend requests. Being the nice girl, she is, Christie has
accepted all the requests.
Now Kuldeep is jealous of all the attention she is getting from other guys, so he asks
her to delete some of the guys from her friend list.
To avoid a 'scene', Christie decides to remove some friends from her friend list, since
she knows the popularity of each of the friend she has, she uses the following
algorithm to delete a friend.
Algorithm Delete(Friend):
DeleteFriend=false
for i = 1 to Friend.length-1
if (Friend[i].popularity < Friend[i+1].popularity)
delete i th friend
DeleteFriend=true
break
if(DeleteFriend == false)
delete the last friend.
Input Format
First line contains T number of test cases. First line of each test case contains N, the
number of friends Christie currently has and K ,the number of friends Christie decides
to delete. Next lines contains popularity of her friends separated by space.
Output Format
For each test case print N-K numbers which represent popularity of Christie friend's
after deleting K friends.




7. Largest cycle in a tree
You are given a tree of N nodes and N-1 edges. Now you need to select two nodes a
and b in the tree such that the cycle that will be formed after adding an edge between
the two nodes a and b, its length should be maximum. If there are more than one
possible answer, you can output any of them.
Input Format
The first line contains an integer as N input. Next N-1 lines contain a pair of integers
(a, b) that denote there is an edge between the two nodes a and b in the tree.
Output Format
In the output, you need to print two integers separated by space which denote the
nodes between which you can add the edge so as to maximize the length of the cycle
in the tree.


8. Monk watching fight
Once Monk was watching a fight between an array and a tree, of being better. Tree
got frustrated and converted that array into a Binary Search Tree by inserting the
elements as nodes in BST, processing elements in the given order in the array. Now
Monk wants to know the height of the created Binary Search Tree.
Help Monk for the same.
Note:
  1) In Binary Search Tree, the left sub-tree contains only nodes with values less than
or equal to the parent node; the right sub-tree contains only nodes with values
greater than the parent node.
  2) Binary Search Tree with one node, has height equal to 1.
Input Format
The first line will consist of 1 integer N, denoting the number of elements in the array.
In next line, there will be N space separated integers, A[i], where 1 ≤ I ≤ N, denoting
the elements of array.
Output Format
Print the height of the created Binary Search Tree.




9. Yatin plays PUBG
Yatin is playing PUBG and he has reached a place with a large staircase in front of him.
And there is an enemy at each landing of the staircase.
The staircase is analogous to a binary tree with each of its nodes as a landing of the
staircase and each of its edges as stairs from one landing to another.

Yatin wants to kill the maximum possible number of enemies. He can kill every person
he can see from his position with his suppressed sniper gun. But he can see only the
persons at the leftmost standing at each level and cannot see the rest.
Before starting shooting them, he wants to know how many persons he can kill. He is
busy keeping an eye on the enemies. So he wants you to find out the maximum
number of people he can kill from that location by providing you with the analogous
a binary search tree.
Input Format
The first line of input contains a number t denoting the number of test cases.
The first line of each test case contains n, the number of nodes in the tree.
The second line of each test case contains n space separated integers (unique) ai
denoting the value at each node of the BST.
Output Format
Print the answer for each test case on a new line.





10. Haunted
The king of ghosts is really disappointed when he sees that all the human beings on
Planet Earth have stopped fearing the ghost race. He knows the reason for this. The
existing ghost race has become really lazy and has stopped visiting Planet Earth to
scare the human race. Hence, he decides to encourage the entire ghost race into
scaring the humans by holding a competition. The king, however, never visits Planet
Earth.
This competition will go on for N days. Currently, there are a total of M ghosts (apart
from the king) existing in the ghost race such that :
- The youngest ghost is 1 year old.
- The oldest ghost is M years old.
- No two ghosts have the same age.
- The age of each and every ghost is a positive integer.
On each day of the competition, ghosts have to visit Planet Earth to scare people. At
the end of each day, a "Ghost of the Day" title is awarded to the ghost who scares the
most number of humans on that particular day. However, the king of ghosts believes
in consistency. Once this title has been given, the ghost who has won the most
number of such titles until that particular moment is presented with a "Consistency
Trophy". If there are many such ghosts, the oldest among them is given the trophy.
Note that this "Title Giving" and "Trophy Giving" happens at the end of each day of
the competition.
You will be given the age of the ghost who won the "Ghost of the Day" title on each
day of the competition. Your job is to find out the age of the ghost who was awarded
with the "Consistency Trophy" on each day of the competition.
Input Format
The first line consists of 2 space separated integers N and M. The next line consists of
N space separated integers such that the ith integer denotes the age of the ghost who
was awarded with the "Ghost of the Day" title on the ith day of the competition.
Output Format
Print N lines. The ith line should contain 2 space separated integers such that the first
integer denotes the age of the ghost who was awarded with the "Consistency Trophy"
on the ith day and the second integer denotes the number of "Ghost of the Day" titles
won by this ghost until the end of the ith day of the competition.


