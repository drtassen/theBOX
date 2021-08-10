<!DOCTYPE html>
<html lang="en">

<head>

</head>

<body>
    <button onclick="box()">soundcloud</button>

    <script>
        function box() {
            var myWindow = window.open("https://soundcloud.com/drtassen", "MsgWindow", "width=800,height=900");
            myWindow.document.write("<p>This window's name is: " + thebox + "</p>");
        }
    </script>
</body>

</html>
