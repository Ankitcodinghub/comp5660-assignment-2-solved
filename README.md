# comp5660-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [COMP5660 Assignment 2 Solved](https://www.ankitcodinghub.com/product/comp5660-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96389&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5660 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
The goal of this assignment set is for you to become familiarized with (I) unambiguously formulating complex problems in terms of optimization, (II) implementing an Evolutionary Algorithm (EA) of the Genetic Pro- gramming (GP) persuasion, (III) conducting scientific experiments involving EAs, (IV) statistically analyzing experimental results from stochastic algorithms, and (V) writing proper technical reports. The problem you will be solving is to employ GP to first evolve a controller for Pac-Man (also referred to as a Pac-Man agent) and subsequently to co-evolve controllers for Pac-Man with maps. This problem is representative of a large and very important class of problems which require the identification of system models such as con- trollers, programs, or equations. An example of the latter is symbolic regression which attempts to identify a system model based on a limited number of observations of the system’s behavior; classic mathematical techniques for symbolic regression have certain inherent limitations which GP can overcome. Employing GP to evolve a controller for Pac-Man is also a perfect illustration of how GP works, while avoiding many of the complications of evolving full blown computer programs.

These are individual assignments and plagiarism will not be tolerated. You must write your code from scratch in one of the approved programming languages. You are free to use libraries/toolboxes/etc, except problem and search/optimization/EA specific ones.

Problem statement

In this assignment you will implement and evolve controllers for Pac-Man and co-evolve against maps.

GPac

In GPac, the world is a two-dimensional grid and there is no world wrap. There are two types of units: Pac-Man and the Ghosts. Pac-Man always starts at the top left cell and all three the ghosts always start at the bottom right cell. These units are guided by controllers, which is what your GP will evolve. Units move in cardinal directions (up, down, left, right); Pac-Man can choose to hold position, but the Ghosts cannot. They move from one grid cell to another in a discrete fashion (i.e., they move a whole cell at a time). Units cannot move off the edges of the map. Ghosts can occupy the same grid cell as other ghosts. If Pac-Man

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
and a Ghost occupy the same cell, the game is over. If Pac-Man and a Ghost collide (i.e., exchange cells), the game is over.

Pills

Before the game begins, cells are chosen at random according to a preset pill-density parameter to contain “pills”. The pill-density parameter specifies the percentage chance for any given cell to contain a pill, subject to the constraints (a) at least one cell needs to contain a pill, (b) pills cannot be placed in walls and (c) Pac- Man’s starting cell cannot contain a pill. Thus: E[number of cells containing a pill] = MAX (1 , pill-density · (total number of cells – 1 – number of walls))

If Pac-Man occupies a cell that contains a pill, the pill is removed, and Pac-Man’s score is increased. When all pills have been removed from the world, the game is over.

Fruit

Each turn that the game is running, there is a user-configurable chance for a piece of fruit to spawn. There can only be one piece of fruit on the field at a time and it may not spawn in the same cell as a pill, a wall, or Pac-Man’s current cell. If Pac-Man occupies the cell that contains the piece of fruit, the fruit is removed, and Pac-Man’s score is increased by the fruit score which is user-configurable.

Time

Each GPac game starts with time equal to the number of grid cells in the world multiplied by the time multiplier. Each turn is one time step. When the time limit reaches zero, the game is over. This prevents games from getting stuck in infinite loops. It also promotes efficient controller evolution.

Game Play

Each turn, the game gives each of the unit’s controllers the current game state. This state includes at least: where all of the units are currently located and where all of the pills are located. Each controller will then choose what move to make (up, down, left, right for all controllers, also hold just for Pac-Man). Once all of the units have determined their next move, the game state will update everyone’s position and decrease the time remaining by one. Once everyone has moved, the game will check if:

1. Pac-Man and any of the Ghosts are in the same cell, causing game-over.

2. Pac-Man collided with a Ghost, causing game-over.

3. Pac-Man is in a cell with a pill, causing the pill to be removed, and the score to be adjusted.

