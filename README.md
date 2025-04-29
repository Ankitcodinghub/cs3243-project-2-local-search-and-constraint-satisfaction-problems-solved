# cs3243-project-2-local-search-and-constraint-satisfaction-problems-solved
**TO GET THIS SOLUTION VISIT:** [CS3243 Project 2-Local Search and Constraint Satisfaction Problems Solved](https://www.ankitcodinghub.com/product/cs3243-introduction-to-artificial-intelligence-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114611&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3243 Project 2-Local Search and Constraint Satisfaction Problems Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Overview

In this project, you will implement local search and Constraint Satisfaction Problem (CSP) algorithms to find valid goal states in a game. Specifically, you are tasked to implement the following algorithms:

1. Implement the Local Search Algorithm (Hill-Climbing or Beam Search).

2. Implement the CSP Backtracking Algorithm.

This project is worth 10% of your module grade.

General Project Requirements

The general project requirements are as follows:

• Individual project

• Python Version: 3.7

• Submission folder: LumiNUS &gt; CS3243 &gt; Projects &gt; Project 2 Submission folder

• Submission format: One standard (non-encrypted) zip file containing only the necessary project files. In particular, it should unzip to give one folder with two .py files: Local.py and CSP.py. More information is given in the Submission Details section below.

As to the specific project requirements, you must complete and submit the following:

• Task 1 (Local Search): Implement your Local Search algorithm in Local.py.

• Task 2 (CSP): Implement your CSP Backtracking algorithm in CSP.py.

Note that you are tasked to implement your own search space and state structure for the game. You are strongly encouraged to reuse your search space and state definition from Project 1.

Background: n-Queens Puzzle

Figure 1: A layout of the 8-queens puzzle.

Input test file

Similar to Project 1, for each test case, you will be given an input text file containing the board configuration (e.g., number of rows/columns, type of game pieces, starting position of game pieces, etc.). You are required to parse the input text file and build the game board and its state.

In Project 2, there are two different types of test case files (e.g., Local1.txt, Local2.txt, … and CSP1.txt, CSP2.txt, …) – one type for Local Search and one type for CSP. You are required to parse the different test case files accordingly for each algorithm.

Getting Started

You are given two python files (Local.py, CSP.py) with the recommended empty functions/classes to be implemented. Specifically, the following are given to you:

1. runlocal/CSP(): DO NOT REMOVE THIS FUNCTION. When called, this function must return a Goal State. The returned output will be evaluated by the autograder for correctness. More details on the output will be given in the later sections.

You are encouraged to write other helper functions to aid you in implementing the algorithms. You are also encouraged, for both python files, to use the same classes to design the game board and pieces (i.e., State, Board, Piece); only the implementation of search() should differ. During tests, when each of the two python files are executed, the input filename will be given as the first command line argument (use sys.argv[1] to get the input filename) and thereafter only the method runXXX() will be called. The output should be a valid Goal State.

Finding a Valid Goal using Local Search/Backtracking

The objectives of this part of the project are:

1. To gain exposure in the implementation of algorithms taught in class.

2. To learn to recognise the differences and utility of each search algorithm.

3. To learn to recognise the effects that the different methods have on the performance and efficiency.

Project 2 Task 1: Overpopulation

Background:

We are given a game board of varying size. Each such board is completely filled with chess pieces (and obstacles). The positions of the chess pieces and obstacles are given in the input test file. The pieces and obstacles will remain static at all times (i.e., they remain in the same position throughout the search). Each chess piece will threaten its surrounding position based on the type of chess piece it is. Note that whilst the chess pieces can threaten each other, they will not actually capture/eliminate other pieces. An example of the initial state of the board is shown below:

Figure 2: An initial state of the game with the the board being completely filled up .

We are also given a positive integer k (where k ≤ n, and given that initially, there are n pieces on the board). The objective of the game is thus to remove at most n − k pieces such that no two pieces on the board threaten each other. This implies that the goal is to find a board with at least k original pieces (i.e., pieces in their starting positions) on it, such that among these k original pieces, no piece is threatening another. The diagram below shows an example of a goal state of the game:

Figure 3: The goal state of the game with 8 pieces left on the board where they are not threatening one another.

Task 1: Local Search

Implement a Local Search algorithm (i.e., Hill-Climbing or Beam search) to solve the problem stated above in Local.py. This can be done through random restarts or other variants of the algorithms specified.

Test file input: Use sys.argv[1] to obtain the name of the test file within the run local() function. This has already been added for you in the template code.

When the runlocal() function is executed, your code should return a dictionary of valid positions such that no two chess piece threaten one another on the board and each chess piece is on the board in the following format:

{pos1 : piece1,pos2 : piece2,…,posn : piecen}

Each position posi and piece piecei, is a (key:value) pair. The key represents a grid index tuple, (x,y), where x is the column index (i.e., a string), and y is the row index (i.e., an integer), such that (x,y) corresponds to a specific grid cell on the board that we wish to reference. The value corresponds to a string identifying a particular type of chess pieces (i.e., ”King”, ”Queen”, ”Bishop”, ”Rook” or ”Knight” – do note that the first letter is capitalised).

More specifically, the positions of the pieces at its goal state should be returned in this format:

{(x1,y1) : piece1,(x2,y2) : piece2,(x3,y3) : piece3,…,(xj,yj) : piecej}

An example of the function printed and its output is shown below:

print(runlocal())

Sample Output:

Project 2 Task 2: Repopulation

In order to reduce the probability of a revolt, the council from the CS3243 Kingdom has decided to relocate the citizens it has exiled. Being a new settlement, the exiled population would have had no difficulties with the relocation. However, as fate would have it, they are stricken by an infectious disease (Covid-99). The citizens must now practise safe distancing amidst their relocation to reduce the chance of transmission.

Background:

We are given a game board of varying size. Each board is initially empty (except for any obstacles). The number of each chess piece are given in the input test file. An example of the initial state of the board is shown below:

Figure 4: An initial state of the game with the the board being completely empty and two obstacles labelled ’X’.

We are also given a set of chess pieces to populate the board with (i.e., the input test file specifies how many pieces of each kind must be placed). The objective of the game is to find positions on the given board for each piece specified in the given set of chess pieces such that no two pieces on the board threaten each other. This implies that the goal is to find a board where all chess pieces specified in the initial set are placed such that no piece is threatening another. The diagram below shows an example of a goal state of the game:

Figure 5: The goal state of the game with no pieces threatening one another and all pieces (8 Queens) stated in the input test file are placed in the goal state.

Task 2: Backtracking

Implement the Backtracking algorithm to solve the problem stated above in CSP.py. You are free to use any heuristics and inference algorithm to speed up the search.

Test file input: Use sys.argv[1] to obtain the name of the test file within the run CSP() function. This has already been added for you in the template code.

When the runCSP() function is executed, your code should return a dictionary of valid positions such that no two chess piece threaten one another and all the given chess pieces have been placed on the board. The required format is:

{pos1 : piece1,pos2 : piece2,…,posn : piecen}

Each position posi and piece piecei, is a (key:value) pair. The key represents a grid index tuple, (x,y), where x is the column index (i.e., a string), and y is the row index (i.e., an integer), such that (x,y) corresponds to a specific grid cell on the board that we wish to reference. The value corresponds to a string identifying a particular type of chess pieces (i.e., ”King”, ”Queen”, ”Bishop”, ”Rook” or ”Knight” – do note that the first letter is capitalised).

More specifically, the positions of the pieces at its goal state should be returned in this format:

{(x1,y1) : piece1,(x2,y2) : piece2,(x3,y3) : piece3,…,(xj,yj) : piecej}

An example of the function printed and its output is shown below:

print(runCSP())

Sample Output:

• Correct implementation of Local Search Algorithm evaluated by passing all public test cases and hidden test cases (4m).

• Correct implementation of Backtracking Algorithm evaluated by passing all public test cases and hidden test cases (6m). 10

Grading Details

Your code will be graded for technical correctness. Please do not change the name of the function runXXX().

There are 3 configuration files released to you via LumiNUS (together with the skeleton implementation files). These files serve as public test cases. There are additional private test cases that we will also run using your code (on CodePost). This is to prevent students from applying bruteforce and simply returning the results without implementing the algorithms. Hence, to get the full credit for each task, you are required to pass all the public test cases and private test cases.

For each test case, the correctness of your code will be tested (e.g., returning the valid goal state in the specific format) and the time taken for the execution of your code will be measured as well. The time taken for your search algorithms will be compared to our solution’s benchmark. If the time taken for your code is above the time limit, it will be considered a failure of the test case. As such, you are encouraged to use efficient data structures when implementing your code (e.g. using a set/dictionary instead of a list). To account for the execution of code on different systems, we have provided additional buffers for the time limit.

In summary, to pass a test case, two conditions have to be fulfilled for Local/CSP. They are:

1. Valid goal state comprising of the chess pieces in valid positions.

2. Time taken to run your search is within the time limit.

CodePost (Platform for Running Autograder)

We will be using CodePost as our platform to run the autograder and test your code. You should have already joined the Course’s group on CodePost from Project 1. If you need any assistance for CodePost signups, please feel free to reach out and email any of the TAs.

Subsequent access: https://codepost.io/student/CS3243%20AY2122%20Semester%

202/Spring%202022/

1. For each task (Local/CSP), click on “Upload assignment”, and upload your Python file Local.py/CSP.py (do NOT rename the files).

3. After the submission has been processed, refresh the page and select “View feedback”.

4. Ideally, if your implementation is correct and is within the runtime threshold, the output will look like this:

Figure 6: Codepost output

5. As mentioned in the previous section, if your solution is incorrect or takes too long, the autograder on CodePost will deem it as incorrect.

Other details

Allowed Libraries:

To aid in your implementation, you are allowed to use these Python libraries:

• CLI arguments: sys

• Datastructures: queue, collections, heapq, array, copy, enum, string

• Math: numbers, math, decimal, fractions, random

• Functional: itertools, functools, operators

• Types: types, typing

Testcases Debugging:

Based on Project 1 feedback, we have updated the Autograder and now it provides stacktrace and debug info in the tests.txt file as shown in the image below. However, in providing the stack trace and error information, we have disabled any printing on your Local.py and CSP.py files. This is to prevent any malicious students from printing the hidden testcases information.

Figure 7: Codepost Debug Output

Submission Details via LumiNUS

• For this project, you will need to submit 1 zip file containing 2 Python files: Local.py, CSP.py.

• Place the 2 files in a folder, name the folder as studentNo and zip it as studentNo.zip. An example will be: A0123456X.zip.

• The format of submission is the same as Project 1

• In summary, your submission file should be a zip file and when unzipped, it will contain the 2 files in a folder: A0123456Z.zip → unzip → A0123456Z folder → Local.py, CSP.py files. There should not be any subfolders.

• Do not modify the file names.

• Make only one submission on LumiNUS.

• Please follow the instructions closely. If your files cannot be opened or if the grader cannot execute your code, this will be considered failing the testcases as your code cannot be tested.

• Submission folder: LumiNUS &gt; CS3243 &gt; Projects &gt; Project 2 Submission Folder
