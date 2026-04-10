---
layout: project
title: Spotted Lanternfly Project 
description: Ongoing Mechanical Design Project 
technologies: [N/A]
image: /assets/images/SFL.jpeg
---

The project is an engineering design challenge where the team acts hired by vineyard and agricultural partners to solve a real farming problem: spotted lanternflies damaging grape crops. Current control methods rely heavily on pesticides, which can contaminate grapes and reduce harvest quality, while washing harvested grapes is impractical because many are crushed during mechanical harvesting 

Our goal is to develop a non-chemical pest control system that protects grape quality and maintains harvesting efficiency. To do this, we must propose and justify a device or ecological intervention (such as a mechanical trap or biological control), evaluate safety and feasibility, and design a plan for testing a prototype. Ultimately, the project combines environmental impact, agricultural practicality, and engineering design to create a realisti and deployable solution for vineyards.

The first milestone of this project is the Client Pitch. 
The team's pitch can be found here: 
<a href="{{ '/assets/Guardians_of_the_Grapevine_Client_Pitch.pdf' | relative_url }}">Download Pitch</a> in PDF format.


The second milestone of this project is the Functional Prototype. 
The team's first functional prototype can be found here: 
<a href="{{ '/assets/Prototype.pdf' | relative_url }}">Download Prototype</a> in PDF format.



# Milestones

