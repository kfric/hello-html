:root {
font: 16px / 1 sans-serif;
}

html {
height: 100%;
}

body {
margin: 0;
min-height: 100%;
background-color: grey;
margin: 1px 50px 50px;
}
/_ ------------------------------------------- _/
h1,
h2 {
color: grey;
background-color: grey;
border: 2px solid grey;
padding: 1rem;
border-radius: 50px;
background-color: black;
}
p {
color: black;
}
ul {
color: black;
}
/_ div {
color: blue;
} _/
/_ singles the declared class _/
/_ .bike {
font-weight: bold;
text-decoration: underline;
} _/
.bike {
font-size: 1.5rem;
font-weight: bolder;
}
.services {
text-transform: uppercase;
}
/_ singles the declared class WITH interaction _/
div:hover {
font-size: xx-large;
font-weight: bold;
}

/_ matches the first element within a group of siblings _/
/_ p:first-child {
font-size: xx-large;
} _/

/_ matches elements based on their position in a group of siblings _/
/_ li:nth-child(odd) {
color: chartreuse;
} _/

/_ p::before {
content: '🔥';
} _/

img {
border: 1px;
border-radius: 50px;
}
figure {
font-size: xx-small;
}
