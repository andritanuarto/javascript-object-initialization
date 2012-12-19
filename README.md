javascript-object-initialization
================================

a very simple example of javascript object initialization

In many cases an object can have more than one property, object  initialization can be the way to go. 
Here is the example:

<code>computer = {drive:"floppy", cpu:"intel", ram:"ddr"}</code>

basicly it says in computer object has 3 properties drive, cpuand ram.

to get each property within the computer object, we just simply write


<code>computer.drive</code> for floppy<br/>
<code>computer.cpu</code> for intel<br/>
<code>computer.ram</code> for ddr<br/>
</br>
<code>document.write("I want a" + computer.drive + " and " + computer.cpu + " and " + computer.ram);</code>

<h2>Multiple functions in one object</h2>

<code>
apple={
  showDrive: function(){
		alert('samsung');
	},
	
	showCpu: function(){
		alert('amd');
	},
	
	showRam: function(){
		alert('ssd');
	}
}
</code>
<code>
apple.showDrive(); //samsung
apple.showCpu();  //amd
apple.showRam();  //ssd
</code>

