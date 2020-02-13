<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<title>Mad Libs</title>
</head>
<body>
<h1>Mad Libs</h1>
Noun: <input type="text" id="noun">
<br>Adjective: <input type="text" id="adjective">
<br>Someone's Name: <input type="text" id="person">
<br>Someone Else Name: <input type="text" id="other-person">
<br>Adverb: <input type="text" id="adverb">
<br>Verb: <input type="text" id="verb">
 <p>
 <button onclick="madTime()">Make Magic happen!!</button>
 <p>
 <div id="story"></div>
 </body>
 <script>
// Start writing your code here! 
 

function madTime() {
    var person = document.getElementById("person").value; 
	var storyDiv = document.getElementById("story");
	var noun = document.getElementById("noun");
	var adjective = document.getElementById("adjective");
	var verb = document.getElementById("verb");
	var adverb = document.getElementById("adverb");
	var otherPerson = document.getElementById("Someone's Name");
	var someoneElseName = document.getElementById("Someone's Else Name");
	
	storyDiv.innerHTML = person + 'walking into petsmart with her' + animal + 'named'+ Someone Else. +
Someone else + 'was very' + adjective + 'and' + verb + 'away.' 
person + 'got very'+ adjective + 'and' + verb + 'after her pet.'+
'While searching for her pet she ran into a' +  adjective + 'unicorn.' +
'The' + adjective + 'unicorn spoke to her and said' + someone else + 'went into the back with the' + animal. + 
person + 'said thank you to the unicorn and walked away.  When they turned around the unicorn disapeared.' +
'Not believing what' + person + 'just saw they'+ verb + 'away.' +
person + 'walked pass many hamsters, fish, cats, and dogs,' + 'but still couldn't find their pet'+ animal. +
'Then I turned the corner and saw my' animal 'dancing with the fish.' 'I' verb
'and then brought some food for my pet.' + 'I then took him home never forgetting this memory.' 
