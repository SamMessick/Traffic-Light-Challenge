<h3>Implementing a traffic-light state machine</h3>
<hr width="50%">
<p>
	These are my attempts at implementing a finite state machine of a traffic light. 
	My only restrictions are that the logic implementing the state machine must be:
</p>
<p><b>
	1.) Minimized <br>
	2.) Free of static hazards
</b></p> 
<p>	
	Any other design considerations are acceptable.
</p>
<hr width="50%">
<p>
	My method assigns each state a unique binary<br>
	name, reduces 3 "next-states" and 3 light outputs<br>
	using a next-state truth table and 6 Karnaugh maps.<br>
	Transistor count is then determined using traditional<br>
	CMOS logic gates (NOT, AND, NAND, and NOR).
<p>
	<i>If you have any suggestions</i> on how to<br>
	or simplify this finite state machine any <br>
	further or have another method of implementing <br>
	traffic light logic, submit a pull request. 
</p>
<p>
	<ins>Please include any relevant work with your schematic.</ins> 
</p>
