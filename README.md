# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
    <title>students grade</title>
    <script type="text/javascript">
    function sum()
    {
        var mark1, mark2, mark3, mark4, mark5, total, percentage;
        mark1 = parseInt(prompt("Enter Subject-1 Marks"));
        mark2 = parseInt(prompt("Enter Subject 2 Marks"));
        mark3 = parseInt(prompt("Enter Subject 3 Marks"));
        mark4 = parseInt(prompt("Enter Subject 4 Marks"));
        mark5 = parseInt(prompt("Enter Subject 5 Marks"));
        total = mark1 + mark2 + mark3 + mark4 + mark5;
        percentage = total / 5;
    
        if (percentage >= 91 && percentage <= 100)
        {
            alert("O Grade");
        }
        else if (percentage >= 81 && percentage <= 90)
        {
            alert("A+ Grade");
        }
        else if (percentage >= 71 && percentage <= 80)
        {
            alert("A Grade");
        }
        else if (percentage >= 61 && percentage <= 70)
        {
            alert("B+ Grade");
        }
        else if (percentage >= 51 && percentage <= 60)
        {
            alert("B Grade"); 
        }
        else
        {
            alert("RA Grade");
        }
    }
    </script>
    </head>
    <body bgcolor="skyblue">
    <h1>To find your grade</h1>
<form>
    <input type="button" value="click" onclick="sum()"/>
</form>
    </h1>
    </body>
    </html>
```

## OUTPUT
![web06-op1](https://github.com/kiruthikaselvam0501/Ex06/assets/168701396/ff19ed61-303f-41f0-ae0d-12ea50be01b1)
![web06-op2](https://github.com/kiruthikaselvam0501/Ex06/assets/168701396/c9a7dcd3-2bc8-4f98-b1cd-8626fb08b48f)
![web06-op3](https://github.com/kiruthikaselvam0501/Ex06/assets/168701396/fca68a3b-6038-4e16-aead-d9c58ea942d6)
![web06-op4](https://github.com/kiruthikaselvam0501/Ex06/assets/168701396/cc0be98c-814b-4568-a040-6bec4431000b)
![web06-op5](https://github.com/kiruthikaselvam0501/Ex06/assets/168701396/0baab16b-ba72-4fab-a228-07a8c7547401)
![web06-op6](https://github.com/kiruthikaselvam0501/Ex06/assets/168701396/61809179-f736-4c7a-a73c-1be1557f1926)



## RESULT
  Student result using JavaScript is created successfully.
