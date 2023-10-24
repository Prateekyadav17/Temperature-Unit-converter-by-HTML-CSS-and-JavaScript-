<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!--LINK CSS FILE-->    
    <link rel="stylesheet" href="Style.css" />
    <title>Temperature Converter App</title>
  </head>
  <body>
    <div class="container">
      <div class="temperature-converter">
          <h1 class="title">Temperature Converter</h1>
          <div class="result">
            <span class="result-heading">Result (Celsius)</span>
            <h2 class="celsius-value" id="celsius"></h2>
          </div>
          <div class="degree-type">
            <div class="degree-field">
              <label for="degree">Degrees</label>
              <input type="number" name="degree" id="degree" />
            </div>
            <div class="temp-field">
              <label for="temp-type">Type</label>
              <select name="temperatures" id="temp-type" autocomplete="on">
                <option id="fahrenheit" value="fahrenheit">Fahrenheit</option>
                <option id="kelvin" value="kelvin">Kelvin</option>
              </select>
            </div>
          </div>
          <button id="convert-btn">Convert</button>
      </div>
    </div>
    <!--LINK JAVASCRIPT FILE-->
    <script src="./Convert.js"></script>
  </body>
</html>
