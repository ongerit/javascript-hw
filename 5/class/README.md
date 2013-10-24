#####Notes for October 23 2013
INDENTATION! INDENTATION!

#####Important to Note
*Where am I going? 

*When I get there what do I want to do?

*Image rollover? 


####Form object 
1. Form

2. GET & POST
* On the server-side 
* HTTP is the language the user uses to connect to the server
*GET is going to ask the browser to collect the name value pair. The name of the field and the value associated with the pair. 
*URL encoding-when a space is passed you get %20

```

```

####MIDTERM

On submit is an event listener. onClick, onSubmit, onBlur

```
	if (document.form1.fullname.value == "")				//--- validate fullname
	{
		alert('Please enter your name !!!');
		return(false);
	}

```

*The first part of the function is how to get there "if (document.form1.fullname.value == "")"

*End the function and return the value
*Return false cuts the process

```
	return(false);

```

###Object in an array
view-source:http://oit.scps.nyu.edu/~sultans/javascript/demo/4dom/option.html
```
var Models =							//an object containing arrays 
{
 CHEV : ['Cobalt','Corvette','Impala','Malibu','Avalanche','Suburban','Tahoe','TrailBlazer','Silverado'], 
 CADI : ['CTS','DTS','STS','XLR Roadster','SRX Crossover','Escalade','ESV','EXT'], 
 GMC  : ['Envoy','Sierra','Yukon','Savana','Denali'],
 CHRS : ['300','Aspen','Crossfire','Pacifica','PT Cruiser','Sebring','Town & Country'],
 JEEP : ['Wrangler','Liberty','Grand Cherokee','Patriot','Compass','Commander'],
 FORD : ['Focus','Taurus','Fusion','Escape','Explorer','Expedition','Ranger','F-150'],
 LINC : ['MKS','Town Car','Navigator'],
 TOYO : ['Corolla','Camery','Avalon','Matrix','Prius','Yaris','Rav4','Tacoma','Tundra','4Runner','Land Cruiser'], 
 NISS : ['Centra','Altima','Maxima','Quest','Z','Murano','Xterra','Pathfinder','Armada','Titan'], 
 HOND : ['Civic','Accord','CR-V','Element','Odyssey','Pilot'], 
 LEXS : ['IS250','ES300','GS400','LS400','RX350','GX450','LX450'], 
 BMW  : ['328i','528i','750','X3','X5','Z4','M'], 
 AUDI : ['A3','A4','A6','A8','TT','Q7'], 
 VOLV : ['S40','S60','S80','V50','V70','XC70','XC90']
} 

```

*Object is a square box with limited values
