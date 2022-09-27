# Lesson for the week of 8/21/2022 - 8/28/2022

## Description
This week we will be studing Anchor tags and multiple pages. We will create a group of webpages to navigate locally through.

We will also learn about Github and how to work with it.

## Steps
1. Dad will work with you on creating a new branch on GitHub.
2. Create a folder Lesson_3Wrk
3. Create a file called index.html
4. Add text below
```
<!DOCTYPE html>
<html>
    <head>
        <title>Main Among us page</title>
        <style>
            #starterImage{
                text-align: center;
                width: 500px;
            }
        </style>
    </head>
    <body>
        <img id="starterImage" src="../Images/red-among-us-png-842x1024.png">
        <h1>Among us is an awesome game</h1>
        <ul>
            <li><a href="./Imposter.html">What is an "Imposter"</a></li>
            <li><a href="./HowToWin.html">How to win.</a></li>
        </ul>
    </body>
</html>
```
5. Create a file called HowToWin.html
6. Add text below
```
<!DOCTYPE html>
<html>
    <head>
        <title>Main Among us page</title>
        <style>
            #starterImage{
                text-align: center;
                width: 500px;
            }
        </style>
    </head>
    <body>
        <img id="starterImage" src="../Images/red-among-us-png-842x1024.png">
        <h1>How to Win!</h1>
        <a href="./main.html">Go gack to the main page.</a>
        <h2>Find the Imposter</h2>
        <p>
            When on the call tell everyone if you saw someone go in a grate.
        </p>
    </body>
</html>
```
7. Open index.html and test the link to the page How to Win.
8. Try the link to get back to the main page. It will throw an error.
9. Look at the code in HowToWin.html notice the ```<a href="./main.html">``` it should be ```<a href="./index.html">```
This is because the file name is not main but index.html.  
10. Open index.html and test the link to the page How to Win.
11. Try the link to get back to the main page. It works
12. Create a file called Imposter.html
13. Add text below
``` 
<!DOCTYPE html>
<html>
    <head>
        <title>Main Among us page</title>
        <style>
            #starterImage{
                text-align: center;
                width: 85%;
            }
        </style>
    </head>
    <body>
        <img id="starterImage" src="../Images/Among-Us-NEW-2.png">
        <h1>Imposters</h1>
        <a href="./index.html">Go gack to the main page.</a>
        <table>
            <tr>
                <th>Jump to section.</th>
            </tr>
            <tr>
                <td><a href="#WhatAreThey">WhatAreThey</a></td>
            </tr>
            <tr>
                <td><a href="#WhoCanBeAnImposter">Who can be an imposter?</a></td>
            </tr>
            <tr>
                <td><a href="#textBlock1">textBlock1</a></td>
            </tr>
            <tr>
                <td><a href="#textBlock2">textBlock2</a></td>
            </tr>
            <tr>
                <td><a href="#textBlock3">textBlock3</a></td>
            </tr>
        </table>
        <h2 id="WhatAreThey">What are they?</h2>
        <p>Imposters are characters working against the team.</p>
        <a href="#starterImage">Go back to the top.</a>
        <br></br>
        <h2 id="WhoCanBeAnImposter">Who can be an imposter?</h2>
        <p>Anyone playing could be the imposter.</p>
        <a href="#starterImage">Go back to the top.</a>
        <br></br>
        <h2 id="textBlock1">Here is just some text.</h2>
        <p>Add a lot of text here</p>
        <a href="#starterImage">Go back to the top.</a>
        <br></br>
        <h2 id="textBlock2">Here is just some text.</h2>
        <p>Add a lot of text here</p>
        <a href="#starterImage">Go back to the top.</a>
        <br></br>
        <h2 id="textBlock3">Here is just some text.</h2>
        <p>Add a lot of text here</p>
        <a href="#starterImage">Go back to the top.</a>
        <br></br>
    </body>
</html>
```
14. Show Dad your code and we will go over uploading to GitHub.