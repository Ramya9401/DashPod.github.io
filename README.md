# Employee Details

<h3>Index</h3>
<ol>
<li><a href="#Introduction">Introduction</a></li>
<li><a href="#Flowchart">Flow Chart</a></li>
<li><a href="#algorithm">Algorithms</a>
  <ul>
    <li><a href="#main">Main Program</a></li>
     <li><a href="#create">Create Employee Details</a></li>
     <li>Get person details</li>
     <li>Get salary details</li>
     <li>validation of name</li>
     <li>validation of date</li>
     <li>Print the employee details</li>
    </ul>
  </li>
    </ol><br>

<h3 id="Introduction">Introduction</h3>
<p>The document briefs you on the program <b>Employee Details</b> using Structures. This program explains the usage of structure within structure and accesing of variables using pointers.</p><br>

<h3 id="Flowchart">Flow Chart</h3>

<br>
<h3 id="algorithm">Algorithms</h3>
<h4 id="main">Main Program</h4>
<ol>
<li>Start the Program.</li>
<li>Create structure for person details as <i>person</i> including firstname,lastname,date-of-birth and assign a variable to structure as <i>psn</i>.</li>
<li>Create structure for salary details as <i>salary</i> including initial salary,increment percentage,current salary,date-of-joining and assign a variable to structure as <i>sal</i>.</li>
<li>Create structure for employee details as <i>employee</i> including pointer variable of type struct person, pointer variable of type struct salary and assign a variable to structure as <i>emp</i>.</li>
<li>Declare variables single pointer "emp1", double pointer "new_emp" of type <i>emp</i> .</li>
<li>Assign address of "emp1" to "new_emp".</li>
<li>Call <i>Create</i> function passing the adress of "new_emp" as argument.</li>
<li>Call <i>Print</i> function passing the adress of "new_emp" as argument.</li>
</ol>

<h4 id="create">Create Employee Details</h4>
<ol>
<li>Allocate the memory of size struct <i>emp</i> to "new_emp".</li>
<li>Allocate the memory of size struct <i>sal</i> to struct sal variable in "new_emp".</li>
<li>Allocate the memory of size struct <i>psn</i> to struct psn variable in "new_emp".</li>

</ol>
