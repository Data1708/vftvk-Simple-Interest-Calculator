function compute(content)
{
    var principal = document.getElementById("principal").value;
    var rate = document.getElementById("rate").value;
    var years = document.getElementById("years").value;
    var interest = principal * years * rate /100;
    var year = new Date().getFullYear()+parseInt(years);
    var textual=document.getElementById("result");
    var content="If you deposit <mark>"+principal+"</mark>,\<br\>at an interest rate of <mark>"+rate+"%</mark>\<br\>You will receive an amount of <mark>"+interest+"</mark>,\<br\>in the year <mark>"+year+"</mark>\<br\>"
    textual.innerHTML=content
    if (principal <= 0) {
		alert("Enter a positive number");
		principal.focus();
		return false;}
  	else {return true}
}

function updateRate(slideAmount){
    var sliderDiv = document.getElementById("rate_val");
    sliderDiv.innerHTML=slideAmount;
}
