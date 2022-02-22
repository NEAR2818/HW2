/* Ignore following classes */

* {
    font-family: "Montserrat", sans-serif;
    background-color: #eeeeee;
  }
  
  #intro {
    color: rgb(0, 0, 0);
    text-align: center;
    margin: 50px;
  }
  
  .insideborder {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .para {
    font-weight: 300;
    margin-left: 10px;
  }
  
  h2 {
    font-size: medium;
    font-weight: 200;
  }
  
  /* Classes that you might find useful */
  /* Note* These classes do not cover every possibloe case to build you flags, you will have to continue to add your own*/
  
  .flag {
    height: 300px;
    width: 500px;
    border-style: solid;
    margin-bottom: 5rem;
  }
  
  .horiz {
    display: flex;
    flex-direction: row;
  }
  
  .twovert {
    height: 50%;
  }
  
  .threevert {
    height: 33.3%;
  }
  
  .threehoriz {
    width: 33.3%;
  }
  
  .skinny {
    height: 17.5%;
  }
  
  .fat {
    height: 30%;
  }
  
  .circle {
    border-radius: 50%;
    height: 200px;
    width: 200px;
    position: relative;
    left: 85px;
    top: 50px;
  }
  
  /* Colors/ Feel free to add your own! */
  
  .red {
    background-color: red;
  }
  
  .orange {
    background-color: orange;
  }
  
  .yellow {
    background-color: yellow;
  }
  
  .green {
    background-color: green;
  }
  
  .blue {
    background-color: blue;
  }
  
  .lightblue {
    background-color: lightblue;
  }
  
  .purple {
    background-color: purple;
  }
  
  .white {
    background-color: #fff;
  }

  body {
    background-color:rgba(39, 39, 39, 0.68); /* Background color of Body */
font-size:0.5px;
}
.greece {
    width: 675em; /* Horizontal Strip width */
    height: 50em; /* Horizontal Strip Length */
    background-color: rgb(13, 94, 175); /* Horizontal Strip Blue Color */
    box-shadow: 0em 50em 0 0 rgb(255, 255, 255), 0em 100em 0 0 rgb(13, 94, 175), 0em 150em 0 0 rgb(255, 255, 255), 0em 200em 0 0 rgb(13, 94, 175), 0em 250em 0 0 rgb(255, 255, 255), 0em 300em 0 0 rgb(13, 94, 175), 0em 350em 0 0 rgb(255, 255, 255), 0em 400em 0 0 rgb(13, 94, 175); /* Forming whole flag */
    
}
.greece::before{
content: ""; /* Mandatory Attribute */
position: absolute; /* Mandatory Attribute */
width: 150em; /* Width of Blue box for Cross */
height: 100em; /* Height of Blue box for Cross */
background-color: rgb(13, 94, 175); /*Blue Color of Box */
box-shadow: 100em 0em 0 0 rgb(13, 94, 175),100em 100em 0 0 rgb(13, 94, 175),0em 100em 0 0 rgb(13, 94, 175); /* Various positions of blue box */
}
.greece::after{
  content: ""; /* Mandatory Attribute */
position: absolute; /* Mandatory Attribute */
width: 50em; /* Width of White box for Cross */
height: 50em; /* Height of White box for Cross */
background-color: rgb(255, 255, 255); /* White Box Color */
left: 100em; /* Positioning Parameters */
box-shadow: 0em 200em 0 0 white,0em 150em 0 0 white,-100em 100em 0 0 white,-50em 100em 0 0 white,0em 50em 0 0 white,50em 100em 0 0 white,100em 100em 0 0 white,0em 100em 0 0 white; /* Various position parameters of box */
}
div {
    position: relative; /* For shift of hoist side to left */
    left:50em; /* Shift threshold */
}
