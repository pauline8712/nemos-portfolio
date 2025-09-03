<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>
<style>
/* Reset */
* { margin: 0; padding: 0; box-sizing: border-box; }


body {
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
line-height: 1.6;
background: #f9f9f9;
color: #333;
overflow-x: hidden;
}


header {
position: fixed;
top: 0; left: 0;
width: 100%;
background: #fff;
box-shadow: 0 2px 8px rgba(0,0,0,0.1);
z-index: 1000;
}


header nav {
display: flex;
justify-content: space-between;
align-items: center;
padding: 1rem 2rem;
max-width: 1200px;
margin: auto;
}


header nav a {
color: #333;
text-decoration: none;
margin: 0 1rem;
font-weight: 500;
transition: color 0.3s;
}
header nav a:hover {
color: #0077ff;
}


/* Hero */
.hero {
height: 100vh;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
text-align: center;
padding: 2rem;
background: linear-gradient(135deg, #0077ff, #00d4ff);
color: #fff;
animation: fadeIn 1.2s ease-in-out;
}


.hero h1 {
font-size: 3rem;
margin-bottom: 1rem;
animation: slideDown 1.2s ease forwards;
}


.hero p {
font-size: 1.25rem;
margin-bottom: 2rem;
max-width: 600px;
}


.btn {
display: inline-block;
padding: 0.75rem 1.5rem;
background: #fff;
color: #0077ff;
font-weight: bold;
border-radius: 50px;
text-decoration: none;
transition: transform 0.3s, background 0.3s;
}
.btn:hover {
transform: scale(1.05);
background: #f0f0f0;
}


/* Sections */
section {
max-width: 1200px;
margin: auto;
padding: 5rem 2rem;
}


h2 {
text-align: center;
font-size: 2rem;
margin-bottom: 3rem;
position: relative;
}


h2::after {
content: '';
display: block;
width: 80px;
height: 4px;
background: #0077ff;
margin: 1rem auto 0;
border-radius: 2px;
}


.about p {
max-width: 700px;
margin: auto;
<a href="https://github.com/yourusername" target="_blank">My GitHub</a></p>
