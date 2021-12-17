<!-- what do you hope to get out of this project? -->


<!-- which of your strengths/values results most resonates with you? -->


<!-- what seems the most difficult about this prodject? -->


<!-- what hard for you a few weeks ago, but now you feel confident with it? -->

<!-- server setup -->

Terminal command: npm init –yes
Terminal command: npm install express –save
Add .gitignore file
In .gitignore file “node_modules/”
In .json file under “test” write “start”: “node server/server.js” (nodemon instead of node)
Terminal command: npm start					    ↑
Create variable to call express and then a variable to run express	    ↑
Terminal command: npm install nodemon (will have to do for each project)
Terminal command: npm install body-parser


technical tasks
[X] prodject setup
    [X] server.js file
    [X] set up express
    [X] .gitignore file
    [X] modify .json file
        [X] nodemon
    [X] bodyParser
    [X] server folder
       [X] index.html file
        [X] scripts folder
            [X] client.js file
            [X] jquery.js file
        [X] styles folder
            [X] styles.css file
[X] html file
    [X] source js, jQuery, and css
    [X] form
        [X] input field for each player number guess
        [X] submit
[ ] CSS file
    [ ] add a little style
[ ] server.js setup
    [X] setup port 5000
    [X] setup static files
    [X] generate random number function 1 to 25
    [X] '/guess-history GET
    [X] '/guess POST
    [X] store the prevous guess's
    [X] send results for guess's
        [X] high, low, correct
    [X] reformate guessHistory as object
[ ] client.js
    [X] source jQuery
    [X] set up functioning submit
    [X] set up AJAX
    [X] append guess's to DOM
    [X] congradulate if winner
    [X] total guess's counter
    [X] .empty()

<!-- notes -->
[ ] 
{
    guessKay: xxx,
    resultKay: high/low/correct
}