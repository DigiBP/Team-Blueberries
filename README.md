<h1 style="text-align: center">🫐Team-Blueberries🫐</br>Absence request process for a watchmaking company</h1>

<h2>Team members</h2>




<!-- Surname, name and email from all team members and from our coach -->
<table>
  <tr>
    <td style="font-weight: bold;">Name</td>
    <td style="font-weight: bold;">Email</td>
  </tr>
  <tr>
    <td>Caroline Rüdisühli</td>
    <td><a href="mailto:caroline.ruedisuehli@students.fhnw.ch">caroline.ruedisuehli@students.fhnw.ch<a/></td>
  </tr>
  <tr>
    <td>Charline Unternährer</td>
    <td><a href="mailto:charline.unternaehrer@students.fhnw.ch">charline.unternaehrer@students.fhnw.ch<a/></td>
  </tr>
  <tr>
    <td>Michael Vontobel</td>
    <td><a href="mailto:michael.vontobel@students.fhnw.ch">michael.vontobel@students.fhnw.ch<a/></td>
  </tr>
  <tr>
    <td>Sabina Portmann</td>
    <td><a href="mailto:sabina.portmann@students.fhnw.ch">sabina.portmann@students.fhnw.ch<a/></td>
  </tr>
</table>
</br>

<h2>Coach</h2>
<table>
  <tr>
    <td style="font-weight: bold;">Name</td>
    <td style="font-weight: bold;">Email</td>
  </tr>
  <tr>
    <td>Charuta Pande</td>
    <td><a href="mailto:charuta.pande@fhnw.ch">charuta.pande@fhnw.ch<a/></td>
  </tr>
</table>
</br></br>
<!-- Ending Surname, name and email from all team members and from our coach -->




<!-- Table of content -->
<h2>Table of content</h2>
<h3><a href="#1. Introduction">1. Introduction</a></h3>
<h4><a href="#1.1 Deliverables and Artefacts">1.1 Deliverables and Artefacts</a></h4>
<h4><a href="#1.2 Tools and platforms">1.2 Tools and platforms</a></h4>
<h4><a href="#1.3 Languages used">1.3 Languages used</a></h4>

<h3><a href="#2. Introduction of our Use Case">2. Introduction of our Use Case</a></h3>

<h3><a href="#3. Current situation">3. Current situation</a></h3>
<h4><a href="#3.1 As-Is Business Process">3.1 As-Is Business Process</a></h4>
<h4><a href="#3.2 Pain Points">3.2 Pain Points</a></h4>

<h3><a href="#4. Desired situation">4. Desired situation</a></h3>
<h4><a href="#4.1 To-Be Business Process">4.1 To-Be Business Process</a></h4>
<h4><a href="#4.2 Decision Tables">4.2 Decision Tables</a></h4>
<h5><a href="#4.2.1 Decision Table Absence from type">4.2.1 Decision Table Absence from type</a></h5>
<h5><a href="#4.2.2 Decision Table Absence from team capacity">4.2.2 Decision Table Absence from team capacity</a></h5>
<h4><a href="#4.3 Improvements">4.3 Improvements</a></h4>

<h3><a href="#5. Digitalization and Automation">5. Digitalization and Automation</a></h3>
<h4><a href="#5.1 Make scenario Google Forms process trigger">5.1 Make scenario "Google Forms process trigger"</a></h4>
<h4><a href="#5.2 Make scenario Inform the employee">5.2 Make scenario "Inform the employee"</a></h4>
<h4><a href="#5.3 Make scenario Inform the manager">5.3 Make scenario "Inform the manager"</a></h4>
<h4><a href="#5.4 Make scenario Confirm and sign HR">5.4 Make scenario "Confirm and sign HR"</a></h4>
<h4><a href="#5.5 Make scenario Send Confirmation to HR and Employee">5.5 Make scenario "Send Confirmation to HR and Employee"</a></h4>
<h4><a href="#5.6 Make scenario Send data to team schedule">5.6 Make scenario "Send data to team schedule"</a></h4>

