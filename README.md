## WEEK 1: ASSIGNMENT

Your first assignment is to create a basic web page with HTML and CSS. Your page must
include the picture of any actor/actress, a heading with their name, and a link to their wikipedia
page. Underneath should be a table that lists some their movies, under table headers labeled title
and year. Finally, add an input date form that allows for the user to choose the month, day and
year from a dropdown menu.

Use CSS to manipulate style

## Extra Tasks

Aside from practicing was done in class, there are a few extra tasks for practice. Instructions are
provided in alpha branch code.

1. Add a footer to your page: The footer must inform the user that the site was "Posted by:" "Your Name".
   The footer must also provide your "Contact Information:" in the form of an email. You will use an anchor
   tag to set up your email display/link. The link will lead the user to a blank, ready to send email addressed
   to you (whatever email address you use).

2. Style your footer

3. Review basic terminal commands (cd, ls, mkdir, cat). Find 3 new basic commands and write a brief summary
   of what each one does. Then practice as many terminal commands as you can. You can make new directories, change
   directories, make new files, list the files in a directory etc.

## WEEK 1: ASSIGNMENT SETUP

1.  In your terminal command, type `npm install live-server -g`

    This will install a simple, zero-configuration command-line http server.

2.  Next you must clone a git repository that contains week one assignment instructions
    and a basic html shell for your first html/css project. There are three branches in
    the repo you will clone. The `alpha` branch will contain your assignment, with instructions
    in place of code. The `beta` will contain the completed code and serve as your answer key.
    While completing the alpha branch, simply refer to `beta` for help.

3.  Remember your Terminal Commands!

    Move to the directory you would like to clone your repo using cd (change directory)

    Clone your repo with what ever name you like typing git clone followed by the link and
    then the new name of your repo

    `git clone https://github.com/t1cgAcademy/Web-Dev-101-Week-1-Assignment.git whateverNameYouWantHere`

    Or you can simply clone the repo and get the default name

    `git clone https://github.com/t1cgAcademy/Web-Dev-101-Week-1-Assignment.git`

    Open your cloned code in Atom or Visual Studio Code

        `atom .` or `code .`

    If the above opening command does not work, you can manually open using your graphical user interface

4)  Sanity Check!!! It is always important to make sure that your code will run as
    intended by entering something simple. Here, we want to make sure that the http server (live-server)
    we downloaded from NPM will run our simple HTML shell. In your index.html file, inside
    the body tag, enter the following line...

- `<div>Hello World</div>`

5. Press `command s` on your keyboard to save the changes.

6. Now, go to your terminal command, make sure you are in your cloned git directory.

7. Now run your simple http server by typing `live-server`. Note: you must be in the projects directory.

   - When you run this command, you will see the following line... `Starting up http-server, serving ./ on: http://0.0.0.0:[someport]` This line shows the local port where your code will run.

8. Go to your browser and enter the following address with the appropriate port... `http://localhost:[someport]/`

Now you should be able to see your "Hello World" in the upper left hand corner of your browser.

Congratulations! You have just run your first HTML code. Now, get into `alpha`, follow the instructional
comments and get coding.
