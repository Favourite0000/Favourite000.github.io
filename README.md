<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>ZURI ASSIGNMENT ON DESIGN</title>
 
</head>
<body> <h1><class="col-h1" > <a href="grid.html" class="col"> Click to show Grid </a></h1>
    <main>
      <div class="container">
      <div>
                  <img src="file:///C:/Users/User/Downloads/icon-sedans.svg" alt="sedan-icon"/>
                <h3>SEDANS</h3>
                <p>Choose a sedan for its</p>
                <p>affordability and excellent</p>
                <p>fuel economy. Ideal for</p>
                <p>cruising in the city or an</p>
                <p>your next road trip.</p>
                <button>Learn More</button>
                </div>
              
       <div>
                   <img src="file:///C:/Users/User/Downloads/icon-suvs.svg" alt="sedan-icon"/>
                <h3>SUVS</h3>
                <p>Take an SUV for its spacious</p>
                <p>interior,power, and</p>
                <p>versatility. Perfect for your</p>
                <p>next family vacation and</p>
                <p>off-road adventures.</p>
                <button>Learn More</button>
                </div>
       <div>
                   <img src="file:///C:/Users/User/Downloads/icon-luxury.svg" alt="sedan-icon"/>
                <h3>LUXURY</h3>
                <p>Cruise in the best car brands</p>
                <p>without the bloated prices.</p>
                <p>Enjoy the enhanced comfort</p>
                <p>of a luxury rental and arrive</p>
                <p>in style.</p>
                <button>Learn More</button>
              </div> 
      </div>    
    </main>
</body>
</html>
  
  
  
  @import url(https://fonts.google.com/specimen/Lexend+Deca);
*{
    margin : 0;
    padding : 0;
    box-sizing: border-box;
}
body{
    background-color:rgb(0, 0%, 95%);
    font-size: 15px;
    font-family: Lexend Deca;
    
}
main
{
    width:50%;
    margin: auto;
    display: flex;
    justify-content: center; 
    align-items : center;
    height: 200vh;
    font-size: 15px;
    padding: 0 20px;


    }

    .col-h1 {
      text-align: center;
    }
    
    .col {
      color: black;
      text-decoration: none;
    }
    
    .col:hover {
      color: rgb(100, 165, 106);
    }

h3{
        font-family: "Big Shoulders Display", cursive;
        font-weight: 700;
        padding: 30px 0;
        color: hsl(0, 0%, 95%);
      }

.button{font-size: 95%;

}    


.div1 {background-color:rgb(31, 77%, 52%);
    width:50%;
    text-align: center;
    padding: 5em;
    display: flex;
    flex-direction: column;

}
.div2 {background-color: rgb(184, 100%, 22%);
    width:50%;
    text-align: center;
    padding: 5em;
}
.div3 {background-color: rgb(20, 29, 3);
    width: 50%;
    text-align: center;
    padding: 5em;
    display: flex;
    flex-direction: column;
    
}





  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GRID task</title>

</head>
<body>
    <div class ="wrapper">
        <div class="one">One</div>
        <div class="two">Two</div>
        <div class="three">Three</div>
        <div class="four">Four</div>
        <div class="five">Five</div>
    </div>
    <style>
.grid-body {
  background-color: black;
}

.col-grid {
  color: white;
  text-decoration: none;
}

.col-grid:hover {
  color: whitesmoke;
}

.wrapper {
  max-width: 60%;
  background-color: white;
  height: 500px;
  margin: auto;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  padding: 10px;
  border-radius: 10px;
  outline: none;
  gap: 10px;
  box-shadow: inset 0px 0px 0px 1px rgb(116, 112, 112);
}

.one {
  grid-column: 1/3;
  background-color: orange;
  text-align: center;
  padding: 30px;
  border-radius: 7px;
  box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
  color: white;
}
.two{
  background-color: yellow;
  text-align: center;
  padding: 30px;
  border-radius: 7px;
  box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
  color: white;
}
.three {
  grid-row: 2/4;
  background-color: green;
  text-align: center;
  padding: 30px;
  border-radius: 7px;
  box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
  color: white;
}
.four {
  grid-column: 2/4;
  background-color: blue;
  text-align: center;
  padding: 30px;
  border-radius: 7px;
  box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
  color: white;
}
.five{
  grid-column: 2/4;
  background-color: blue;
  text-align: center;
  padding: 30px;
  border-radius: 7px;
  color: white;
  box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
}

/* Mobile style */

@media (max-width: 768px) {
  .container {
    margin: 10px auto;
    width: 375px;
    max-width: 400px;
    padding: 0 10px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
  }

  .sedan,
  .luxury,
  .suvs {
    border-radius: 10px;
    padding: 10px 15px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex: 1 1 300px;
    width: 100%;
  }

  img {
    width: 50px;
    margin-top: 10px auto;
  }

  h1 {
    padding: 15px 0 20px 0;
  }

  p {
    text-align: center;
  }

  button {
    margin: 20px 0;
    padding: 13px 30px;
    font-size: 15px;
    cursor: pointer;
    height: 50px;
  }

  button:hover {
    background-color: transparent;
    border: 2px white solid;
    color: white;
    border-radius: 50px;
  }



  .wrapper {
    max-width: 60%;
    background-color: white;
    height: 500px;
    margin: auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding: 10px;
    border-radius: 10px;
    outline: none;
    gap: 10px;
    box-shadow: inset 0px 0px 0px 1px rgb(223, 223, 223);
  }

  .one {
    grid-column: 1/4;
    background-color: #031D44;
    text-align: center;
    padding: 30px;
    border-radius: 7px;
    box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
    color: white;
  }
  .two{
    grid-column: 2/4;
    background-color: #04395E;
    text-align: center;
    padding: 30px;
    border-radius: 7px;
    box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
    color: white;
  }
  .three {
    grid-row: 2/3;
    background-color: #70A288;
    text-align: center;
    padding: 30px;
    border-radius: 7px;
    box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
    color: white;
  }
  .four{
    grid-column: 1/4;
    background-color: #D5896F;
    text-align: center;
    padding: 30px;
    border-radius: 7px;
    box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
    color: white;
  }
  .five {
    display: none;
    grid-column: 1;
    background-color: orange;
    text-align: center;
    padding: 30px;
    border-radius: 7px;
    color: white;
    box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
  }


@media (max-width: 600px) {
  
  .wrapper {
    max-width: 60%;
    background-color: white;
    height: 700px;
    margin: auto;
    display: grid;
    grid-template-columns: 10%;
    padding: 10px;
    border-radius: 10px;
    outline: none;
    gap: 10px;
  }

  .one {

    grid-column: 1/5;
    background-color: bright orange;
    text-align: center;
    padding: 30px;
    border-radius: 7px;
    box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
    color: white;
  }
  .two{

    grid-column: 1/5;
    background-color: yellow;
    text-align: center;
    padding: 30px;
    border-radius: 7px;
    box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
    color: white;
  }
  .three {

    grid-column: 1/5;
    background-color: green;
    text-align: center;
    padding: 30px;
    border-radius: 7px;
    box-shadow: 0px 0px 5px 1px rgba(116, 112, 112, 0.774);
    color: white;
  }
  .four {

    grid-column: 1/5;
    background-color: blue;
    text-align: center;
    padding: 30px;
    border-radius: 7px;
    color: white;
  }
  .five {
    grid-column: 1/5;
    display: grid;
    background-color: blue;
    text-align: center;
    padding: 30px;
    border-radius: 7px;
    color: white;
  } 
</style>   
</body>
</html>
