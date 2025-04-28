# it5001-lab-6--multi-dimensional-arrays-solved
**TO GET THIS SOLUTION VISIT:** [IT5001 Lab 6- Multi-dimensional Arrays Solved](https://www.ankitcodinghub.com/product/it5001-week-6-multi-dimensional-arrays-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119258&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IT5001 Lab 6- Multi-dimensional Arrays Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Part 1 Matrix Operations

In this part, you can assume that all matrix entries are integers.

Task 1 Transpose

Write a function transpose(m) that takes in a matrix m with dimensions r x c and returns the transpose of m which has dimensions c x r.

&gt;&gt;&gt; pprint(m)

[[1, 1, 1, 0, 1, 0, 0, 1, 0, 1], [1, 0, 1, 0, 0, 0, 1, 0, 0, 0],

[0, 0, 1, 1, 0, 0, 0, 1, 1, 0],

[0, 1, 1, 1, 1, 0, 0, 0, 1, 1]]

&gt;&gt;&gt; pprint(transpose(m)) [[1, 1, 0, 0],

[1, 0, 0, 1],

[1, 1, 1, 1],

[0, 0, 1, 1],

[1, 0, 0, 1],

[0, 0, 0, 0],

[0, 1, 0, 0],

[1, 0, 1, 0],

[0, 0, 1, 1],

[1, 0, 0, 1]]

Task 2 Multiplication

Write a function matMul(m1,m2) that returns the result of multiplying matrix m1 by m2.

&gt;&gt;&gt; m1 = [[1,2,3],[5,6,7],[9,10,11],[13,14,15]]

&gt;&gt;&gt; m2 = [[4,3,2,1,8,1],[1,2,3,4,3,1],[5,6,7,8,1,2]]

&gt;&gt;&gt; pprint(matMul(m1,m2))

[[21, 25, 29, 33, 17, 9],

[61, 69, 77, 85, 65, 25],

[101, 113, 125, 137, 113, 41],

[141, 157, 173, 189, 161, 57]]

Task 3 Minor Matrix

Write a function minorMatrix(m,i,j) that returns the minor matrix of m without row i and column j.

&gt;&gt;&gt; pprint(m)

[[21, 25, 29, 33, 17, 9],

[61, 69, 77, 85, 65, 25],

[101, 113, 125, 137, 113, 41],

[141, 157, 173, 189, 161, 57]]

&gt;&gt;&gt; pprint(minorMatrix(m,2,3))

[[21, 25, 29, 17, 9], [61, 69, 77, 65, 25], [141, 157, 173, 161, 57]]

Task 4 Determinant

Write a function det(m) that returns the determinant of matrix m.

&gt;&gt;&gt; m = [[6,1,1],[4,-2,5],[2,8,7]]

&gt;&gt;&gt; det(m)

-306

&gt;&gt;&gt; m = [[1,2,3,4],[5,6,7,8],[9,10,11,12],[13,14,15,16]]

&gt;&gt;&gt; det(m)

0

Part 2 Maze

Let’s assume a maze is an r x c grid that consists of 0s and 1s, where 0 represents an empty space and 1 represents a blocked space.

Task 1 Random Maze

Write a function createRandomMaze(r,c) which returns a maze of size r x c where every space has an equal random chance of being empty or blocked.

&gt;&gt;&gt; maze = createRandomMaze(8,14)

&gt;&gt;&gt; mTightPrint(maze)

01111111010011

00000001000000

10000100100000

10110010000010

00001100011001

10000101010100

10001001011000

10010100110100

Task 2 Solvable

Suppose you can enter a r x c maze from its top left corner at position (0,0) and exit from its lower right corner at position (r-1,c-1). Write a function isSolvableMaze(m) that takes in a maze m and returns True if you can eventually reach the exit from the entrance, and False otherwise. In other words, determine if the maze is solvable. (You can only move horizontally or vertically, not diagonally.)

Extra Tasks

• Write some code to find a maze generated by Task 1 that has a size of 15 x 30 and is also solvable.

• Other than mTightPrint(), write your own function to beautify your maze presentation.

• When you find out a maze is solvable, leave a trace (e.g. replace the space with a ‘.’) to show the path found.
