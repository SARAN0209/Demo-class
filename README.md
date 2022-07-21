# Day 03
# 1.JSON LOOPS
# FOR LOOP:
var arr={
"NAME":"Saran",
"AGE":"26",
"PLACE":"Tirupattur"
}
for(var i=0;i<arr.length;i++){
console.log(arr[i]);
};

# FOR IN LOOP
var arr={
"NAME":"Saran",
"AGE":"26",
"PLACE":"Tirupattur"
}
for(var key in arr){
console.log(key,arr[key]);
};

# 2.Resume data in JSON format

"NAME":       "Saran C",
"ADRESS":     "No: 123, Phase – II, Housing Board, Tirupattur (TK).
               Tirupattur (DT)-635601",

"Email":     "saranbabu2609@gmail.com",
"Contact No: "+918344522300",
 

"Career Objective",
             "To work in your esteemed organization where I can prove my technical and functional expertise and work towards the growth of the organization",
 "Skill Sets",
 
"Below is a list of software products and tools that I have worked with",
 "Operating Systems",	
              "Windows": "xP, 7, 8 and 10",
"Strength",
            •	"Perfectionist and Time Punctual",
            •	"Optimistic",
            •	"High motivated in team work and dedication',
            •	"Good ability to learn new things",
"Personal Details",

"Name":	"C. Saran",
"Father’s Name":	  "Mr. K. Chandra Babu",
"Date of Birth":	  "24 June 1996"
"Sex":	            "Male",
"Languages Known": 	"Tamil and English",
"Marital Status":	  "Single",
"Nationality":	    "Indian",


"Declaration",

"I hereby declare that all the details furnished here are true to the best of my knowledge",
"[SARAN C]"

# 3.Diference between window,screen and document
# WINDOW:
  Each browser tab has its own top-level window object. Each <iframe> (and deprecated <frame>) element has its own window object too, nested within a parent window.   Each of these windows gets its own separate global object. window.window always refers to window, but window.parent and window.top might refer to enclosing         windows, giving access to other execution contexts. 
# SCREEN:
  the portion of a screen displaying the rendered document is the viewport in JavaScript, which is potentially confusing because we call an application's portion of   the screen a window when talking about interactions with the operating system. The getBoundingClientRect() method of any document element will return an object     with top, left, bottom, and right properties describing the location of the element in the viewport.
# DOCUMENT:
  Each window object has a document object to be rendered. These objects get confused in part because HTML elements are added to the global object when assigned a     unique id.
 
 
 
 
 
 

