# Calculator tests for SoapUI
<p><i>Calculator tests using variables. Integration tests use the property transfer of the result from one test to the next. The values ​​of variables for integration tests are set using Groovy steps</i></p>
<h3>Tests:</h3>
  <h4><b>Checking the addition function:</b></h4>
    <p>
      <b>Positive:</b>
        <ul>
          <li>Zero + Zero</li>
          <li>Positive integer + Zero</li>
          <li>Positive integer + Positive integer</li>
          <li>Positive integer + Negative integer</li>
          <li>Negative integer + Zero</li>
          <li>Negative integer + Negative integer</li>
          <li>Maximum positive integer (int) + Zero</li>
          <li>Maximum positive integer (int) + Negative integer</li>
          <li>Maximum positive integer (int) + Maximum negative integer (int)</li>
          <li>Maximum negative integer (int) + Zero</li>
          <li>Maximum negative integer (int) + Positive integer</li>
        </ul>
    </p>
    <p>
      <b>Negative:</b>
        <ul>
          <li>Positive integer greater than int + zero</li>
          <li>Positive integer greater than int + Positive integer</li>
          <li>Positive integer greater than int + Negative integer</li>
          <li>Positive integer greater than int + Negative integer is greater than integer</li>
          <li>Negative integer is greater than int + Zero</li>
          <li>Negative integer is greater than int + Positive integer</li>
          <li>Negative integer is greater than int + Negative integer</li>
          <li>Maximum positive integer (int) + Positive integer</li>
          <li>Maximum negative integer (int) + Negative integer</li>
          <li>Two empty fields</li>
          <li>Positive integer + Empty field</li>
          <li>Negative integer + Empty field</li>
          <li>Positive integer greater than int + Empty field</li>
          <li>Negative integer is greater than int + Empty field</li>
          <li>Maximum positive integer (int) + Empty field</li>
          <li>Maximum negative integer (int) + Empty field</li>
      </ul>
    </p>
<h3>Intergation tests:</h3>
    <h4>Checking two actions with addition</h4>
      <ul>
        <li>Addition and addition</li>
        <li>Addition and division</li>
        <li>Addition and multiplication</li>
        <li>Addition and substraction</li>
      </ul>
    <h4>Checking two actions with division</h4>
      <ul>
        <li>Division and addition</li>
        <li>Division and division</li>
        <li>Division and multiplication</li>
        <li>Division and subtraction</li>
      </ul>
    <h4>Checking two actions with multiplication</h4>
      <ul>
        <li>Multiplication and addition</li>
        <li>Multiplication and division</li>
        <li>Multiplication and multiplication</li>
        <li>Multiplication and subtraction</li>
      </ul>
    <h4>Checking two actions with subtraction</h4>
      <ul>
        <li>Subtraction and addition</li>
        <li>Subtraction and division</li>
        <li>Subtraction and multiplication</li>
        <li>Subtraction and substraction</li>
      </ul>
