<html>
<head>
<title> FIBONACCI</title>
</head>
<body style="background-color:pink"> 
<h3 style="text-align:center; color:Red">FIBONACCI SEQUENCE </h3>
<script type="text/javascript">

var limit = prompt("Enter the limit 'n' to generate the fibonacci number:", " ");
var fib1=0;
var fib2=1;

document.write("Limit of Fibonacci Sequence: ",limit, "<br/>");
document.write("Fibonacci Sequence:"+"<br/>");
document.write(fib1+"<br/> ");
document.write(fib2+"<br/> ");
 
var i,fib3;
for(i=2; i<limit; i++)
{
	 fib3=fib1+fib2;
	 document.write(fib3+"<br/>");
	 fib1=fib2;
	 fib2=fib3;
}

</script>
</body>
</html>
