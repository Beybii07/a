<!DOCTYPE html>
<html>

<head>

<style>

ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    width: 200px;
    background-color: #f1f1f1;
}

li a {
    display: block;
    color: #000;
    padding: 8px 0 8px 16px;
    text-decoration: none;
}

li a.active {
    background-color: steelblue;
    color: white;
}

li a:hover:not(.active) {
    background-color: turquoise;
    color: white;
}

</style>

</head>

<body>

<h2>Vertical Navigation Bar</h2>

<p>In this example, Active class is 
in a Steelblue background color and 
a white text.</p>

<ul>

<li><a class="active" href="#home">
Home</a></li>
<li><a href="#Content">Content</a>
</li>
<li><a href="#contact">Contact</a>
</li>
<li><a href="#about">About</a>
</li>

</ul>

</body>
</html>
