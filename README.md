# getelementbytagname
<html>
    <head>
        <title>getElementByTagName</title>
        <script type="text/javascript">
            function changeStyling()
            {
                var para=document.getElementsByTagName("p");
                para[0].style.fontSize=20;
                para[1].style.color="red";
                para[2].style.fontWeight="bold";

            }
        </script>
    </head>
    <body>
        <p>This is paragraph 1</p>
        <p>This is paragraph 2</p>
        <p>This is paragraph 3</p>
        <li>Types of fruits</li>
        Kiwi <br>
        watermelon
        <br>
        <button onclick="changeStyling()">Click Me</button>
    </body>
</html>
