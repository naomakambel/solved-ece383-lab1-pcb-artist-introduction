Download Link: https://assignmentchef.com/product/solved-ece383-lab1-pcb-artist-introduction
<br>
<em>Goals: The goals of this lab are to introduce students to PCB Artist software to create schematic layouts and generate printed circuit board designs. An additional goal is the creation of a PIC24HJ128GP502 component in PCB Artist.</em>

<h1>1.  Introduction</h1>

This lab introduces students to PCB Artist software. PCB is an acronym that stands for <strong>P</strong>rinted <strong>C</strong>ircuit <strong>B</strong>oard. Students will learn how to design electronic circuits using PCB Artist’s schematic tool and then generate a layout of the design using the PCB tool. The final objective will be to design and implement a custom PIC24HJ128GP502 component in PCB Artist.




This lab requires you to capture portions of the screen. The lab computers use the Windows 10 operating system. This includes the “Snipping Tool” that may be used to capture portions of the screen. Other third party tools are also available.




As always, read through the entire lab and scan the supplied files before starting work. The reporting requirements have you verify your work to the teaching assistant (TA). In all cases, make it easy for the TA to verify your computations by showing your work. Note that this lab can be fully completed outside of the lab and demonstrated to the TA during lab session.




<h1>2.  PRELAB – TASK 1: Introduction to PCB Artist</h1>




For this task we will use video tutorials from Advanced Circuits to introduce PCB Artist and its associated schematic capture capabilities. View the seven step-by-step video tutorials located at <a href="http://www.4pcb.com/pcb-software-tips-tools.html">http://www.4pcb.com/pcb-software</a><a href="http://www.4pcb.com/pcb-software-tips-tools.html">tips-tools.html</a><a href="http://www.4pcb.com/pcb-software-tips-tools.html">.</a> These videos reflect the content of the <em>PCB Artist Introduction and Tutorial </em>that can be accessed from the <em>Help-&gt;Tutorials-&gt;Design Tutorial </em>menu within PCB Artist. Complete chapters 1 and 2 of the tutorial. You will be required to show the TA the completed schematic upon entering the lab.




Read the Printed Circuit Board basics tutorial at <a href="https://learn.sparkfun.com/tutorials/pcb-basics">https://learn.sparkfun.com/tutorials/pcb-basics</a> <a href="https://learn.sparkfun.com/tutorials/pcb-basics">a</a>nd answer the following questions. Provide typewritten answers to the following questions.




<ol>

 <li>Usually, a PCB is made of four known layers of different materials. Describe the four layers in your own words.</li>

 <li>Define the following terms in your own words: a) Finger, b) Pad, c) Panel, d) Plated through hole, e) Silkscreen, f) Soldermask, g) Surface mount, and h) Via.</li>

</ol>




<strong>TA check: Upon arrival in the lab, show the TA the circuit and the answers you completed. This circuit should closely resemble the completed tutorial circuit given on page 30 of the <em>PCB Artist Introduction and Tutorial </em>document. Include a printout of your circuit and answers in your lab report</strong>.




<h1>3.  TASK 2: 555 Timer Circuit Schematic with PCB Artist</h1>




Use PCB Artist to create the digital clock circuit given in Figure 1 below. This circuit includes the following components: a 10KΩ resistor (R<sub>A</sub>) a 100KΩ resistor (R<sub>B</sub>), a 1μF capacitor and a 555 timer chip. One possible PCB Artist layout of the circuit is shown in Figure 2. The LM555CJA integrated circuit may be found in the natsemi.cml component library. The capacitors and resistors may be found in the discrete.cml component library. Use the

“C”component for the capacitors and the “R<sub>A</sub>” component for the resistors.

<h2>Figure 1. 555 Timer-Based Digital Clock Circuit</h2>




<strong>Figure 2. PCB Artist Layout of 555 Timer-Based Digital Clock Circuit </strong>

<strong>TA check: Show the TA the circuit you completed. Include a printout of your circuit in your lab report</strong>.

<h1>4.  TASK 3: Creation of a Printed Circuit Board Layout with PCB Artist</h1>