4. Pac-Man is in a cell with a piece of fruit, causing the fruit to be removed, and the score to be adjusted. 5. All the pills are removed, causing game-over.

6. Time remaining is equal to zero, causing game-over.

Score

Pac-Man’s score is equal to the percentage of the total number of pills he has consumed truncated to an integer, plus the score for fruit consumed. If the game ends because there are no more pills on the board, Pac-Man’s score is increased by the percentage of time remaining truncated to an integer. This score can be used directly for the fitness of the Pac-Man controller. Ghost fitness should be inversely proportional to Pac-Man’s fitness (for example, negate his fitness) and if the game ends due to Pac-Man’s demise, then the Ghost score is increased by the percentage of time remaining truncated to an integer.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
World File Format

GPac generates a sequence of your world states for a single run to facilitate debugging, visualization, and grading. The common file format you are required to use consists of header values for the width and height of the world, followed by, for each snap shot that you are outputting, a list of ordered triples consisting of &lt;key&gt;&lt;space&gt;&lt;value&gt;&lt;space&gt;&lt;value&gt;. The origin (0,0) is in the lower-left corner. The valid triples are:

m Pac-Man; second value is x-coordinate; third value is y-coordinate 1 Ghost 1; second value is x-coordinate; third value is y-coordinate 2 Ghost 2; second value is x-coordinate; third value is y-coordinate 3 Ghost 3; second value is x-coordinate; third value is y-coordinate p Pill; second value is x-coordinate; third value is y-coordinate

w Wall; second value is x-coordinate; third value is y-coordinate

f Fruit spawned; second value is x-coordinate; third value is y-coordinate

t End of current turn; second value is remaining time; third value is current score

Note that you only need to write out the pill and wall locations during the first snap shot as the moves of Pac-Man implicitly define the pill locations of all later snap shots. This will make your world file significantly smaller in size. Here is an example file for a world with width 40, height 30, 3 snap shots, and 3 pills:

40

30

m 0 29

1 39 0

2 39 0

3 39 0 w11

w 36 20

w 10 10

w 2 29

p 1 29

p 36 19

p 27 8

t 2400 0 m 1 29

1 38 0

2 38 0

3 39 1

t 2399 33 m 1 28

1 38 1

2 37 0

3 39 0

t 2398 33

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
General implementation requirements

For this assignment series you must implement GPac controllers for Pac-Man. You are provided with an implementation of GPac with proper score calculation, spawn mechanics, game-over identification, and world file generation (called a game log in the code). In theory, the fitness of a controller is its expected performance for an arbitrary game instance (i.e., its performance averaged over all game instances). However, as it is computationally infeasible to evaluate a controller over all possible game instances, for the purpose of this assignment it will be sufficient to play a single game instance to completion to estimate fitness. Your code needs to be compatible with the provided GPac implementation and adhere to the specifications of the individual assignments in this series. Your submission should also compile and execute within the base Conda Linux environment as prescribed in the environment setup assignment. If you require a package not present in that base environment, please contact a TA for approval. In all assignments that contain Jupyter notebooks: those notebooks must be completed and submitted with results from running the full notebook.

The GP controllers must be implemented as follows: for each valid action and the corresponding new state from executing the action, apply the state evaluator encoded in the GP tree, returning the valid action with the best state evaluation. The terminal nodes consist of sensor inputs and floating point constants. The function nodes consists of mathematical operators which take as input floating point numbers and provide as output floating point numbers as well. You need to implement at minimum four sensor inputs, where the target location specifically refers to the grid cell where the controller’s unit is moving to this turn, namely: (1) the Manhattan distance between the target location and the nearest Ghost, (2) the Manhattan distance between the target location and the nearest pill, (3) the number of walls immediately adjacent to the target location, and (4) the Manhattan distance between the target location and the fruit. Note: When considering a move in which a pill or the fruit is consumed, immediately increasing the Pac-Man to pill or fruit distance input may lead your controllers to think that the new state is worse than the state prior to eating the fruit. You need to implement at minimum five mathematical operators, namely: (1) addition, (2) subtraction, (3) multiplication, (4) division, and (5) rand(a,b) which returns uniform randomly a number between a and b.

