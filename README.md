@import url('https://fonts.googleapis.com/css?family=Poppins:200,300,400,500,600,700,800,900&display=swap');
*
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
body
{
 display: flex;
 justify-content: center;
 align-items: center;
 min-height: 100vh;
 background: #161616;
}
.container
{
  position: relative;
  display: flex;
  gap: 30px;
}
.container .box
{
    position: relative;
    padding: 40px 0;
    width: 240px;
    background: #222;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.container .box .circle
{
    position: relative;
    width: 150px;
    height: 150px;
    background: conic-gradient(from 0deg,var(--clr) 0%,var(--clr) 0% var(--i), #333 var(--i), #333 100%);
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.container .box.circle::before
{
   content: " ";
   position: absolute;
   inset: 10px;
   background: #25252b;
   border-radius: 50%;
}
.container .box h2
{
  position: relative;
  text-align: center;
  font-size: 2.5em;
  color: #fff;
  font-weight: 600;
}
.container .box h2 small
{
    font-size: 0.5em;
    font-weight: 300;
}
.container .box h3
{
color: #fff;
text-transform: uppercase;
margin-top: 20px;
font-weight: 500;
letter-spacing: 0.1em;
