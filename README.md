Download Link: https://assignmentchef.com/product/solved-sdev-homework2-javascript
<br>
5/5 - (1 vote)

<ol>

 <li>There are in total 3 questions in this homework and each question is mandatory.</li>

 <li>The instructions for each question are presented in each part below.</li>

 <li>Please follow the instructions carefully.</li>

 <li>You are only supposed to modify the JavaScript files.</li>

 <li>Please open the HTML file in your browser to see if your code works and open it up in a text editor like Sublime to read through the code and understand the function calls.</li>

 <li>We’ve 2 Bonus questions worth 10 points each with instructions in its own section</li>

</ol>

<p class="alignleft h5">Part 1: Sign Up Dialogs with Modals (32 points)

<button class="btn btn-primary btn-sm alignbtn" type="button" data-toggle="collapse" data-target="#multiCollapseExample2" aria-expanded="false" aria-controls="multiCollapseExample2">Expand</button>

The first portion of this assignment is dedicated to understanding modals. As shown in the example below, modals allow you to incorporate a pop-up dialog into your website for any interactions that you want to happen in a sub-window on your website. Modals are typically used for log-in and sign-up interfaces, but could be used to display any content on your webpage.

<button class="btn btn-primary" type="button" data-toggle="modal" data-target="#exampleModalCenter">Launch demo modal</button>

You will be creating a modal to allow users to sign up for a website with their name and a password. The example provided below has the input components your modal is expected to accept, but using Javascript and regular expressions you will be adding in scripts to make the password validation functional.

<a class="btn btn-primary" href="#myModal" data-toggle="modal">Click to Open Sign Up Modal</a>

For the following questions, you will likely find it helpful to consult these resources:

<button class="btn btn-primary" type="button" data-toggle="modal" data-target="#resourceModal">Resource Links</button>

<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#part1_q1_collapse" aria-expanded="false" aria-controls="part1_q1_collapse">Question 1.1 </button>

<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#part1_q2_collapse" aria-expanded="false" aria-controls="part1_q2_collapse">Question 1.2 </button>

<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#rule_3_collapse" aria-expanded="false" aria-controls="rule_3_collapse">Question 1.3 </button>

<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#rule_4_collapse" aria-expanded="false" aria-controls="rule_4_collapse">Question 1.4 </button>

Download the archive <a href="../resources/hw2/signup-modal.zip" target="_blank" rel="noopener">signup-modal.zip</a>

You will be editing the <i>login.js</i> and <i>login.css</i> files. You should not need to edit <i>login.html</i> in order to make the password validation functional, but that is where the changes you make will be evident.

For these questions, you will modifying the javascript code we provide in the file <i>login.js</i> in /resources/js/login.js to match password properties. We have provided the skeleton code for a function called openModal() that will handle your regex expressions. We have provided comments in the included file to

<ol>

 <li>Write the regular expression for Javascript to match lowercase characters.</li>

 <li>Write the regular expression for Javascript to match uppercase characters.</li>

 <li>Write the regular expression for Javascript to match digits.</li>

 <li>Change the minLength variable such that the length of the password is at least 8 characters.</li>

</ol>

You are going to work with on the CSS using the classLists feature in this question.



<strong>Overall Objective:</strong>The password needs to have a lowercase character, an uppercase character, a digit, should match the confirm password field and should be 8 charcters long at least.If you notice after clicking the “Click to Open Signup Modal”, right at the bottom there are 5 rows. For example: <a href="https://imgur.com/5qkA7YV"><img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

   <noscript>

    <img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" title="source: imgur.com" src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" data-recalc-dims="1">

    </noscript>

   </noscript>

  </noscript></a>What you are going to be doing is playing with the bootstrap classes to change there from an red with a cross to green with a check mark when the condition is satisfied

<b>For an example, let’s consider just the lowercase condition</b>

