# conversion

&lt;html> &lt;body>  &lt;h2>JavaScript Functions&lt;/h2>  &lt;p>This example calls a function which performs a temperature in celsius  and returns it in  Fahrenheit :&lt;/p>  &lt;button onclick="myFunction()">Click me&lt;/button>  &lt;input type="text" id="c">&lt;br>&lt;br> &lt;input type="text" id="f">&lt;br>&lt;br>   &lt;script>  function myFunction() {   document.getElementById("f").value = parseFloat(document.getElementById("c").value)*1.8+32 ; } &lt;/script>   &lt;/body> &lt;/html>