The highest-score-game-sequence all-time-step world file is a file in the previously specified World File Format containing a sequence of world states at every time step of typically the best run of your experiment (i.e., the run with the global best fitness). In 2a &amp; 2b the solution file should contain the best Pac- Man controller found, in 2c the solution files should contain the best Pac-Man controller and map found respectively.

The solution file format must be exactly as follows to allow automated format checking: you need to output your parse tree(s) such that each tree node is on a new line in the format &lt;‘|‘ characters corresponding to tree depth&gt;&lt;node character&gt;, where the root of the tree is at depth 0 and the following characters represent tree nodes:

<ul>
<li>Sensor inputs
G Manhattan distance to nearest ghost

P Manhattan distance to nearest pill

W Number of immediately adjacent walls

F Manhattan distance to nearest fruit

#.# Constant value (where the ‘#‘ character is replaced with a one or more digits)
</li>
<li>Operators
+ Addition

– Subtraction

* Multiplication

/ Division

RAND Random number between two children node values.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
All of the above operators should have strictly two children.

For the sensor inputs P and F, if a move would place Pac-Man on top of a pill or fruit, the sensor value

should be 0, rather than considering the item as collected and gone. If there is no fruit, then F should have a constant value.

Note: you are encouraged to implement additional sensor inputs and operators with your own (well documented) single or multiple character representations. These new operators are not bound to the strict two children constraint of the required operators, but make sure you document the degree or range of acceptable degrees for your operators. Additional sensor nodes often lead to interesting agent capabilities and strategies.

Example

Here is an example parse tree:

*

/

1.2 G W P

The parse tree shown above would look as follows in a solution file:

<pre>*
|/
||1.2
||G
|RAND
||W
||P
</pre>
Version control requirements

