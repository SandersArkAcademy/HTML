# Lessons for the week of August 15 - 19, 2022
## Tables
Tables are a way to format information and data. In this lesson we will explore how to create tables in HTML.

 Open Visual Studio Code
2. Create a new file "SimpleTableHelper.html"
3. Type in the section below:
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Simple table example.
        </title>
    </head>
    <body>
        <h1>Making a simple table</h1>
        <style>
            table, th, td
            {
                border: 1px solid black
            }
        </style>
        <table>
            <tr>
                <th>Among Us Player name</th>
                <th>Wins</th>
                <th>Losses</th>
            </tr>
            <tr>
                <td>Jon</td>
                <td>0</td>
                <td>1</td>
            </tr>
            <tr>
                <td>Rose</td>
                <td>1</td>
                <td>3</td>
            </tr>
        </table>
    </body>    
</html>
```
4. Run your html page and show Mom and Dad.

## Styles
Now let us change the color or the border by changing the style.

Change line 13 from below
``` border: 1px solid black ```
to
``` border: 10px solid red ```

1. Run your code and see the difference.  Show Mom and Dad

## Change the values of the table.

1. Change Jon to have 5 wins. (Change line 24) from below
```<td>0</td>```
to
```<td>5</td>```
2. Run your code and see the difference.  Notice that the value in the table displays different. Show Mom and Dad.

3. Change the style back to black and 2px (pixels thick)
Change line 13 from below
``` border: 10px solid red ```
to
``` border: 2px dotted black ```

4. Run you code and see the difference. Notice the lines of the table display different.  Show Mom and Dad.



