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

The third and final milestone of this project is the Client Report. 
The team's client report can be found here: 
<a href="{{ '/assets/report.pdf' | relative_url }}">Download Report</a> in PDF format.

# Milestones

- [Milestone 1: Client Pitch](#milestone-1-client-pitch)
- [Milestone 2: Functional Prototype](#milestone-2-functional-prototype)
- [Milestone 3: Client Report](#milestone-3-client-report)

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
<img width="390" height="527" alt="Image" src="https://github.com/user-attachments/assets/8df04749-ed0b-4eed-95b5-19ec3366a3fa" />

<img width="436" height="543" alt="Image" src="https://github.com/user-attachments/assets/e1a31c5e-1622-4480-ad7c-215b5f8dbb23" />

# Milestone 3: Client Report

<h1>Guardians of the Grapevine Client Report</h1>

<p><strong>Team Members:</strong> Ash Puri, Henry Ainscough, James Larrabee, Katherine Krishtopa, Skylar Walcoff<br>
<strong>Clients:</strong> Cornell CALS Extension / E&amp;J Gallo Winery / National Grape</p>

<h2>Context & Problem Statement</h2>
<p>
Commercial vineyards in the NY region are increasingly impacted by spotted lanternfly (SLF) infestations, which reduce fruit quality and weaken overall plant health. Current control methods rely heavily on pesticides, which can compromise produce safety.
</p>

<p>
Our project focuses on attracting SLFs and diverting them away from grapevines. By doing this, we aim to preserve fruit quality and minimize reliance on pesticides. Practical constraints include access to an electrical power source for the zapping mechanism and noise pollution caused by the vibrating mechanism.
</p>

<h2>Impact</h2>
<p>
The proposed approach reduces both grape contamination and reliance on pesticides, resulting in lower crop loss. In turn, this improves marketability by supporting organic practices and enhancing overall fruit quality and taste. It also promotes a more sustainable and environmentally cautious growing process, aligning with increasing consumer demand for cleaner agricultural practices.
</p>

<h2>Solution Direction</h2>
<p>
Our solution is a non-chemical, selective, and scalable device that attracts and eliminates SLFs to protect grapevines and preserve harvest quality. The concept centers on a pole that vibrates at approximately 60 Hz, based on research indicating that SLFs are attracted to this frequency. Once the insects are drawn to the device, the pole uses an electrified zapping mechanism to eliminate them upon contact.
</p>

<h2>Final Prototype: Vibrating Zapper Column</h2>

<p><strong>What it is:</strong><br>
The device consists of a vertical pole mounted on a base that houses a motor-driven vibration mechanism. The motor rotates a cam, which converts rotational motion into lateral vibrations of the pole. Initially, the prototype produced vibrations around 25 Hz, but through gear ratio adjustments, the system was refined to reach the target 60 Hz frequency.
</p>

<p>
Once attracted, SLFs move onto the pole, where a zapping system using two conductive sheets, similar to insect mesh, is integrated. When insects make contact across the conductive surfaces, they complete an electrical circuit and are eliminated.
</p>

<p><strong>How it would be used:</strong></p>
<ul>
<li>Placed between vineyard rows</li>
<li>SLFs are attracted to the 60 Hz frequency</li>
<li>SLFs are zapped when they land on the column</li>
<li>Can function during the growing season</li>
</ul>

<p><strong>Why it’s better than the status quo:</strong></p>
<ul>
<li>No chemicals or manual labor</li>
<li>No contamination or fruit bruising</li>
<li>Provides a targeted pest-control method</li>
<li>Can be scaled across vineyards</li>
</ul>

<h2>In-Depth Application</h2>
<p>
This device is designed to be portable and easily deployed throughout a vineyard, allowing growers to position units wherever infestations are most concentrated. Growers can adjust placement based on vine density and pest activity, allowing the device to integrate easily into existing vineyard operations.
</p>

<p>
Because the system requires minimal setup and maintenance, it can be used without disrupting daily workflows or harvesting processes. Its practicality also makes it suitable for vineyards of varying sizes, from small operations to large-scale commercial fields. Overall, the device provides a convenient and adaptable solution that allows for quick and easy implementation across vineyards.
</p>

<h2>Final Prototype Design</h2>

<p><strong>Fig. 1:</strong> Overall picture of final design</p>
<p><strong>Fig. 2:</strong> Sketch of design</p>

<h2>Conclusion and Recommendation</h2>
<p>
Based on our design development and testing results, we recommend advancing the Vibrating Zapper Column to field-testing in a vineyard environment. The prototype successfully met all key success criteria, including achieving 60 Hz vibration frequency, operating for 5 minutes without failure, and tolerating 10 N of lateral force without deformation.
</p>

<p>
To support successful field implementation, we recommend minor improvements such as incorporating weather-resistant materials, optimizing the power supply through solar integration, and enhancing durability for long-term outdoor use. Field-testing will also allow for improvement of device spacing, pest reduction effectiveness, and performance under varying environmental conditions.
</p>

<p>
If taken to market, several design improvements would further enhance performance. These include switching to fully weatherproof materials, such as stainless steel, replacing the motor with a speaker system for more efficient frequencies, and scaling the device to a size comparable to a vine to increase its area of influence. Overall, the device is promising and ready for field-testing.
</p>

<h2>Final Testing and Results</h2>

<h3>60 Hz Vibration Test</h3>
<p>
We tested whether the device achieved the target vibration frequency, which is essential for attracting SLFs. Using the PhyPhox app, we measured the output and confirmed a frequency of 60 Hz. This verifies that our gear ratio adjustments were successful and that the device meets its primary functional requirement.
</p>

<h3>Continuous Operation Test</h3>
<p>
To evaluate reliability, we ran the device continuously for 5 minutes. The mechanism maintained consistent performance with no signs of wear, damage, or failure. This indicates the device can operate for extended periods with minimal maintenance, making it suitable for real-world vineyard use.
</p>

<h3>Lateral Force Test</h3>
<p>
We tested structural stability by applying a lateral force to the pole to simulate environmental forces such as wind. The structure withstood up to 10 N of force before deformation. This confirms that the device is mechanically stable and capable of maintaining performance under typical field conditions.
</p>

<p>
Overall, the device successfully met all defined success criteria, demonstrating strong performance in functionality, long-term durability, and structural stability. These results indicate that the design will be effective and safe if used in real vineyards.
</p>

<h2>Initial Prototype and Testing Details</h2>
<p>
Our assembly was done in a simple manner. We used Fusion to CAD a base plate that could hold all of our components. Inside the designed base plate, we included slots for the motors, batteries, and gear axles so that the final construction would be simple and organized.
</p>

<p>
Using the CAD-designed base plate and the components ordered from McMaster, we first inserted the pole into its slot. We then placed the motor and gear system inside the base. After those components were settled, we inserted the battery and wiring so the internal parts would not be interfered with.
</p>

<p>
Next, we placed insect mesh around the pole and fastened it using zip ties, creating a non-conductive surface to attach the next layer of insect mesh. We then placed the second mesh on the outside of the zip ties and secured it to the previous mesh. Finally, we attached wires from the meshes to a power supply, creating the bug-zapping mechanism.
</p>

<h2>Primary Testing and Improvements</h2>

<h3>1. Vibration Frequency Test</h3>
<p>
PhyPhox, a smartphone application, was used to measure the vibration frequency of the initial prototype, which was recorded at 25 Hz. This was below the target frequency required to effectively attract SLFs.
</p>

<p><strong>Improvement:</strong> We adjusted the gear ratios to increase the rotational speed of the driven shaft to 3600 rpm, corresponding to the desired 60 Hz frequency.</p>

<h3>2. Continuous Operation Test</h3>
<p>
To assess durability, we ran the device continuously for 5 minutes. While the mechanism remained functional and intact, the wooden cam caused noticeable damage to the pole due to repeated impact.
</p>

<p><strong>Improvement:</strong> We replaced the wooden cam with a softer rubber cam that rotates within the tube, significantly reducing wear and improving long-term durability.</p>

<h3>3. Lateral Force Test</h3>
<p>
We applied a lateral force to the pole to evaluate structural stability, reaching 5 N without deformation. While this was acceptable for the prototype stage, further improvement was needed for real-world conditions.
</p>

<p><strong>Improvement:</strong> We refined the design by making the base plate opening slightly narrower, reducing pole movement and increasing overall stability.</p>

<h2>References</h2>
<p>
Throughout the design process, we sought guidance from Professor V. Hunter Adams from Cornell’s Electrical and Computer Engineering department, who provided valuable insight into vibration generation and system design. From this discussion, we learned that a speaker-based system would be more effective for producing low-frequency vibrations on the order of tens of Hz, although we continued with a motor-based approach due to budget constraints.
</p>

<p>
We also received guidance on optimizing the zapping mechanism, specifically the use of a dual-layer conductive mesh system where the SLF completes the circuit upon contact. Incorporating expert feedback allowed us to move beyond initial concepts and develop a more informed and functional solution.
</p>

<h2>Bill of Materials</h2>

<table border="1" cellpadding="8" cellspacing="0">
<tr>
<th>Part</th>
<th>Specs</th>
<th>McMaster Code</th>
<th>Fabrication Details</th>
<th>Reasoning</th>
<th>Cost</th>
</tr>

<tr>
<td>Base Plate</td>
<td>Custom-designed base plate for final system</td>
<td>NA</td>
<td>CAD + 3D Print</td>
<td>Holds and secures all components in place</td>
<td>$50</td>
</tr>

<tr>
<td>Pole</td>
<td>Outer Diameter: 1.75 in, Inner Diameter: 1.375 in, Impact-Resistant Polycarbonate Round Tube</td>
<td>8585K88</td>
<td>NA</td>
<td>Transmits vibration</td>
<td>$15.44</td>
</tr>

<tr>
<td>DC Gear Motor</td>
<td>60 Hz frequency, torque of 0.02 Nm, power around 7W, speed of 3600 RPM</td>
<td>In house</td>
<td>NA</td>
<td>Drives the vibration mechanism</td>
<td>$1.95</td>
</tr>

<tr>
<td>Electric Screen</td>
<td>24" Wide Aluminum Insect Screening, Unfinished</td>
<td>1023A75</td>
<td>Cut to size using scissors</td>
<td>Surface for zapping</td>
<td>$8.96</td>
</tr>

<tr>
<td>Zip Ties</td>
<td>Standard lab zip ties</td>
<td>In house</td>
<td>NA</td>
<td>Secures the electric screen</td>
<td>$0.00</td>
</tr>

<tr>
<td>AA Batteries</td>
<td>3 AA batteries</td>
<td>In house</td>
<td>NA</td>
<td>Powers the motor</td>
<td>$0.00</td>
</tr>

<tr>
<td>Battery Holder</td>
<td>AA battery holder with wire leads</td>
<td>In house</td>
<td>Wires soldered to motor</td>
<td>Holds batteries and supplies power</td>
<td>$0.00</td>
</tr>

<tr>
<td>AC Adaptor</td>
<td>12VDC, 1500mA, AC Adaptor</td>
<td>In house</td>
<td>NA</td>
<td>Powers the electric field</td>
<td>$0.00</td>
</tr>
</table>

<p><strong>Total Cost:</strong> $76.35</p>

<img width="466" height="523" alt="Image" src="https://github.com/user-attachments/assets/c5f41d85-80dd-4804-9219-a3a5f471ca49" />