<h3><a href="#6. Other artefacts">6. Other artefacts</a></h3>
<h4><a href="#6.1 Google Forms">6.1 Google Forms</a></h4>
<h4><a href="#6.2 Google Sheet Employee Absence Request Form (responses)">6.2 Google Sheet "Employee Absence Request Form (responses)"</a></h4>
<h4><a href="#6.3 Google Sheet Team schedule">6.3 Google Sheet "Team schedule"</a></h4>

<h3><a href="#7. Conclusion">7. Conclusion</a></h3>

</br></br>
<!-- Ending Table of content -->




<!-- Contenct -->
<!-- Introduction -->
<h2 id="1. Introduction">1. Introduction</h2>
This work was completed as part of a group project in the Digitalization of Business Processes module in the spring semester of 2023.
The first step was to analyze and model an existing process. In a second step, the existing process was to be optimized and automated as far as possible.
</br></br>

<h3 id="1.1 Deliverables and Artefacts">1.1 Deliverables and Artefacts</h3>
We following deliverables were mandatory:
<ul>
  <li>Link to GitHub repositories containing modelling artefacts and other project artefacts, if required, and a documentation (e.g., Readme and interlinked .md files).</li>
  <li>Link to a running workflow(s) and/or instatiation(s) of a link to start form(s) and/or cloud-based deployment(s).</li>
  <li>Link to presentation slides.</li>
</ul>
</br>

<h3 id="1.2 Tools and platforms">1.2 Tools and platforms</h3>
We had several DevOps-tools and development platforms available for our assessment.
We used the following:
<ul>
  <li>Camunda Modeler (Platform 7)</li>
  <li>GitHub</li>
  <li>Visual Studio Code</li>
  <li>Git</li>
  <li>Make</li>
  <li>Google</li>
</ul>
</br>

<h3 id="1.3 Languages used">1.3 Languages used</h3>
To fulfill our tasks, we used several languages:
<ul>
  <li>Hyper Text Markup Language (HTML) & Cascading Style Sheets (CSS)</li>
  <li>Business Process Modeling Notation (BPMN)</li>
  <li>Friendly Enough Expression Language (FEEL)</li>
  <li>Git commands</li>
</ul>
</br></br>
<!-- Ending Introduction -->




<!-- Use Case -->
<h2 id="2. Introduction of our Use Case">2. Introduction of our Use Case</h2>
&#129488;// Charline
</br></br>
<!-- Ending Use Case -->




<!-- Current situation -->
<h2 id="3. Current situation">3. Current situation</h2>
<p>Currently, when an employee wants to request a leave of absence, the process is time-consuming and almost entirely paper-based. The employee must first ask the secretary to print out a form that he can fill out and send to his manager. The manager can then validate the request, but does not have the possibility to consult the balance of available days or the attendance schedule of all employees in his team. If the manager refuses the request, he announces it to the employee, otherwise the request is forwarded to the HR team. The HR manager must also sign the form before passing it to an HR secretary. The HR secretary then verifies the presence of both signatures as well as the employee's available day balance (in the ERP). If everything is in order, the request is officially accepted.</p>
</br></br>

<h3 id="3.1 As-Is Business Process">3.1 As-Is Business Process</h3>
<p>The As-Is Business Process looks like this:</p> 
<img src="https://github.com/DigiBP/Team-Blueberries/blob/main/docs/AbsenceRequest_AS_IS.png" alt="As-Is Business Process">
</br></br>

<h3 id="3.2 Pain Points">3.2 ⚡Pain Points⚡</h3>
<ul>
  <li>Time-consuming and cascading process (several people involved).</li>
  <li>Paper-based process, not digitized.</li>
  <li>The manager does not have the possibility to consult the planning of his team.</li>
  <li>The manager does not have the possibility to consult the balance of available days of his employees.</li>
</ul>
</br></br>
<!-- Ending Current situation -->




<!-- Desired situation -->
<h2 id="4. Desired situation">4. Desired situation</h2>
<p>&#129488;// Please have a review @Charline. In the meantime, there have probably been some changes.</p>
<p>Proposed improvement: The implementation of a system that communicates with the ERP. This system is accessible to the HR team and all employees of the company, including managers.</p>