For this task we will create a printed circuit board layout from the digital clock circuit schematic created as a part of task 2. Chapter 4 of the <em>PCB Artist Introduction and Tutorial </em>describes the basic process of converting the circuit schematic into a printed circuit board layout. Read from the beginning of chapter 4 to the section titled “<strong>Unrouting the design</strong>”. Use the described process using the <strong>Schematic To PCB </strong>wizard within PCB Artist. You can accept all the default choices provided by the wizard until the “Place and Route” dialog box is shown. Select “Arrange Outside the Board” for component placement and select “Next”. This will result in a PCB that will be similar to the diagram shown in Figure 3 below.

<h2>Figure 3. PCB Wizard Generated Design with Components Unplaced and Nets Unrouted</h2>

Select <em>Tools-&gt;Auto Place Components-&gt;All Components </em>to have PCB Artist auto-place all the circuit components onto the PCB. Select <em>Tools-&gt;Auto Route Nets-&gt;All Nets </em>to have PCB Artist auto-route all the circuit networks (i.e. connections between components) on the PCB. This will result in a printed circuit board similar to the one shown in Figure 4 below.




<h2>Figure 4. Printed Circuit Board with all Components Placed and all Nets Routed</h2>

<strong> </strong>

<strong>TA check: Show the TA the printed circuit board you completed. Include a printout of your PCB in your lab report</strong>.




<h1>5.  TASK 4: PIC24HJ128GP502 Schematic Symbol, PCB Footprint, and Component in PCB Artist</h1>




For this task you will create a component for the PIC24HJ128GP502 microcontroller in PCB Artist. Begin by reading  and  completing  the  Library  Creation  Tutorial  within  PCB  Artist  (<em>Help-&gt;Tutorials-&gt;Part  Creation Tutorial</em>). After completing the tutorial, perform the following steps:




<ul>

 <li>Within the Library Manager, create a new schematic symbol library called ece383.ssl. Use the Symbol Wizard tool to create a schematic symbol called PIC24HJ128GP502. Example screen captures for this wizard are shown below.</li>

</ul>

<strong> </strong>

<strong> </strong>

<h2>Figure 5. Click New Lib … button to make ece383 folder</h2>










<h2>Figure 6. Technology and Unit Selection</h2>







<h2>Figure 7. Symbol Type, Origin, and Component Name Position</h2>










<h2>Figure 8. Symbol Pin and Line Styles</h2>







<h2>Figure 9. Pin Layout</h2>










<h2>Figure 10. Symbol Naming and Final Creation Step</h2>




<ul>

 <li>Within the Library Manager, create a new component library called ece383.cml. Use the Component Wizard tool to create a component called PIC24HJ128GP502. Example screen captures for this wizard are shown below.</li>

</ul>




<h2>Figure 11. Click New Lib… to make ece383.cml file in components tab</h2>







<h2>Figure 12. Create a Normal Component Type</h2>







<h2>Figure 13. Component Details</h2>










<h2>Figure 14. Schematic Symbol to Use</h2>







<h2>Figure 15. PCB Symbol to Use (DIP28_300 from the prolib.psl Library)</h2>










<h2>Figure 16. Assign Pins (Use the Assign 1-to-1 Function)</h2>













<h2>Figure 17. Save the Component in the Component Library</h2>




<ul>

 <li>Edit the component and provide terminal names for each pin as shown in the figure below. The terminal names will closely match those given in the PIC24HJ128GP502 diagram shown on page 4 of the PIC24 datasheet on the class website. Save the edited component in the component library.</li>

 <li>Close all the windows. Click either F8 or Add Component button. Find the “ece383.cml” library. Select the PIC24HJ128GP502 and click add. The placed component should resemble that shown in Figure 19.</li>

</ul>







<h2>Figure 18. Component Terminal/Pin Naming</h2>




<strong>TA check: Add the created component to a schematic design and show the TA the component placement within the schematic. Use a screen capture tool to capture the schematic window and include it in your lab report. An example screenshot is given below</strong>.




<strong>Figure 19. PIC24HJ128GP502 Placement in a Schematic</strong>




<h1>6.  Laboratory Report</h1>




No later than a week from the day the lab is performed, provide the TA a printed copy of a lab report following the ECE383 Lab report Template given on the class website. Each lab group will submit one joint lab report to the TA. Your report should have the reporting requirements needed for Tasks 1, 2, 3 and 4.


