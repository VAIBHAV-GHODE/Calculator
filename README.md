<!-- CALCULATOR DEMO IN JAVA SCRIPT -->  
    
    
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
    <script>
        var num1 = prompt('Enter first number');
        var num2 = prompt('Enter second number');
        var op = prompt(" Enter Operator from + - * / ");

        if (op == "+")
        {
            add(num1,num2)
        }

        else if (op == "-")
        {
            subtract(num1,num2)
        }

        else if (op == "*")
        {
            multiply(num1,num2)
        }
        else if (op == "/")
        {
            division(num1,num2)
        }
        else
        {
            document.write("Invalid input");
        }


        function add(a,b)
        {
            var result = parseInt(a) + parseInt(b);
            document.write("Addition result is :"+result);
        }

        function subtract(a,b)
        {
            var result = parseInt(a) - parseInt(b);
            document.write("Subtraction result is :"+result);
        }

        function multiply(a,b)
        {
            var result = parseInt(a) * parseInt(b);
            document.write("Multiply result is :"+result);
        }

        function division(a,b)
        {
            var result = parseInt(a) / parseInt(b);
            document.write("Division result is :"+result);
        }




    </script>

</body>
</html>

