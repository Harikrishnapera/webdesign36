//Project Javascript File

function register()
{
	//alert();
	var nobj=document.getElementById('name');
	alert(nobj.value);
	//var name=nobj.value;
	//window.location.href="../../python/store.py?n=name";
}
function login()
{
	//alert();
	/*
	 dummy user:
	
	*/
	var username="harikrishna";
	var pass="123456";
	var uname=document.getElementById('unameid');
	//var upass=document.getElementById('upass');
	var msg=document.getElementById('logmsg');
	//alert(upass.value);
	//alert(uname.value==username);
	//alert(upass.value==pass);
	//alert(uname.value==username && upass.value==pass);
	if(uname.value==username)
	{
		msg.innerHTML="Login Successful";
		msg.style.color="green";
		
	}
	else{
		
		msg.innerHTML="Invalid Username";
		msg.style.color="red";
	}
	
}

function mcheck()
{
	var x=document.getElementById('mob');
	var y=document.getElementById('msg');
	var m=x.value;
	if(!(isNaN(m)) && m.length==10)
	{
		y.innerHTML="Valid Mobile Number";
		y.style.color="green";
	}
	else
	{
		y.innerHTML="Invalid Mobile Number";
		y.style.color="red";
	}
}