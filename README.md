# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

Step 1:
Clone the git hub repository to your theia.ide .Start a new project folder.Create a new app for your web application.

Step 2:
Create a template for your simple calculator .Write the appropiate HTML and CSS code.

Step 3:
Now run the server and check whether your webapplication is working.If it's working good then let's move to the next step.

Step 4:
Now add Script tag to use javascript in your html file. Write the appropiate javascript code to do basic arithmetic calculations.

Step 5:
Now use CSS tags to align the buttons in a proper way for better appearance.

Step 6:
Validate the HTML and CSS code.

Step 7:
Publish the website in the given URL.


## PROGRAM :
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>SEC Demo on Calculator</title>
        <style>
        table{
            border: 10px solid black;
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 5px solid yellowgreen;
            padding: 20px 30px;
            font-size: 24px;
            font-weight: bold;
            border-radius: 2px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color: red;
            border-radius: 2px;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:black;">Standard Calculator</h1>
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="1" onclick="result.value+='1'"></td>
                <td><input type="button" value="2" onclick="result.value+='2'"></td>
                <td><input type="button" value="3" onclick="result.value+='3'"></td>
                <td><input type="button" value="+" onclick="result.value+='+'"></td>
            </tr>
            <tr>
                <td><input type="button" value="4" onclick="result.value+='4'"></td>
                <td><input type="button" value="5" onclick="result.value+='5'"></td>
                <td><input type="button" value="6" onclick="result.value+='6'"></td>
                <td><input type="button" value="-" onclick="result.value+='-'"></td>
            </tr>
            <tr>
                <td><input type="button" value="7" onclick="result.value+='7'"></td>
                <td><input type="button" value="8" onclick="result.value+='8'"></td>
                <td><input type="button" value="9" onclick="result.value+='9'"></td>
                <td><input type="button" value="" onclick="result.value+=''"></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"></td>
                <td><input type="button" value="0" onclick="result.value+='0'"></td>
                <td><input type="button" value="." onclick="result.value+='.'"></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="C" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
## OUTPUT:
![image](https://user-images.githubusercontent.com/118367518/214895718-c5157711-c971-472e-8aa5-521244c5daf1.png)

## Result:

Thus a web application has been designed as a standard calculator.

