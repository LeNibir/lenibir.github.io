<!DOCTYPE html>
<html> 
<head>
<title> NIBIR'S FIRST WEBSITE! </title>
<meta charset="utf=8">
<link rel="stylesheet"
href="style.css">
</head>
<body> 
<h1><U>WELCOME TO NIBIR'S FIRST WEBSITE!</U></h1>
<P>Hello dear user, This is my first website developed by me using <B>VS CODE!</B></P>
<button onclick="Itoldyoutonotclickmehahah()">Don't Click!</button>
<p id="message"></p>
<script src="script.js" defer></script> 
</body>
</html>
body { background-color: blue;
    font-family: 'Times New Roman', Times, serif;
text-align: center;
margin-top: 50px;
min-height: 100vh;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
}
h1 {color: red;}
p{font-size: 25px;}
p{color: rgb(0, 0, 0);}
button { font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    padding: 20px 20px;
font-size: large;
text-decoration: underline;
font-weight: 300;
border-radius: 5px;
cursor: pointer;
}
button:hover {text-decoration: dashed;
background-color: aquamarine;
transition: background-color 0.3s , transform 0.2s ;
transform: scale(1.1);
}
function  Itoldyoutonotclickmehahah() {
document.getElementById("message").innerText ="BRUH I TOLD YOU TO NOT CLICK";
let colors = ["#f0f0f0", "#ffe4e1", "#e6e6fa", "#f5f5dc", "#d0f0c0"];
let randomcolors = colors[Math.floor(Math.random() * colors.length)]
document.body.style.backgroundColor = randomcolors ;

}



