# Document-Object-Model
DOM is a part of java script consider it as a main part for the front end development

THROUGH DOM WE CAN CHANGE THE WRITTEN PART IN HTM FILE OR CSS
 
IN HTML THERE ARE DIFFERENT SYNTAX FOR TAGS,CLASS,ID

FOR NORMAL 

document.innerhtml.body="  ";
 for tag
 document.querySelector('h1').innerhtml="fff";
for ID
doument.getElementbyId('four').innerhtml="ff";

for changing the background color
document.body.style.backgroundColor = "#201F2E"//color code

for changing the font
we use fontfamily;

if we want to create a element

let newDestination = document.createElement("li")
newDestination.innerHTML = "Oaxaca, Mexico";

if we want to remove a element
 
let paragraph = document.querySelector('p');
document.body.removeChild(paragraph);


for creating a button

function turnButtonRed{
	element.style.backgroundColor = "red";
  element.style.color = "white";
  element.innerHTML = "red Button"; 
}

element.onclick = turnButtonRed;