<ul class="list-group-flush">

 <li class="list-group-item">In the beginning, this is what you have: a red cross with “A lowercase letter in red”: <a href="https://imgur.com/5qkA7YV"><img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

   <noscript>

    <img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

     <noscript>

      <img decoding="async" title="source: imgur.com" src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" data-recalc-dims="1">

     </noscript>

    </noscript>

   </noscript></a></li>

 <li class="list-group-item">If a lower case is entered you need to make the following display: <a href="https://imgur.com/Opzzdfl"><img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/Opzzdfl.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

   <noscript>

    <img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/Opzzdfl.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" title="source: imgur.com" src="https://i0.wp.com/i.imgur.com/Opzzdfl.png?w=980&amp;ssl=1" data-recalc-dims="1">

    </noscript>

   </noscript></a></li>

</ul>

<strong>There is one if-else block for each of the following:</strong>

<ul class="list-group-flush">

 <li class="list-group-item">If lowerCaseLetters regex matches or not.</li>

 <li class="list-group-item">If upperCaseLetters regex matches or not</li>

 <li class="list-group-item">If numbers regex matches or not.</li>

 <li class="list-group-item">If the minimum length of the password is &gt;= minLength or not.</li>

</ul>

<b>First, use console.log to check the value of any classList, for example:</b>

<ul class="list-group-flush">

 <li class="list-group-item">console.log(letter.classList)</li>

 <li class="list-group-item">You should an array be getting a single element, with a value “invalid”</li>

</ul>

<b>Let’s dive deeper on how to achieve what needs to be done. Let’s consider just the lowercase condition again.</b>

<ul class="list-group-flush">

 <li class="list-group-item">In the beginning, this is what you have: a red cross with “A lowercase letter in red”: <a href="https://imgur.com/5qkA7YV"><img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

   <noscript>

    <img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

     <noscript>

      <img decoding="async" title="source: imgur.com" src="https://i0.wp.com/i.imgur.com/5qkA7YV.png?w=980&amp;ssl=1" data-recalc-dims="1">

     </noscript>

    </noscript>

   </noscript></a></li>

 <li class="list-group-item">If we enter the “if” condition, that would mean that we have a lowercase character entered. So the above needs to change.</li>

 <li class="list-group-item">To do this, all you need to do is <span style="color: red;">remove</span> the invalid class, and <span style="color: red;">add</span> the correct class that would have the display look as follows: <a href="https://imgur.com/Opzzdfl"><img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/Opzzdfl.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

   <noscript>

    <img decoding="async" title="source: imgur.com" data-recalc-dims="1" data-src="https://i0.wp.com/i.imgur.com/Opzzdfl.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" title="source: imgur.com" src="https://i0.wp.com/i.imgur.com/Opzzdfl.png?w=980&amp;ssl=1" data-recalc-dims="1">

    </noscript>

   </noscript></a></li>

</ul>

<b>This needs to be done everywhere we have the classList.add() function and classList.remove() function.</b>

<ul class="list-group-flush">

 <li class="list-group-item">You can look up the names of the css classes from the login.css file.</li>

 <li class="list-group-item">The class that needs to go into these functions is defined in the CSS file ‘login.css’. <span style="color: red;">Do not use classes from outside this file and do not add classes to this file.</span></li>

</ul>

<b>Rubric:</b>

<ol class="list-group-flush">

 <li class="list-group-item">“A Lowercase letter” changes from red to green after lower case is entered in the password field. If a lower case is removed and no other lower case characters remain it moves from green to red too.</li>

 <li class="list-group-item">“A capital(Uppercase) letter” changes from red to green after upper case is entered in the password field. If a upper case and no other uppper case characters remain it moves from green to red too.</li>

 <li class="list-group-item">“A number” changes from red to green after digit is entered in the password field. If a digit is removed and no other digits remain it moves from green to red too.</li>

 <li class="list-group-item">“Minimum 8 characters” changes from red to green after password of length greater than 7 is entered. If characters are deleted and the length of the password is less than 8, it moves from green to red.</li>

 <li class="list-group-item">“Password and Confirm Password Match” changes from red to green after both values are entered in the password fields. If they dont match, it needs to move from green to red</li>

