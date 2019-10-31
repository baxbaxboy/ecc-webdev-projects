<html>
<head><title>button.com</title>
   <script>
       var x = null;
       var y = null;
       function button1(){
       x = setTimeout(function(){alert("boom you're dead"); }, 5000);
       }
       function button2(){
       clearTimeout(x);
       window.alert("You saved the day");
       }
   
   </script> 
</head>
<body>
    <button onclick="button1()">button 1</button>
    <button onclick="button2()">button 2</button>
    <button>button 3</button>
    <button>button 4</button>


</body>
</html>
