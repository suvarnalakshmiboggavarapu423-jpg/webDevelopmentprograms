# webDevelopmentprograms
<!DOCTYPE html>
<html>
    <head>
        <tittle>DOM Example</tittle>
            <style>
                #box {
                    width: 200px;
                    padding: 20px;
                    background-color: lightblue;
                    text-align: center;
                    margin: top 10px;
                }
            </style>
        
    </head>
    <body> 
        <h2 id ="heading">Welcome to DOM</h2>
        
        <button onclick="changeContent()">click Me</button>

        <div id ="box">this is a box</div>

        <script>
            function changeContent() {
                document.getElementById("heading").innerHTML = "DOM update!";
                document.getElementById("box").style.backgroundColor = "lightgreen";
                document.getElementById("box").style.color = "green";
                document.getElementById("box").innerHTML = "content";
            }
        </script>
    </body>
</html>
