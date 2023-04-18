<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>這啥？</title>
    <!--CSS-->
    <style>
        .myli{
            color: blue;
        }
    </style>
</head>
<body>

<a href="about.html">About</a>

<ul id="t1">
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ul>
<ul>
    <li>A</li>
    <li>B</li>
    <li>C</li>
</ul>

<!--JS-->
<script src="http://code.jquery.com/jquery-3.6.4.js"></script>
<script type="text/javascript">
    $(function (){
        console.log("AAAA");
        $("#t1 > li").addClass("myli")
    });

</script>
</body>
</html>