</ol>

<strong>Overall Objective:</strong>Validate that the text in the password field and confirm password field are equal.

<ul class="list-group-flush">

 <li class="list-group-item">You need to validate that the text in the password field and confirm password field are equal.</li>

 <li class="list-group-item">For two points, all that you have to do is look at the line “var passEqualsConfPass = false;” and replace false, with the correct variable comparison to make sure that the passwords match.</li>

 <li class="list-group-item">For another 2 points, repeat what you did in Question 1.2 for the if and else conditions for the match element.</li>

</ul>

<strong>Overall Objective:</strong>Enable the Button when all the conditions for a valid password are satisfied.

<ul class="list-group-flush">

 <li class="list-group-item">What you will notice is that if any of the conditions for the password have a red cross, the button is disabled.</li>

 <li class="list-group-item">What you need to do is in the enableButton() function, there is a line that says “var condition = false”, replace the false with the right condition such that if we have all green ticks, the button gets enabled and you can click it. <b>POINTS: 10</b></li>

 <li class="list-group-item">Click the button to see a successful Modal</li>

</ul>

<p class="alignleft h5">Part 2: Theory (18 points)

<button class="btn btn-primary btn-sm alignbtn" type="button" data-toggle="collapse" data-target="#multiCollapseExample3" aria-expanded="false" aria-controls="multiCollapseExample3">Expand</button>

Download the archive to work on this section <a href="../resources/hw2/Theory.zip">Theory.zip</a>

This folder contains two files:

<pre>  |--Theory    |--coding.html    |--coding.js</pre>




You will find instructions in the <b>coding.html</b> file to complete this section of the homework.

Make sure not to modify the HTML/CSS or the existing JS functions. Add JS functions where necessary and reference them in the given fuctions.

<p class="alignleft h5">Part 3: Tic-Tac-Toe (50 points)

<button class="btn btn-primary btn-sm alignbtn" type="button" data-toggle="collapse" data-target="#multiCollapseExample4" aria-expanded="false" aria-controls="multiCollapseExample4">Expand</button>

Download the archive <a href="../resources/hw2/tic-tac-toe.zip" target="_blank" rel="noopener">tic-tac-toe.zip</a>

<pre>Directory Structure:    |--tic-tac-toe      |--tic-tac-toe.html      |--rules.js</pre>




Implement the functions defined in <b>rules.js</b>

The tic-tac-toe board verification logic can be found <a href="../resources/hw2/Board-verification-logic.pdf" target="_blank" rel="noopener">here</a>


You’ll not be modifying <b>tic-tac-toe.html</b>

<h4>Implement these rules Rules in <b><u>rules.js</u></b></h4>

These same rules are defined in <b><u>rules.js</u></b>

<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#rule_1_collapse" aria-expanded="false" aria-controls="rule_1_collapse">Rule 1 –</button>

<ol>

 <li>Input fields for the player 1 or player 2 names cannot be empty. Show an alert if the user tries to start the game without entering these two fields. <a href="https://i.imgur.com/v0N8FeP.png" target="_blank" rel="noopener">See picture</a></li>

 <li>The game should not start if any of these fields are empty.</li>

 <li>Once the game has started, these two input fields should be disabled. The two fields should show the Move types of player 1 and player 2 (X or O) <a href="https://i.imgur.com/yhEu14J.png" target="_blank" rel="noopener">See picture</a></li>

 <li>Once the game has started, The turn information should be should be shown.<a href="https://i.imgur.com/SovbuDk.png" target="_blank" rel="noopener">See picture</a>Note: Turn starts with “X”. The turn is shown in “Bold”.</li>

 <li>Once the game has started, click on begin play should alert – “Already started. Please <b>Reset Play</b> to start again.” <a href="https://i.imgur.com/nXimgDS.png" target="_blank" rel="noopener">See picture</a></li>

