<h1>Design Documentation</h1>

<h2><u>Components List</u></h2>

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

<h2><u>Assembly Instructions</u></h2>

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
