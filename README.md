# Test.github
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <h1 style="color:red">My to do list
        </h1>
        <h3>Monday</h3>
        <input id="MyInput" placeholder="tap to add"><button onclick="newElement()">Add</button>
        <ul id="MyUl">
         <li>Eat</li>   
        </ul>
        
        <h3>Tuesday</h3>
        <input id="MyInput-2" placeholder="tap to add"><button onclick="newElementt()">Add</button>
        <ul id="MyUl-2">
         <li>Sleep</li>   
        </ul>
        
        <h3>Wednesday</h3>
        <input id="MyInput-3" placeholder="tap to add"><button onclick="newElementtw()">Add</button>
        <ul id="MyUl-3">
         <li>Hit on women</li>   
        </ul>
        
        <h3>Thursday</h3>
        <input id="MyInput-4" placeholder="tap to add"><button onclick="newElementtur()">Add</button>
        <ul id="MyUl-4">
         <li>Study</li>   
        </ul>
        
        
        <h3>Friday</h3>
        <input id="MyInput-5" placeholder="tap to add"><button onclick="newElementtf()">Add</button>
        <ul id="MyUl-5">
         <li>Ball</li>   
        </ul>
        <h3>Saturday</h3>
        <input id="MyInput-6" placeholder="tap to add"><button onclick="newElementts()">Add</button>
        <ul id="MyUl-6">
         <li>Wash</li>   
        </ul>
        
        <h3>Sunday</h3>
        <input id="MyInput-7" placeholder="tap to add"><button onclick="newElementto()">Add</button>
        <ul id="MyUl-7">
         <li>Pray</li>   
        </ul>
        <script>
         /* By Nuel*/
/*Monday*/
alert ("pls ignore any error messages you may encounter, for something that works should'nt be given an error message, if seen, know its as an error from the system and not the code");

function newElement(){
    var li= document.createElement("li");
    var inputvalue= document.getElementById("MyInput").value;
    var t= document.createTextNode(inputvalue);
    li.appendChild(t);
    if (inputvalue ===''){
        alert ("You need to add a list");
    }
    else{
        document.getElementById("MyUl").
        appendChild(li);
    }
    
    document.getElementById("MyInput").value = "";


    
    //create a close button
    
    var myNodelist = document.getElementsByTagName("li");
var i;
for (i = 0; i < myNodelist.length; i++) {
  var span = document.createElement("SPAN");
  var txt = document.createTextNode("\u00D7");
  span.className = "close";
  span.appendChild(txt);
  myNodelist[i].appendChild(span);
}

// Click on a close button to hide the current list item
var close = document.getElementsByClassName("close");
var i;
for (i = 0; i < close.length; i++) {
  close[i].onclick = function() {
    var div = this.parentElement;
    div.style.display = "none";
  }
}  
    
}
/*Tuesday*/
function newElementt(){
    var li= document.createElement("li");
    var inputvalue= document.getElementById("MyInput-2").value;
    var t= document.createTextNode(inputvalue);
    li.appendChild(t);
    if (inputvalue ===''){
        alert ("You need to add a list");
    }
    else{
        document.getElementById("MyUl-2").
        appendChild(li);
    }
} 

  

/*Wednesday*/

function newElementtw(){
    var li= document.createElement("li");
    var inputvalue= document.getElementById("MyInput-3").value;
    var t= document.createTextNode(inputvalue);
    li.appendChild(t);
    if (inputvalue ===''){
        alert ("You need to add a list");
    }
    else{
        document.getElementById("MyUl-3").
        appendChild(li);
    }
}


/*Thursday*/

function newElementtur(){
    var li= document.createElement("li");
    var inputvalue= document.getElementById("MyInput-4").value;
    var t= document.createTextNode(inputvalue);
    li.appendChild(t);
    if (inputvalue ===''){
        alert ("You need to add a list");
    }
    else{
        document.getElementById("MyUl-4").
        appendChild(li);
    }
}


/*Friday*/
function newElementtf(){
    var li= document.createElement("li");
    var inputvalue= document.getElementById("MyInput-5").value;
    var t= document.createTextNode(inputvalue);
    li.appendChild(t);
    if (inputvalue ===''){
        alert ("You need to add a list");
    }
    else{
        document.getElementById("MyUl-5").
        appendChild(li);
    }
}


/*Saturday*/
function newElementts(){
    var li= document.createElement("li");
    var inputvalue= document.getElementById("MyInput-6").value;
    var t= document.createTextNode(inputvalue);
    li.appendChild(t);
    if (inputvalue ===''){
        alert ("You need to add a list");
    }
    else{
        document.getElementById("MyUl-6").
        appendChild(li);
    }
}


/*Sunday*/
function newElementto(){
    var li= document.createElement("li");
    var inputvalue= document.getElementById("MyInput-7").value;
    var t= document.createTextNode(inputvalue);
    li.appendChild(t);
    if (inputvalue ===''){
        alert ("You need to add a list");
    }
    else{
        document.getElementById("MyUl-7").
        appendChild(li);
    }
}
     </script>


    </body>
</html>
