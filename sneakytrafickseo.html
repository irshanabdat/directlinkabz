<html>
<head>
<script>
//Popunder settings
var ppwidth		=	500;
var ppheight		=	500;
var pptop		=	100;
var ppleft		=	100 ;
var ppscrollbars	=	0;
var ppresizable		=	0;
var pptoolbar		=	0;
var pppplocationbar	=	0;
var ppmenubar		=	0;
var ppstatus		=	0;
var ppdirectories	=	0;

var ppurl 		=	'https://www.seotrafick.tk/p/popcest.html';

var ppdelay = 3000;
var timer = null;
var speed = 3; //1 is  slow




//DO NOT EDIT UNDER HERE!!

  var myWidth = 0, myHeight = 0;
  if( typeof( window.innerWidth ) == 'number' ) {
    //Non-IE
    myWidth = window.innerWidth;
    myHeight = window.innerHeight;
  } else if( document.documentElement && ( document.documentElement.clientWidth || document.documentElement.clientHeight ) ) {
    //IE 6+ in 'standards compliant mode'
    myWidth = document.documentElement.clientWidth;
    myHeight = document.documentElement.clientHeight;
  } else if( document.body && ( document.body.clientWidth || document.body.clientHeight ) ) {
    //IE 4 compatible
    myWidth = document.body.clientWidth;
    myHeight = document.body.clientHeight;
  }



var endTop = (myHeight / 2) - 50;
var endLeft = (myWidth / 2) - 200;

//******************************************************
// Our popunder element
//******************************************************
function popunder(){
	var newwindow = window.open(ppurl,'popunder','height='+ppheight+',width='+ppwidth+',toolbar='+pptoolbar+',directories='+ppdirectories+',status='+ppstatus+',menubar='+ppmenubar+',scrollbars='+ppscrollbars+',resizable='+ppresizable+',top='+pptop+',left='+ppleft+'');
	newwindow.blur();
	window.focus();
	document.body.focus();
	//document.getElementById('test').focus();
	//alert("test");
}

//******************************************************
// Hide the new window!
//******************************************************

function hideme(){
	//alert (window.opener);
	window.blur();
	window.opener.focus();
}

//******************************************************
// Simple little function to get Elements as an object
//******************************************************
function getEl(id)
{
	var el = document.getElementById(id);
	return el;
}
//******************************************************
// Function to show Elements
//******************************************************
function showEl(id)
{
	getEl(id).style.display ="";
}
//******************************************************
// Function to hide Elements
//******************************************************
function hideEl(id)
{
	getEl(id).style.display ="none";
}

//******************************************************
// Function to move Element
//******************************************************
function moveEl(id)
{
	var popup = getEl(id);
	var currentTop = parseInt(popup.offsetTop);
	var currentLeft = parseInt(popup.offsetLeft);
	
	var keepMoving = false;
	//Move
	if (currentTop <= endTop)
	{
		popup.style.top = (currentTop + speed) + "px";
		keepMoving = true;
	}
	if(currentLeft <= endLeft)
	{	
		popup.style.left = (currentLeft + speed) + "px";
		keepMoving = true;
	}
	if (keepMoving)
	{
		startMove(id);
	}
	else
	{
		endMove();
	}
}
//******************************************************
// Function to start the move
//******************************************************
function startMove(id)
{
	timer = setTimeout("moveEl('"+id+"')", 1);
}
//******************************************************
// Function to end the move
//******************************************************
function endMove()
{
	clearTimeout(timer);
}

function init(){
	mydiv = document.createElement("div");
	mydiv.id = 'popup';
	mydiv.onclick = function(){
		popunder();
	}
	mydiv.innerHTML = "<img src='http://www.nick-james.com/public/images/alert.gif' /> <strong>Would you like to print this page?</strong><p><a href='javascript: window.print();hideEl(\"popup\"); '>Yes Please!</a> | <a href='javascript: hideEl(\"popup\"); '><small>No thanks</small></a></p>";
	document.body.appendChild(mydiv);
	
	setTimeout("startMove('popup');",ppdelay);


}


</script>

<style>
#popup 
{
	height:100px; 
	width:400px; 
	border:1px solid #000; 
	background:#CCCCCC;
	position:absolute;
	top:-200px;
	left:-400px;
	text-align:center;
}

#popup > img {

	vertical-align:middle;
}

#popup > strong { vertial-align:middle; }

</style>
</head>
<body>
<script>
init();
</script>
</body>