</ol>

<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#rule_2_collapse" aria-expanded="false" aria-controls="rule_2_collapse">Rule 2 – </button>

<ol>

 <li>The reset play button should reset the whole game. (At any time when reset is clicked – All the three text boxes should be cleared and Turn should be set to the default message.) <b>POINTS: 2</b></li>

 <li>The text boxes for entering name should be enabled back. <b>POINTS: 2</b></li>

 <li>The Tic Tac Toe Grid should be set to its default entries. <b>POINTS: 2</b></li>

 <li>Clicking reset play again and again shall have the same effect every time (or no effect when clicked multiple times). <b>POINTS: 2</b>Note: Do not just reload the page. (No marks will be awarded for that.)</li>

</ol>

<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">Rule 3 – </button>

<ol>

 <li>The text box to enter Move should only take values (A1, A2, A3, B1, B2, B3, C1, C2, C3) (Hint: It will be validated after clicking on <b>Play</b>) <b>POINTS: 3</b></li>

 <li>Invalid moves should be reported by an alert message.(You are encouraged to use Modal which you learned in HW1 – Usage is not mandatory.) <b>POINTS: 2</b></li>

 <li>If the move is a valid move, the grid should be updated with the correct move (Player 1 is always – ‘X’, and Player 2 is always ‘O’ (This is not zero!)) – The turn information should also be updated (Example: After the first move – turn is set to ‘O’ <a href="https://i.imgur.com/mQB9CYX.png" target="_blank" rel="noopener">See picture</a> <b>POINTS: 4</b></li>

 <li>A move should always be a valid move. (Example: If say a move was made in the already filled cell, it should be invalidated with an alert.) <b>POINTS: 2</b></li>

 <li>If the game has not started, clicking on <b>Play</b> should give an alert “The game has not started.” <b>POINTS: 2</b></li>

 <li>After any move, the state of the table should be validated.(See the document attached in HW2 files to better understand). If there is a winner – Show it in an alert message – (Ex – Winner is X or O) – Displaying name is not important. <a href="https://i.imgur.com/FzQMYXP.png" target="_blank" rel="noopener">See picture</a> <b>POINTS: 13</b></li>

 <li>The game should reset itself once a winner is determined. <b>POINTS: 2</b></li>

 <li>After all the moves have exhausted, you’re not required to display any message. (It should be obvious to Reset play.)</li>

</ol>

<p class="alignleft h5">Bonus Question

<button class="btn btn-primary btn-sm alignbtn" type="button" data-toggle="collapse" data-target="#multiCollapseExample5" aria-expanded="false" aria-controls="multiCollapseExample5">Expand</button>

<ol>

 <li><b>Bonus 1: </b>– Add the Tic-Tac-Toe app to your website (Hosted using GitHub Pages) that you created in HW1 . Create a hyperlink from your homepage.</li>

 <li><b>Bonus 2: </b>– Unit TestingYou’ll need to setup <em>Jasmine</em> in your part3 directory and write 3 unit tests for the <code>isEmpty</code> predefined in the rules.js. Create a .spec file and write 3 unit tests. These tests will call the <code>isEmpty</code> with the following values

  <ol>

   <li>Any non-empty string of your choice – assert that it returns false</li>

   <li>“” (empty string) – assert that it returns true</li>

   <li>undefined – assert that it returns true</li>

  </ol>Create a SpecRunner.html page that runs these tests when opened. You can follow <a href="https://howtodoinjava.com/javascript/jasmine-unit-testing-tutorial/">this</a> tutorial to learn about Jasmine, and look at a simple example <a href="https://embed.plnkr.co/plunk/ODgvKr">here</a>.</li>