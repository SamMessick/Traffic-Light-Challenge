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
<h4>Update 10/7/2017</h4>
<p>The original switching logic could have been further<br>
   minimized with a completely NOR-NOR implementation of each<br>
   output and next state. In addition, state changes required<br>
   more than one bit to change at a time. When implemented, <br>
   the circuit functioned as expected (followed the state diagram)<br>
   but did so one state change in advance of the expected<br>
   state. This error is resolved in my second implementation, <br>
   Updated-CMOS-Switching-Logic.jpg. The updated circuit <br>
   is featured at <a href="http://tinyurl.com/y8h3a9r5">this link</a>.
</p>
<h4>Update 10/7/2017</h4>
<p>The second switching logic could have been further<br>
   minimized by matching the states to the desired outputs.<br>
   When implemented, the circuit functioned as expected 
   (followed the finalstate diagram). The updated circuit <br>
   is featured at <a href="http://tinyurl.com/ybppz98f">this link</a>.
</p>
