COMPANY:CODTECH IT SOLUTIONS PVT
NAME: Vishakha Dayanand Pati
 Intern ID :CT08LNI
 DOMAIN: Frontend Web Development.
 DURATION:4 WEEKS
 MENTOR:Neela Santosh
 DESCRIBE:
 HTML:
 A container div holds the quiz content with a header (h1).
The quiz div will likely display the quiz questions dynamically The result div is where the result will be shown after submitting the quiz.
There are three buttons:
submit: To submit the quiz.
retry: To retry the quiz initially hidden with the class "hide".
showanswer: To show the answers also hidden initially.text2.js is included, which likely handles the functionality of the quiz, such as loading questions, submitting answers, and displaying results.
style2.css: Ensure that this CSS file provides the necessary styles, including the .hide class to hide elements and styling for the quiz layout and buttons.
text2.js: Make sure this script dynamically generates quiz questions, handles user interactions, calculates the score, and shows the appropriate result.
CSS:
margin: 0; padding: 0;: These properties remove any default margin and padding that browsers apply to the body element.
display: flex;: This enables flexbox layout for the body, allowing easy centering of its childrenlike the .container.
justify-content: center;: This centers the content horizontally within the body using flexbox.
align-items: center;: This centers the content vertically within the body using flexbox.background-color: #fff;: Sets the background color of the .container to white.
padding: 20px;: Adds 20 pixels of space inside the container around its content.
border-radius: 10px;: Rounds the corners of the .container by 10 pixels, giving it a soft, smooth look.

he body is styled to be a full-screen page with a centered container (thanks to flexbox) and a background image (photo2.jpg).
The .container holds the quiz content, which is styled with padding, rounded corners, and a shadow for a clean and modern look.
Buttons are styled to be green, with a hover effect that changes their color to a darker green.
The .hide class is used to hide buttons (likely in JavaScript to control visibility during the quiz).
The header (<h1>) and result section are styled for readability, with spacing around them to avoid crowding.

JAVASCRIPT:
Quiz Data: Stores questions, options, and correct answers.
Shuffle Function: Randomizes the order of options for each question.
Dynamic Question Display: Displays one question at a time, with shuffled options.
Answer Handling: Tracks score and incorrect answers, moves through questions.
Result Display: After the quiz, shows the score and incorrect answers.
Retry and Show Answers: Allows the user to restart the quiz or see all the answers.
The displayQuestion() function is called initially to start the quiz by displaying the first questio


















C![Image](https://github.com/user-attachments/assets/0e6f0c1f-a96e-43c8-8376-317d591ce7bc)
