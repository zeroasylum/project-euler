var main = function () {
 var fibo1= 1;
 var fibo2=2;
 var summe=0;
 for (var i =0;i<20;i++) {
 	fibo1=fibo1+fibo2;
 	$("<p>"+fibo1+"<br>").appendTo('.one');
 	if (fibo1%2==0) {
		summe=summe +fibo1;
	} 	
 	fibo2=fibo2+fibo1;
 	$("<p>"+fibo2+"<br>").appendTo('.one');
  	if (fibo2%2==0) {
		summe=summe+fibo2;
	} 		
 }
 $("<p>"+summe+"<br>").appendTo('.sum');
};

$(document).ready(main);