For each assignment you will be given a new repository on [https://classroom.github.com]. Please view your repository and the README.md file. It may clear things up after reading this.

Included in your repository is a script named “finalize.sh”, which you will use to indicate which version of your code is the one to be graded. When you are ready to submit your final version, run the command ./finalize.sh from your local Git directory, then commit and push your code. This will create a text file, “readyToSubmit.txt”, that is pre-populated with a known text message for grading purposes. You may commit and push as much as you want, but your submission will be confirmed as “final” if “readyToSub- mit.txt” exists and is populated with the text generated by “finalize.sh” at 10:00pm on the due date. If you do not plan to submit before the deadline, then you should NOT run the “finalize.sh” script until your final submission is ready. If you accidentally run “finalize.sh” before you are ready to submit, do not commit or push your repo and delete “readyToSubmit.txt”. Once your final submission is ready, run “finalize.sh”, commit and push your code, and do not make any further changes to it.

The code currently pushed to the default branch will be pulled for grading. The TAs should not have to worry about external dependencies. Any files created by your assignment must be created in the present working directory or its subfolders.

</div>
</div>
<div class="layoutArea">
<div class="column">
RAND

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Submissions, penalties, documents, and bonuses

You may commit and push to your repository at anytime. At submission time, your latest, pushed and finalized, commit to the master branch will be graded (if there is one). In order to ensure that the correct version of your code will be used for grading, after pushing your code, visit [https://github.com] and verify that your files are present. If for any reason you submit late, then please notify the TAs when you have submitted. If you do submit late, then your first late submission will be graded.

The penalty for late submission is a 5% deduction for the first 24 hour period and a 10% deduction for every additional 24 hour period. So 1 hour late and 23 hours late both result in a 5% deduction. 25 hours late results in a 15% deduction, etc. Not following submission guidelines can be penalized for up to 5%, which may be in addition to regular deduction due to not following the assignment guidelines.

Your code needs to compile/execute as submitted without syntax errors and without runtime errors. Grading will be based on what can be verified to work correctly as well as on the quality of your source code. You must follow the coding requirements as stated in the syllabus.

Documents are required to be in PDF format; you are encouraged to employ LATEX for typesetting.

Note that the first two assignments in this series are weighted equally, but the third and last counts double to allow you one extra chance to significantly makeup your assignment grade.

Deliverable Categories

There are three deliverable categories, namely:

GREEN Required for all students in all sections.

YELLOW Required for students in the 6000-level sections, bonus for the students in the 5000-level section. RED Bonus for all students in all sections.

Note that the max grade for the average of all assignments in Assignment Series 2, including bonus points, is capped at 100%.

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Assignment 2a: Random Search

You must implement a random search through valid parse tree space for Pac-Man controllers in GPac. In this assignment, you are asked to complete the Jupyter notebook 2a notebook.ipynb and several other Python files as directed by the notebook. Your submission should also contain a report to document the findings of a 30-run experiment as well as files containing the world file (log) and tree from the solution with the highest fitness from all runs. In your report, include a stair-step plot showing the progression of number of fitness evaluations versus local best fitness for the run that produced the highest fitness overall, the standard deviation and mean of the best fitness found from each run, and an informal analysis of your agent’s performance from watching the visualization of the highest-fitness solution. In this informal analysis, we want you to comment on whether or not you think the agent performs well, as well as any notable behavioral quirks.

The deliverables of this assignment are:

GREEN 1 your source code and completed notebook

GREEN 2 a PDF document headed by your name, AU E-mail address, and the string “COMP x66y Fall 2021 Assignment 2a”, where x and y need to reflect the section you are enrolled in, containing your report, including statistical analysis and plot(s)

GREEN 3 files containing any data you analyzed to write your report or generate your plot(s), in a format that can be easily understood by the TAs (if you think you might should include instructions on how to interpret your data, then you should!), as well as the highest-score-game-sequence all-time-step world files, and solution files (these should go in the repo’s worldFiles, and solutions directories respectively).

RED 1 In order to demonstrate that an EA is a reasonable tool for solving a given problem, it is generally more compelling to compare the EA to a simple optimization algorithm such as a hill climber, rather than random search. Showing that the EA outperforms a hill climber indicates that the problem being solved is probably multimodal, and that evolution allows a more effective exploration of the search space. Up to 15% bonus points can be earned by investigating the use of a hill climber to optimize controllers by making small changes to the controller and accepting changes that improve fitness. This bonus investigation needs to be documented, including result plots and a new config file, in a separate section of the required document marked as “Hill Climber”. You also need to indicate in your source files any code which pertains to this bonus and additionally describe it in your README.md file. Basically, you need to make it as easy as possible for the TAs to see with a glance what part of your submission pertains to this bonus, and which does not.

Edit your README.md file to explain anything you feel necessary. Submit all files via GitHub, by pushing your latest commit to the master branch. The due date for this assignment is 10:00 PM on Sunday October 24, 2021.

</div>
</div>
<div class="layoutArea">
<div class="column">
Grading

The point distribution is as follows:

Assessment Rubric \ Deliverable Category Algorithmic comprehension

Logging and output files

Good programming including code reliability, commenting, correctness, &amp; practices Report

</div>
<div class="column">
Green Red 50 55

15 5 10 10 25 30

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
Assignment 2b: Genetic Programming Search

You need to evolve a GP tree controller for Pac-Man which generates the most high-quality valid action out of the 5 possible actions for Pac-Man that it can find, employing the approach described in the general specification. The map should be the same static map as specified in Assignment 2a. In this assignment, you are asked to complete the Jupyter notebook 2b notebook.ipynb and several other Python files as directed by the notebook.

You need at minimum to implement support for the following EA configurations, as described in the notebook:

Representation Tree

Initialization Ramped half-and-half (see Section 6.4 in [1])

Parent Selection Fitness Proportional Selection, k-Tournament Selection without replacement, uniform random selection

Recombination Sub-Tree Crossover

Mutation Sub-Tree Mutation

Survival Selection Truncation, k-Tournament Selection without replacement Bloat Control Parsimony Pressure

Termination Number of fitness evaluations

Your submission should also contain a report to document the findings of a 30-run experiment as well as files containing the world file (log) and tree from the solution with the highest fitness from all runs. In your report, include the following:

<ul>
<li>a plot showing fitness evaluations versus best and average population fitness averaged over 30 runs (like Assignments 1b-1d)</li>
<li>statistical analysis (F-test and t-test) comparing the best fitness obtained by each run to the data generated by the search algorithm in Assignment 2a</li>
<li>a brief discussion interpreting the results of the statistical tests</li>
<li>an informal comparison of the behavior of the best Assignment 2a agent and the best GP agent from
watching the visualization of the highest-scoring solutions from each algorithm The deliverables of this assignment are:

GREEN 1 your source code and completed notebook

GREEN 2 a PDF document headed by your name, AU E-mail address, and the string “COMP x66y Fall 2021 Assignment 2b”, where x and y need to reflect the section you are enrolled in, containing your report, including statistical analysis and plot(s)

GREEN 3 files containing any data you analyzed to write your report or generate your plot(s), in a format that can be easily understood by the TAs (if you think you might should include instructions on how to interpret your data, then you should!), as well as the highest-score-game-sequence all-time-step world files, and solution files (these should go in the repo’s worldFiles, and solutions directories respectively).
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
YELLOW 1 Investigate the role of parsimony pressure with respect to both parsimony technique (e.g., tree depth versus tree size) and parsimony coefficient (i.e., the amount of penalty incurred for bloat). This bonus investigation needs to be documented, including fitness evaluations versus a relevant tree complexity metric as well as the usual fitness evaluations versus best and average fitness plots averaged over all runs, and also including appropriate statistical analysis, in a separate section of your report marked as “Parsimony Investigation”. You also need to indicate in your source files any code which pertains to this bonus and additionally describe it in your report. Basically, you need to make it as easy as possible for the TAs to see with a glance what part of your submission pertains to this deliverable. Students enrolled in COMP 5660 can earn up to 15% bonus for this investigation. For students enrolled in COMP 6660 this will count for 15% regular points (not bonus) beyond the GREEN deliverables.

RED 1 Up to 10% bonus points can be earned by investigating having multiple simultaneous Pac-Man’s all employing identical controllers, where they all have to die for the game to end, and they share the same score (i.e., there’s no competition between the Pac-Man’s). You should add appropriate additional terminals, such as “Distance to nearest other Pac-Man”. This bonus investigation needs to be documented, including result plots, in a separate section of the required document marked as “Multiple Identical Pac-Man Controllers”. Basically, you need to make it as easy as possible for the TAs to see with a glance what part of your submission pertains to this bonus, and which does not. See the notebook for details on modifying the play GPac function to support this.

RED 2 Up to 15% bonus points can be earned by investigating the evolution of a controller that controls all ghosts, with the fitness of negative game score, and plays against a static Pac-Man strategy. You should add appropriate additional terminals, such as “Distance to nearest Pac-Man” and “Distance to nearest other ghost”. This bonus investigation needs to be documented in a separate section of the required document marked as “Multiple Identical Ghost Controllers”. You also need to indicate in your source files any code which pertains to this bonus and additionally describe it in your report. Basically, you need to make it as easy as possible for the TAs to see with a glance what part of your submission pertains to this bonus, and which does not. See the notebook for details on modifying the play GPac function to support this. Performing competitive co-evolution with ghosts will be a bonus on Assignment 2c.

Include a readme file to explain anything you feel necessary. The due date for this assignment is 10:00 PM on Sunday November 7, 2021.

</div>
</div>
<div class="layoutArea">
<div class="column">
Grading

The point distribution per deliverable category is as follows:

Assessment Rubric \ Deliverable Category Algorithmic

Logging and output files

Good programming including code reliability, commenting, correctness, &amp; practices Report

Statistical analysis

</div>
<div class="column">
Green Yellow Red 50% 55% 65%

10% 5% 5% 10% 10% 10% 15% 15% 20% 15% 15% 0%

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
Assignment 2c: Competitive Co-evolutionary Search

You need to co-evolve within a configurable number of fitness evaluations, where a fitness evaluation is defined to be a single game played, a GP controller for Pac-Man which generates the supposedly optimal valid action out of the 5 possible actions for Pac-Man and a map that provides the supposedly optimal challenge for Pac-Man. The type of co-evolution you will be using is competitive co-evolution [1, Section 15.3] employing two populations, one for the Pac-Man controllers and one for the maps. The recommended GP and EA approaches are the same as in Assignment 2b and Assignment 1b for Pac-Man controllers and maps, respectively. In this assignment, you are asked to complete the Jupyter notebook 2c notebook.ipynb and several other Python files as directed by the notebook.

You need at minimum to implement support for the following EA configurations, where operators with multiple options are comma separated, and operators need to be able to be configured independently for Pac-Man and maps respectively:

Pac-Man Representation Tree

Pac-Man Initialization Ramped half-and-half (see Section 6.4 in [1])

Pac-Man Parent Selection Fitness Proportional Selection, k-Tournament Selection without replacement, uniform random selection

Pac-Man Recombination Sub-Tree Crossover

Pac-Man Mutation Sub-Tree Mutation

Pac-Man Survival Selection Truncation, k-Tournament Selection without replacement

Pac-Man Bloat Control Parsimony Pressure

Map Representation Fixed-length binary string

Map Initialization Uniform random binary strings

Map Parent Selection Fitness Proportional Selection, k-Tournament Selection without replacement, uni- form random selection

Map Recombination Uniform, 1-Point

Map Mutation Binary String Mutation

Map Survival Selection Truncation, k-Tournament Selection without replacement Termination Number of fitness evaluations

Note: If μ of the Pac-Man population is not equal to μ of the map population or λ of the Pac-Man population is not equal to λ of the map population, some controllers or maps will have to be used more than once to complete all fitness evaluations. If you use a controller or map more than once, simply take the average of all games the controller or map played for fitness and store the game log of the game that was better for the individual in question (e.g., Pac-Man uses the log with the higher score and a map uses the log with the lower score).

For each experiment in this assignment you are asked to submit highest-score-game-sequence all-time-step world files from an exhibition game (i.e., an extra match does not count as an evaluation) played between your best Pac-Man controller and Map from the final generation of the same run. Similarly, you will produce two solution files per experiment: one for the Pac-Man controller and one for the map used in this game. Note that for all deliverables except RED 4, acceptable statistical analysis consists of reporting the mean and standard deviation of the best fitness of the final generation of each species across all runs in your experiment.

The deliverables of this assignment are:

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
GREEN 1 your source code and completed notebook

GREEN 2 a document in PDF format headed by your name, AU E-mail address, and the string “COMP

x66y Fall 2021 Assignment 2c”, where x and y need to reflect the section you are enrolled in’, containing:

Methodology Describe the custom parts of your EA design, such as your function and terminal sets, as well as your approach to performing adversarial evaluations, in sufficient detail to allow someone else to implement a functionally equivalent EA, and explain your EA design decisions.

Experimental Setup Provide your experimental setup in sufficient detail to allow exact duplication of your experiments (i.e., producing the exact same results within statistical margins) and justify your choice of EA strategy parameters.

Results List your experimental results in both tabular (mean and standard deviation) and graphical formats (box plots preferred).

Discussion Discuss any notable behavioral characteristics of the Pac-Man controllers when compared to the controllers found in Assignment 2b. In particular, we want you to report on how and if agent behavior changed in the presence of co-evolving maps.

Conclusion Conclude your report by stating your most important findings and insights in the con- clusion section.

Bibliography This is where you provide your citation details, if you cited anything. Only list refer- ences here that you actually cite in your report.

Appendices If you have more data you want to show than what you could reasonably fit in the body of your report, this is the place to put it along with a short description.

GREEN 3 files containing any data you analyzed to write your report or generate your plot(s), in a format that can be easily understood by the TAs (if you think you might should include instructions on how to interpret your data, then you should!), as well as the highest-score-game-sequence all-time-step world files, and solution files (these should go in the repo’s worldFiles, and solutions directories respectively).

YELLOW 1 Investigate under what circumstances co-evolutionary cycling occurs in Pac-Man and maps and adding a section to the document to describe all aspects of your investigation, including CIAO plots [2] to visualize your findings. You need to include all your related configuration, data, world, and solution files and clearly indicate in your source files any code which pertains to this deliverable. Basically, you need to make it as easy as possible for the TAs to see with a glance what part of your submission pertains to this deliverable, and which does not. Students enrolled in COMP 5660 can earn up to 10% bonus for this investigation. For students enrolled in COMP 6660 this will count for 10% regular points (not bonus) beyond the GREEN deliverables.

RED 1 Up to 10% bonus points can be earned by investigating the co-evolution of a controller that controls all ghosts, with the fitness of negative game score, and plays against co-evolving Pac-Man controllers on a static map. You should add appropriate additional terminals, such as “Distance to nearest Pac-Man” and “Distance to nearest other ghost”. This bonus investigation needs to be documented in a separate section of the required document marked as “Pac-Man and Ghost Co-Evolution”. You also need to indicate in your source files any code which pertains to this bonus and additionally describe it in your report. Basically, you need to make it as easy as possible for the TAs to see with a glance what part of your submission pertains to this bonus, and which does not.

RED 2 Up to 10% bonus points can be earned by investigating the cooperative co-evolution of a Ghost controller with a map using a static Pac-Man strategy and negative game score as fitness for both species. This bonus investigation needs to be documented in a separate section of the required document marked as “Map and Ghost Cooperative Co-Evolution”. You also need to indicate in your source files any code which pertains to this bonus and additionally describe it in your report. Basically, you need to make it as easy as possible for the TAs to see with a glance what part of your submission pertains to this bonus, and which does not.

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
RED 3 Up to 10% bonus points can be earned by investigating 3-species co-evolution Pac-Man controllers, maps, and Ghost controllers. This bonus investigation needs to be documented in a separate section of the required document marked as “3-Species Co-Evolution”. You also need to indicate in your source files any code which pertains to this bonus and additionally describe it in your report. Basically, you need to make it as easy as possible for the TAs to see with a glance what part of your submission pertains to this bonus, and which does not.

RED 4 You may have noticed that this assignment doesn’t contain any request for rigorous statistical anal- ysis. This is because performing meaningful statistical analysis is often nuanced (and computationally expensive) for problems without an inherent absolute fitness metric (like GPac). For up to 10% bonus points, design and implement a method for performing a meaningful, fair, and consistent comparison between solutions from any two co-evolution configurations/experiments co-evolving the same species, then perform statistical analysis using metrics obtained from your comparison method. Your method and statistical analysis results (with your interpretation of results) should be documented in a separate section of the required document marked as “Statistical Analysis of Co-Evolution”. You also need to indicate in your source files any code which pertains to this bonus and additionally describe it in your report. Basically, you need to make it as easy as possible for the TAs to see with a glance what part of your submission pertains to this bonus, and which does not.

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
References

</div>
<div class="column"></div>
<div class="column">
&nbsp;

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
10%

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
10%

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
10%

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
10%

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
[1] A. E. Eiben and J. E. Smith, Introduction to Evolutionary Computing. Second Edition, Springer-Verlag, Berlin Heidelberg, 2015, ISBN 978-3-662-44873-1.

[2] Dave Cliff and Geoffrey F. Miller, Tracking the red Queen: Measurements of Adaptive Progress in Co- Evolutionary Simulations. In Advances in Artificial Life, Lecture Notes in Computer Science, Volume 929, Pages 200-218, Springer-Verlag, Berlin Heidelberg, 1995, ISBN 978-3-540-59496-3. http://www. cs.uu.nl/docs/vakken/ias/stuff/cm95.pdf

</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
</div>
