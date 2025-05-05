# cse102-assignment-6-a-mini-game-for-2-players-solved
**TO GET THIS SOLUTION VISIT:** [CSE102 Assignment 6-A mini game for 2 players Solved](https://www.ankitcodinghub.com/product/cse102-assignment-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101988&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE102 Assignment 6-A mini game for 2 players Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this assignment, you are asked to write a mini game for 2 players. The game is described below.

In this game, there are two seperate roads for the players. The player who will start first will be chosen by tossing the dice. Likewise, the players move along their way (clockwise) by tossing the dice. If a player ends up their movement on a penalty point (indicated by X) they should take 2 steps backward. Whoever ends up on (or beyond) the finish line (indicated by _) wins the game.

</div>
</div>
<div class="layoutArea">
<div class="column">
•

• • • •

</div>
<div class="column">
The dots are used to draw a path for the players. You may use different characters such as “|” and “-”.

-&gt; indicates the position of the player 1. -&gt; indicates the position of the player 2. -&gt; indicates the finish line.

-&gt; indicates the penalty points.

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 1 of 2

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
CSE102 – Spring 2022 Homework #6 How to program the game?

</div>
</div>
<div class="layoutArea">
<div class="column">
– – –

–

– – – –

–

– –

–

→ → → → → →

</div>
<div class="column">
Before starting to code, please watch the video which shows the playing of the game.

The whole game area should be saved in a 2D array with 15 rows and 30 columns.

Each item in the game; such as the positions of the players, finish line etc. should be the elements of the array.

There should be 3 penalty points for Player 1 and 6 penalty points for Player 2. The positions of the penalty points:

o For Player 1 -&gt; (1, 14), (7, 28) and (13, 14)

</div>
</div>
<div class="layoutArea">
<div class="column">
o For Player 2 -&gt; (3, 10), (3, 18), (5, 26), (10, 26), (11, 10) and (11, 18)

The position of the finish lines should be (2,1) for Player 1 and (4,3) for Player2.

The positions of the players at the beginning are (1,1) for Player 1 and (3,3) for Player 2.

The size of the game area and the positions are constant.

When the game starts, the positions of the players will change repeatedly. The program should update their positions in the array.

According to the position of a player when they toss, the player’s position may change by its row and/or column index. Be careful at the corners of the road.

Using pointers are not allowed, use a practical way to repeat the steps.

Dice tossing should be handled by generating a random integer by using the following function.

</div>
</div>
<div class="layoutArea">
<div class="column">
o rand () -&gt; returns a positive integer or 0. Do not remember that you need a random integer in a range of [1,6].

</div>
</div>
<div class="layoutArea">
<div class="column">
o Add srand(time(NULL)); in your main function. Otherwise the rand() function will return the same integers regardless of a rerun of the program.

</div>
</div>
<div class="layoutArea">
<div class="column">
o Include stdlib.h and time.h libraries to use these functions.

You can write and use your own functions for a clean coding, but the followings are necessary:

</div>
</div>
<div class="layoutArea">
<div class="column">
o void printMap () -&gt; prints the game area, use the parameters you will need if any.

o int dice () -&gt; returns a random integer in a range of [1,6]

o intstartGame()-&gt;decides(accordingtodicenumbers)andreturnsthe#oftheplayer

</div>
</div>
<div class="layoutArea">
<div class="column">
who will start the game.

Use the parameters you need (if any) as the inputs of the functions.

Use different colors when you print the array as shown above.

When a player steps backward because of a penalty, print this information. Using libraries other than stdio.h and the ones specified above is not allowed. Add comments to your code and hand in a .c file only.

See the attached video for a visual example of the game.

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 2 of 2

</div>
</div>
</div>
