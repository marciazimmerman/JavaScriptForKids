# JavaScriptForKids
<!--Working through the book JavaScript for Kids by Nick Morgan-->
<!--This is the Objects chapter.-->

var hertl = {
	lastname: "Hertl",
	firstname: "Tomas",
	identifiers:
	["San Jose", "Sharks", 48]
};

var jagr = {
	lastname: "Jagr",
	firstname: "Jaromir",
	identifiers:
	["Florida", "Panthers", 68]
};

var elias = {
	lastname: "Elias",
	firstname: "Patrik",
	identifiers:
	["New Jersey", "Devils", 26]
};

var hanzal = {
	lastname: "Hanzal",
	firstname: "Martin",
	identifiers:
	["Arizona", "Coyotes", 11]
};

var mrazek = {
	lastname: "Mrazek",
	firstname: "Petr",
	identifiers:
	["Detroit", "Red Wings", 34]
	
};

var will = {
	lastname: "Will",
	firstname: "Roman",
	identifiers:
	["","",35]
};

var czechs = [hertl, jagr, elias, hanzal, mrazek, will];

// czechs[0];
// this code asks for the element at index 0, which consists of all of the keys and their properties.
// czechs[1].identifiers;
// this code asks for the element at index 1, which is the variable named jagr,
// and then asks for that property under that object under the key named identifiers.

czechs[4].identifiers[2];
// returns 34

czechs[3].identifiers[1];
// returns Coyotes
var capHit = {};
	capHit.hertl = 0.925;
	capHit.jagr = 4;
	capHit.elias = 6;
	
capHit.hertl += 3;
capHit.hertl;