- [Milestone 1: Client Pitch](#milestone-1-client-pitch)
- [Milestone 2: Functional Prototype](#milestone-2-functional-prototype)

# Milestone 1: Client Pitch

<p><strong>Team:</strong> Guardians of the Grapevine<br>
<strong>Clients:</strong> Cornell CALS Extension / E&amp;J Gallo Winery / National Grape</p>

<h2>Problem Statement</h2>
<p>
Commercial vineyards in the NY region are struggling with spotted lanternfly infestations that reduce fruit quality and weaken vines. 
Pesticide use risks contaminating grapes, and fruit washing is impractical since around 50% of mechanically harvested grapes turn into “grape soup,” reducing yield. 
Growers need a non-chemical control method that protects harvest efficiency and fruit quality.
</p>

<h2>Impact</h2>
<p>
Reduced grape contamination and pesticide use, leading to lower crop loss and increased marketability due to organic practices and improved taste.
</p>

<h2>Concept A: Vibrating Zapper Column</h2>

<p><strong>What it is:</strong><br>
A tall metal column that vibrates at 60 Hz. It includes a retractable Faraday cage that drops and delivers an electric current to eliminate lanternflies inside.
</p>

<p><strong>How it would be used:</strong></p>
<ul>
<li>Placed between vineyard rows</li>
<li>Cage drops and zaps when flies enter</li>
<li>Lanternflies are attracted to 60 Hz frequency</li>
</ul>

<p><strong>Why it’s better than the status quo:</strong></p>
<ul>
<li>No chemicals or manual labor</li>
<li>No contamination or fruit bruising</li>
<li>Operates during the growing season</li>
</ul>

<p><strong>Proof of Concept:</strong><br>
A small-scale prototype can be built and tested in controlled outdoor conditions using substitutes for live insects.
</p>

<h2>Concept B: Bat Box</h2>

<p><strong>What it is:</strong><br>
A wooden structure designed to attract natural predators of spotted lanternflies using UV light cues and thermal insulation.
</p>

<p><strong>How it would be used:</strong></p>
<ul>
<li>Installed at vineyard perimeters</li>
<li>Increases bat population near vineyards</li>
<li>Operates during peak infestation periods</li>
</ul>

<p><strong>Why it’s better than the status quo:</strong></p>
<ul>
<li>No chemicals used</li>
<li>Low maintenance system</li>
<li>Promotes ecological pest control</li>
</ul>

<p><strong>Proof of Concept:</strong><br>
A prototype can be installed in a local forest and monitored for bat activity.
</p>

<h2>Key Risks</h2>
<ul>
<li>Electrical safety concerns in outdoor environments</li>
<li>Potential harm to non-target species</li>
<li>Uncertainty about lanternfly response to 60 Hz frequency</li>
</ul>

<p>
These risks will be addressed through field testing and consultation with electrical safety experts.
</p>

<h2>Questions for Client</h2>
<ol>
<li>
<strong>What percentage reduction in SLFs defines success?</strong><br>
Determines cost targets and number of devices needed.
</li>
<li>
<strong>What regulations apply to unmonitored electrical devices in vineyards?</strong><br>
Impacts system design and safety requirements.
</li>
<li>
<strong>What spacing constraints exist between vineyard rows and perimeters?</strong><br>
Affects device size and placement.
</li>
</ol>

# Milestone 2: Functional Prototype

<h1>Design Documentation</h1>

<h2>Components List</h2>

<table border="1" cellpadding="8" cellspacing="0">
<tr>
<th>Component + Specs</th>
<th>McMaster Code</th>
<th>Fabrication Details</th>
</tr>

<tr>
<td>Impact-Resistant Polycarbonate Tube, 1/16" Wall Thickness, 1-3/4" OD, 1-5/8" ID</td>
<td>8585K88</td>
<td>NA</td>
</tr>

<tr>
<td>Motor: Mabuchi-55, 1.5 VDC, 1350 RPM, 0.32 Amps, 6 g-cm, 50% efficiency, Jameco Part #2209094</td>
<td>NA</td>
<td>NA</td>
</tr>

<tr>
<td>Base Plate, Material: PLA</td>
<td>NA</td>
<td>CAD then 3D printed at RPL</td>
</tr>

<tr>
<td>Battery Pack: 4 AA batteries</td>
<td>NA</td>
<td>Batteries put into black box and connected to the motor via wires</td>
</tr>

<tr>
<td>Cardboard</td>
<td>NA</td>
<td>Manually cut and shaped to create a mounting surface for motor</td>
</tr>

<tr>
<td>Tape</td>
<td>NA</td>
<td>NA</td>
</tr>

<tr>
<td>Balsa Wood: petal shaped</td>
<td>NA</td>
<td>Used a dremel for the hole and shaped using sandpaper</td>
</tr>
</table>

---

<h2>Assembly Instructions</h2>

<ol>
<li>
<strong>Base Fabrication:</strong> The structural base was designed using CAD to ensure accurate dimensions and internal clearances. A central hole and internal support feature were included to stabilize the tube. The base was then 3D printed in the Rapid Prototyping Lab (RPL).
</li>

<li>
<strong>Tube Installation:</strong> A plastic tube was inserted vertically into the base. Internal supports ensured alignment and stability, especially under vibration.
</li>

<li>
<strong>Electrical System Setup:</strong> A DC motor was connected to a battery pack using insulated wires in a simple closed circuit. Connections were tested prior to integration.
</li>

<li>
<strong>Motor Mounting:</strong> A cardboard platform was attached to stabilize the motor and increase contact area. The motor was secured inside the base using tape.
</li>

<li>
<strong>Cam Design and Fabrication:</strong> The design evolved from a small snail cam to a larger asymmetric cam made from balsa wood, improving motion and displacement.
</li>

<li>
<strong>Cam Integration:</strong> The cam was aligned to periodically contact the tube bottom during rotation, ensuring consistent interaction without excessive friction.
</li>

<li>
<strong>Final Assembly and Testing:</strong> The system was fully assembled and tested. The rotating cam induces vibrations in the tube, confirming functionality.
</li>
</ol>

<p><strong>Overall Function:</strong> The device converts rotational motion from the motor into periodic vertical impacts, producing oscillatory motion in the tube.</p>

## Assembly Steps
<img width="563" height="676" alt="Image" src="https://github.com/user-attachments/assets/e87fa83f-14d0-45db-b9fa-3697036cd974" />

<img width="556" height="701" alt="Image" src="https://github.com/user-attachments/assets/f2fdcd62-7dab-4a37-b1e1-e191b74d1e30" />

<img width="559" height="460" alt="Image" src="https://github.com/user-attachments/assets/ed6c0e05-09ae-4866-b640-2a17045a1efc" />
---

<h2>Success Criteria</h2>

<p>
The product attempts to eliminate spotted lanternflies by vibrating at ~60 Hz and zapping them. The frequency attracts the insects, enabling effective removal.
</p>

<h3>Criterion 1: Vibration Frequency</h3>
<ul>
<li>Rod must produce ~60 Hz vibration</li>
<li>Prototype success threshold: ~20–30 Hz</li>
<li>Measured using vibration analysis app (PhyPhox)</li>
<li>Demonstrated via live testing</li>
<li>High priority for system effectiveness</li>
</ul>

<h3>Criterion 2: Vibration Consistency</h3>
<ul>
<li>System must sustain vibration over time</li>
<li>Test: run at ~60 Hz for 5 minutes</li>
<li>Measured via timer + smartphone analysis</li>
<li>Acceptable if near-target frequency is maintained</li>
<li>Important but slightly lower priority than attraction</li>
</ul>

<h3>Criterion 3: Vibration Detectability</h3>
<ul>
<li>Vibration must be physically detectable</li>
<li>Test: 15/15 participants feel vibration</li>
<li>Used as proxy for insect detectability</li>
<li>Can be demonstrated live</li>
<li>Critical for effectiveness</li>
</ul>

<h3>Criterion 4: Structural Stability</h3>
<ul>
<li>Rod must remain upright during operation</li>
<li>Must support applied force (~5 N for 5 minutes)</li>
<li>Test includes pushing force or weight application</li>
<li>Demonstrated by stable operation during exhibition</li>
<li>High priority to prevent system failure</li>
</ul>

<p><strong>Exhibition Requirements:</strong></p>
<ul>
<li>Run continuously for 5 minutes</li>
<li>Maintain structural stability</li>
<li>Show consistent ~60 Hz vibration signal</li>
<li>Allow audience to feel vibration</li>
</ul>

<h2>Design Tests</h2>

<h3>Motion and Interference</h3>

<p><strong>What will be tested:</strong> Vibration frequency of the rod and whether the vibration is transmitted along the full length of the rod.</p>

<p><strong>Why will it be tested:</strong> The system must produce a vibration around 60 Hz to attract spotted lanternflies. The vibration must also propagate along the rod so that it can be detected upon contact.</p>

<p><strong>Success Criterion tested:</strong><br>
Criterion 1: Vibration Frequency<br>
Criterion 2: Vibration Consistency<br>
Criterion 3: Vibration Detectability
</p>

<p><strong>How it will be tested:</strong> A smartphone vibration analysis app (such as PhyPhox) will be used to measure frequency and generate a graph for analysis.</p>

<p><strong>Testing Calculations:</strong> T = 60 - 20 = 40 ms = 0.04 s → Frequency = 1/T = 25 Hz</p>

<p><strong>Results of testing (Pass/Fail):</strong> Pass for all three criteria. The prototype produced a frequency of 25 Hz. Motion was primarily rotational and remained consistent for 5 minutes. The vibration was detectable by touch and sound.</p>

<p><strong>Design Changes Needed:</strong> A stronger motor is needed to reach closer to 60 Hz. Rotational motion should be reduced in favor of vertical and horizontal vibration (x and z directions) to improve lanternfly interaction.</p>

---

<h3>Load Bearing and Structural Integrity</h3>

<p><strong>What will be tested:</strong> Ability of the rod to remain upright under applied force.</p>

<p><strong>Why will it be tested:</strong> The rod must withstand forces such as lanternfly weight and wind without tipping. Stability prevents component damage and maintains effective contact area.</p>

<p><strong>Success Criterion tested:</strong> Criterion 4: Structural Stability</p>

<p><strong>How it will be tested:</strong> A Newton-meter will be attached to the rod. Forces will be applied while measuring displacement and stability.</p>

<p><strong>Results of testing (Pass/Fail):</strong> Pass. The rod remained upright under 5 N of force with no permanent deformation.</p>

<p><strong>Design Changes Needed:</strong> Minor reinforcement of the base through improved 3D printing will enhance durability. No major changes required.</p>

---

<h3>Repeat Use / Cycle Testing</h3>

<p><strong>What will be tested:</strong> Consistency of vibration over time.</p>

<p><strong>Why will it be tested:</strong> The system must operate continuously without failure. Stable vibration is necessary to consistently attract spotted lanternflies.</p>

<p><strong>Success Criterion tested:</strong><br>
Criterion 2: Vibration Consistency<br>
Criterion 4: Structural Stability
</p>

<p><strong>How it will be tested:</strong> The system will run continuously for 5 minutes while frequency is recorded at the beginning, middle, and end using a vibration analysis app. Stability will also be observed.</p>

<p><strong>Results of testing (Pass/Fail):</strong> Pass for both criteria. The system ran continuously for 5 minutes, maintained a frequency of 25 Hz ± 5 Hz, and did not tip over.</p>

<p><strong>Design Changes Needed:</strong> Increase frequency toward 60 Hz by selecting a stronger motor (e.g., from McMaster-Carr or Amazon). Consider a more durable rod material due to observed wear at the base contact point.</p>

<h2>Illustration and Intent of the Design</h2>

<p><strong>Explanation:</strong></p>

<p>
The base of the prototype serves as the foundation for the entire system and maintains the structural integrity of all components. It houses both the motor and the switch, which together generate the vibration of the pole. In future iterations, the base will also contain the electronic components required to power the bug-zapping mechanism.
</p>

<p>
The pole functions as the primary method of attracting spotted lanternflies, as research indicates they are drawn to sources emitting vibrations around 60 Hz. The motor and cam mechanism work together to periodically strike the pole, inducing vibrations that propagate along its length.
</p>

<p><strong>Sketch Book Design:</strong></p>
