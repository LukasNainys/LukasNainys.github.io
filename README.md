<!DOCTYPE html>
<html>
    <head>
        <title>World yes</title>
    </head>
    <body>
        <h1>Content goes here...</h1>
        <hr />
        <!-- this is a comment-->
        <ul>
            <li><i>Item 1</i></li>
            <li><b>Item 2</b></li>
            <li><u>Item 3</u></li>
            <li><s>Item 4</s></li>
        </ul>
        <table>
            <tr><td>Frame Number</td><td>Page Number</td><td>Reference Count</td><td>Dirty bit</td></tr>
            <tr><td>0</td><td>43</td><td>0</td><td>1</td></tr>
            <tr><td>1</td><td>42</td><td>4</td><td>1</td></tr>
            <tr><td>2</td><td>0</td><td>18</td><td>0</td></tr>
            <tr><td>3</td><td>1</td><td>8</td><td>1</td></tr>
            <tr><td>4</td><td>2</td><td>2</td><td>0</td></tr>
        </table>
        <article>
            <header>An article</header>
            <p>Articles are relatively standalone pieces of content that could be used (think cut'n'paste) on another web Page max is bad </p>
            <section>A section is a division of an article </section>
            <footer>The footer of the article</footer>
        </article>
        <div>Does nothing but something</div>
        <p>Normal Text</p>
        <canvas id="myCanvas" width="200" height="100" style="border:100px solid #915303;">
                Your browser does not support the HTML5 canvas tag.</canvas>
                
                <script>
                var c = document.getElementById("myCanvas");
                var ctx = c.getContext("2d");
                ctx.font = "72px Comic Sans";
                ctx.strokeText("qoop",50,50);
                </script>
    </body>
</html>