<p>When the employee wants to request a leave of absence, he will be able to log in to the system by fingerprint recognition. He will be able to check the number of vacation days still available, and if his balance is at 0, he will have the possibility to request an unpaid vacation. When the manager receives the request, he will be able to consult the planning of his team before making his choice. Finally, if the request is rejected, the employee will be informed, otherwise the HR team will be informed that a new absence request has been accepted.</p>
</br></br>

<h3 id="4.1 To-Be Business Process">4.1 To-Be Business Process</h3>
<p>The To-Be Business Process looks like this:</p>
<p>&#129488;// Add pic from our final to-be business process</p>
</br></br>

<h3 id="4.2 Decision Tables">4.2 Decision Tables</h3>
<p>To keep the modeling process as lean as possible, we used two decision tables (DMN).</p>
<p>In the first DMN it is first checked which type of absence is desired. This can be seen in the first line.</p>
<p>After that, there are a number of additional specifications that must be met in order for the test to be approved either automatically or provisionally. If a requirement is not met, the request is rejected.</p>
</br></br>

<h4 id="4.2.1 Decision Table Absence from type">4.2.1 Decision Table Absence from type</h4>
This table is the first step in identifying which type of absence is requested by the employee.

&#129488;// Pic from our final Decision Table Absence from type
</br></br>

<h4 id="4.2.2 Decision Table Absence from team capacity">4.2.2 Decision Table Absence from team capacity</h4>
<p>This table is the second step to ensure that the capacity of the team is not reached when an emyployee wants to take time off. The current capacity is set to &lt;50% of employees must be available.</p>

&#129488;// Pic from our final Decision Table Absence from team capacity
</br></br>

<h3 id="4.3 Improvements">4.3 Improvements</h3>
&#129488;// describe the improvements
</br></br>
<!-- Ending Desired situation -->




<!-- Digitalization and Automation -->
<h2 id="5. Digitalization and Automation">5. Digitalization and Automation</h2>
&#129488;// describe what we have done
</br></br>

<h3 id="5.1 Make scenario Google Forms process trigger">5.1 Make scenario "Google Forms process trigger"</h3>
&#129488;// Description and pic
</br></br>

<h3 id="5.2 Make scenario Inform the employee">5.2 Make scenario "Inform the employee"</h3>
&#129488;// Description and pic
</br></br>

<h3 id="5.3 Make scenario Inform the manager">5.3 Make scenario "Inform the manager"</h3>
&#129488;// Description and pic
</br></br>

<h3 id="5.4 Make scenario Confirm and sign HR">5.4 Make scenario "Confirm and sign HR"</h3>
&#129488;// Description and pic
</br></br>

<h3 id="5.5 Make scenario Send Confirmation to HR and Employee">5.5 Make scenario "Send Confirmation to HR and Employee"</h3>
&#129488;// Description and pic
</br></br>

<h3 id="5.6 Make scenario Send data to team schedule">5.6 Make scenario "Send data to team schedule"</h3>
&#129488;// Description and pic
</br></br>
<!-- Ending Digitalization and Automation -->




<!-- Other artefacts -->
<h2 id="6. Other artefacts">6. Other artefacts</h2>
&#129488;// describe what we have done
</br></br>

<h3 id="6.1 Google Forms">6.1 Google Forms</h3>
&#129488;// Description and pic
</br></br>

<h3 id="6.2 Google Sheet Employee Absence Request Form (responses)">6.2 Google Sheet "Employee Absence Request Form (responses)"</h3>
&#129488;// Description and pic
</br></br>

<h3 id="6.3 Google Sheet Team schedule">6.3 Google Sheet "Team schedule"</h3>
&#129488;// Description and pic
</br></br>
<!-- Ending Other artefacts -->




<!-- Conclusion -->
<h2 id="7. Conclusion">7. Conclusion</h2>
&#129488;// describe it
</br></br>
<!-- Ending Conclusion -->
<!-- Ending Content -->