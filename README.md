<!--
    Benson Zhu
    Web Developement
    Mr. Irimina
    9/26/23




  <!DOCTYPE html>
<html>
    <head>
        <title></title>
        <style></style>
        <script>
          function greet(){
          console.log("Hello World.");
          }
          function shoutTen(){
            console.log("10");
          }
         
        </script>
    </head>
    <body onload = "greet();">
      <button onclick = "shoutTen();">Shout 10</button>
    </body>
</html>
  -->








<!--  <!DOCTYPE HTML>
  <html>
    <head>
      <title>Add Subtract Multiply Divide</title>
      <style></style>
        <script>
          function initialize()
          {
            num1 = 3;
            num2 = 7;
          }
          function addNumbers()
          {
            var result = num1 +num2;
            console.log(result);
          }
          function subtractNumbers()
          {
            var result = num1 - num2;
            console.log(result);
          }
          function multiplyNumbers()
          {
            var result = num1*num2;
            console.log(result);
          }
          function divideNumbers()
          {
            var result = num1/num2;
            console.log(result);
          }
          </script>
    </head>
    <body onload = "initialize();">
      <button onclick = "addNumbers();">Add the 2 Numbers</button>
      <button onclick = "subtractNumbers();">Subtract the 2 Numbers</button>
      <button onclick = "multiplyNumbers();">Multiply the 2 Numbers</button>
      <button onclick = "divideNumbers();">Divide the 2 Numbers</button>
    </body>
  </html>




  -->






<!--
  <!DOCTYPE HTML>
  <html>
    <head>
      <title></title>
        <style></style>
        <script>
        function initialize()
        {
            outputDiv = document.getElementById("divout");
        }
        function clickResponse()
        {
            outputDiv.innerHTML = "Now you've clicked the button.";
        }
        </script>
        </head>
    <body onload = "initialize();">
      <div id =  "divout">
        You have not clicked the button.
      </div>
      <button onclick = "clickResponse();">Click me!</button>
    </body>
  </html>
  -->

<!--
  <!DOCTYPE HTML>
  <html>
    <head>
      <title>Up and Down</title>
      <style></style>
    <script>
      function initialize()
      {
        numberOutput = document.getElementById("output");
        negativeButton = document.getElementById("negativebtn");
        myNumber = 0;
        negativesAllowed = false;
        display();
      }
      function addOne(){
        myNumber++;
        display();
      }
      function subtractOne()
      {
        myNumber--;
        if(myNumber<0 && !negativesAllowed){
          myNumber = 0;
        }
        display();
      }
      function display(){
        numberOutput.innerHTML = myNumber;
        if(!negativesAllowed){
          negativeButton.innerHTML = "Negatives are OFF";
        }
        else{
          negativeButton.innerHTML = "Negatives are ON";
        }
      }
      function toggleNegatives(){
        negativesAllowed = !negativesAllowed;
        if(myNumber < 0){
          myNumber  = 0;
        }
        display();
      }
    </script>
    </head>
    <body onload = "initialize();">
    <h1 id = "output">0</h1>
    <hr />
  <button onclick = "addOne();">Add</button>
  <button onclick = "subtractOne();">Subtract</button>
  <button onclick = "toggleNegatives();" id = "negativebtn">Negatives are OFF</button>
</body>
  </html>

-->

<!DOCTYPE HTML>
<html>
    <head></head>
    <title></title>
    <script>
        function initialize(){
            messageOutput = document.getElementById("output");
            message = "";
        }
        function display(){
            messageOutput.innerHTML = message;
        }
        function addCharacter(ch){
            message += ch;
            display();
        }
    </script>
    <body onload = "initialize();">
    <div id = "output"></div>
    <hr />
    <button onclick = "addCharacter('0');">0</button>
    <button onclick = "addCharacter('1');">1</button>
    <button onclick = "addCharacter('2');">2</button>
    <button onclick = "addCharacter('3');">3</button>
    <button onclick = "addCharacter('4');">4</button>
    <button onclick = "addCharacter('5');">5</button>
    <button onclick = "addCharacter('6');">6</button>
    <button onclick = "addCharacter('7');">7</button>
    <button onclick = "addCharacter('8');">8</button>
    <button onclick = "addCharacter('9');">9</button>
    <button onclick = "addCharacter('A');">A</button>
    <button onclick = "addCharacter('B');">B</button>
    <button onclick = "addCharacter('C');">C</button>
    <button onclick = "addCharacter('D');">D</button>
    <button onclick = "addCharacter('E');">E</button>
    <button onclick = "addCharacter('F');">F</button>
    <button onclick = "addCharacter('G');">G</button>
    <button onclick = "addCharacter('H');">H</button>
    <button onclick = "addCharacter('I');">I</button>
    <button onclick = "addCharacter('J');">J</button>
    <button onclick = "addCharacter('K');">K</button>
    <button onclick = "addCharacter('L');">L</button>
    <button onclick = "addCharacter('M');">M</button>
    <button onclick = "addCharacter('N');">N</button>
    <button onclick = "addCharacter('O');">O</button>
    <button onclick = "addCharacter('P');">P</button>
    <button onclick = "addCharacter('Q');">Q</button>
    <button onclick = "addCharacter('R');">R</button>
    <button onclick = "addCharacter('S');">S</button>
    <button onclick = "addCharacter('T');">T</button>
    <button onclick = "addCharacter('U');">U</button>
    <button onclick = "addCharacter('V');">V</button>
    <button onclick = "addCharacter('W');">W</button>
    <button onclick = "addCharacter('X');">X</button>
    <button onclick = "addCharacter('Y');">Y</button>
    <button onclick = "addCharacter('Z');">Z</button>
</body>
</html>

