- {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  }

@font-face {
font-family: DMSans;
src: url(/assets/fonts/DMSans-VariableFont_opsz\,wght.ttf);
}

body {
width: 100%;
font-family: DMSans;
background-color: whitesmoke;
line-height: 1;
min-height: 100vh;
display: flex;
justify-content: center;
align-items: center;
flex-flow: column wrap;
}

main {
max-width: 100%;
display: grid;
place-items: center;
font-size: 2em;
gap: 30px;
padding: 32px;
}

div {
border-radius: 15px;
padding: 32px;
/_ box-shadow: 1px, 2px, 2px; _/
display: flex;
flex-flow: column;
justify-content: center;
align-items: center;
width: 80%; /_change the width into 90% on mobile_/
font-weight: 600;
gap: 20px;
overflow: hidden;
}
img {
align-self: center;
width: 70%;
}
.cont1 {
background-color: antiquewhite;
justify-content: center;
align-items: flex-start;
}
.cont1 h2 {
font-weight: 500;
width: 80%;
margin-bottom: 20px;
}
.span1 {
font-style: italic;
color: rgba(105, 45, 224);
}

.cont2 {
background-color: rgba(105, 45, 224, 0.816);
color: #fff;
gap: 20px;
height: 400px;
}

.span2 {
color: goldenrod;
}
.header {
text-align: center;
font-size: 3rem;
width: 64%;
font-weight: 400;
}
.footer {
font-size: 1rem;
font-weight: 400;
}
.cont3 {
background-color: rgba(125, 71, 234, 0.3);
gap: 30px;
}
.span3 {
width: 70%;
font-size: 1.7rem;
text-align: center;
font-weight: 500;
}
.cont3 img {
width: 300px;
}
.cont3 h1 {
font-weight: 600;
font-size: 2rem;
width: 100%;
}
.cont4 {
background-color: rgb(237, 192, 88);
align-items: flex-start;
justify-content: flex-start;
}
.cont4 h3 {
width: 60%;
margin-bottom: 10px;
font-weight: 500;
}

.cont5 {
background-color: #fff;
justify-content: flex-start;
align-items: flex-start;
}
.cont5 img {
width: 80%;
}
.cont5 p {
width: 70%;
}

.cont6 {
background-color: rgb(237, 192, 88);
height: 310px;
overflow: hidden;
justify-content: flex-start;
align-items: flex-start;
/_ padding: 0; _/
}
.cont6 p {
width: 60%;
}
.cont6 img {
margin-top: 10px;
}

/\* \*/
.cont7 {
background-color: #fff;
align-items: flex-start;
}

.cont7 h1 {
font-weight: 500;
}
.span5 {
display: block;
font-size: 25px;
font-weight: 400;
}
.cont8 {
display: flex;
justify-content: center;
align-items: center;
gap: 15px;
background-color: rgba(105, 45, 224, 0.955);
color: #fff;
text-align: center;
font-weight: 300;
}
.span4 {
white-space: nowrap;
}

.p8 {
width: 60%;
font-size: 1.5rem;
}

@media screen and (min-width: 1080px) {
main {
grid-template-columns: repeat(10, 1500px);
grid-template-rows: repeat(13, 100px);
gap: 1em;
}

.cont1 {
grid-column: 1/2;
grid-row: 1/4;
}
}

/\*
@media screen and (min-width: 800px) {
main {
width: 100%;
place-content: center;
padding: 2rem;
grid-template-columns: repeat(10, 100px);
grid-template-rows: repeat(10, 100px);
gap: 1em;
}
.cont1 {
grid-column: 1/3;
grid-row: 1/5;
grid-column: 1/5;
}
.cont2 {
grid-column: 3/7;
grid-row: 1/3;
}
.cont3 {
grid-row: 8/11;
grid-column: 1/5;
}
.cont4 {
grid-column: 1/3;
grid-row: 5/9;
}
.cont5 {
overflow: hidden;
grid-column: 3/5;
grid-row: 4/6;
padding: 10px;
}
.cont6 {
grid-column: 5/7;
grid-row: 4/6;
padding: 10px;
height: auto;

@media screen and (min-width: 1080px) {
main {
width: 100%;
display: grid;
grid-template-columns: repeat(12, 100px);
grid-template-rows: repeat(11, 100px);
gap: 1em;
place-content: center;
justify-content: start;
align-items: start;
font-size: 40px;
}
div {
overflow: hidden;
/\* padding: 30px;
justify-content: center;
align-items: center;
min-width: 300px;
}
.cont1 {
grid-column: 1/4;
grid-row: 1/6;
padding: 16px;
align-items: center;

    padding: 30px;

}
.cont2 {
grid-column: 4/10;
grid-row: 1/4;
height: auto;
}
.cont3 {
grid-column: 10/13;
grid-row: 1/7;
align-items: flex-start;
margin-left: 70px;
padding-left: 16px;
}
.cont3 img {
padding: 32px;
width: 450px;
}
.cont3 h3 {
width: 70%;
}
.span3 {
width: 90%;
font-size: 1.2rem;
text-align: left;
font-weight: 500;
}
.cont4 h3 {
width: 100%;
}
.cont4 img {
padding: 35px;
width: 280px;
align-self: center;
}
.cont5 {
grid-column: 4/7;
grid-row: 4/7;
font-size: 40px;
}
.cont5 img {
width: 350px;
height: 100px;
}
.cont5 p {
margin-top: 5px;
width: 70%;
}
.cont6 {
grid-column: 7/10;
grid-row: 4/7;
height: auto;
padding: 20px;
}
.cont6 p {
width: 80%;
font-size: 2.5rem;
}
.cont6 img {
margin-top: 50px;
width: 250px;
height: 300px;
align-self: center;
justify-self: baseline;
}
.cont7 {
grid-column: 4/7;
grid-row: 7/11;
}
.cont7 img {
width: 250px;
align-self: center;
}
.cont8 {
grid-column: 7/13;
grid-row: 7/11;
display: flex;
flex-flow: row;
font-size: 2.4rem;
}
.cont8 img {
width: 40%;
}
.p8 {
padding: 10px;
width: 90%;
text-align: left;
font-weight: 600;
}
}

}
} \*/
