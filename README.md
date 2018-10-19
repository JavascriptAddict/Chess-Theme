# Chess-Theme
A simple one page pure HTML &amp; CSS theme created for you

<!doctype html>
<HTML>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" type="text/css" href="//fonts.googleapis.com/css?family=Lobster" />
<style>

html,body{

width: auto;
height: 100%;
left: 0;
bottom: 0;
margin: 0;
padding: 0;
background-position: center;
background-size:cover;
background-repeat:no-repeat;
box-sizing:border-box;
background-color: black;

}
.nav{

width: 100%;
height: 50px;
position: relative;
top: 0;
left: 0;
padding: 0;
background-color: white;
border-bottom-left-radius: 50%;
border-bottom-right-radius: 50%;




}
.nav ul{
    
box-sizing:border-box;
width: 100%;
text-align: center;
height: 50px;
margin: 0;
padding: 5px;
right: 0;
overflow: auto;

}
.nav li{

list-style-type: none;
text-decoration: none;
font-weight:bold;
color: black;
font-family: 'Lobster', cursive;
font-size: 20px;
margin: 5px;
display: inline-block;

}
.nav li:hover{
color: orange;
}
.bannerleft{

    color: white;
    font-weight: bold;
    font-family: 'Lobster', cursive;
    width: auto !important;
    padding: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    /* bring your own prefixes */
    transform: translate(-50%, -50%);
    text-align: center;


}
.bannerleft p{

   
    text-align: center;
    color: grey;

}
#content{

    top: 50px;
    width: 100%;
    padding: 2%;
    margin: 0;
    position: absolute;
    box-sizing:border-box;
    bottom: 0;

}
</style>
</head>
<body>

<div class="nav">

<ul>
<li>
Home
</li>
<li>
About
</li>
<li>
Contact
</li>
<li>
Locate
</li>
</ul>

</div>

<div id="content">
    <div class="bannerleft">
<h1>
    Chess Theme
</h1>
<p>Proudly created for you by JavascriptAddict</p>

</div>
</div>
</body>

</html>
