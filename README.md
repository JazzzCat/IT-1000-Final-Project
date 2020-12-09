![SpaceX Logo](https://user-images.githubusercontent.com/75458324/101556006-761a5880-397f-11eb-8ef1-375eb82338b6.jpg)

# What is SpaceX?

SpaceX is an American aerospace manufaturer and space transportation services company that is headquartered in Hawthorne, California. It was originally founded in 2002 by Elon Musk with the future goal to reduce transportation in space in order be able to colonize Mars. The company has around 8,000 employees as of May of 2020.

SpaceX stands for Space Exploration Technologies Corp. and has been becoming more well-known every year. NASA has shown big interest into this company and has awarded SpaceX with several contracts over the past two decades, which range from development of new spacecrafts to transporting cargo to the International Space Station (ISS). NASA has also awarded SpaceX with more than $3.1 billion to fund the development of its new Crew Dragon capsule. The Dragon capsule is a class of reusable cargo spacecraft. A big thing that the company is known for, is that they are able to reuse the rockets / capsules multiple times instead of having to rebuild them each time they launch. 


* [Goals](Goals.md)
* [Achievments](Achievements.md)
* [Ownership & Funding](Ownership&Funding.md)
* [Accidents](Accidents.md)











To be able to code the program used for the rockets, a very simplified code such as the FizzBuzz program must be able to be created with ease. Below is an example of the FizzBuzz program.

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i < 100; i++) {
		displayHTML += "<p>" + i + "</p>";
	}
	display.innerHTML = displayHTML;
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>